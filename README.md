Install Umbraco Specific Version
https://www.nuget.org/packages/Umbraco.Templates/13.0.0
dotnet new install Umbraco.Templates::13.0.0

# Ensure we have the version specific Umbraco templates
dotnet new install Umbraco.Templates::13.5.2 --force

# Create solution/project
dotnet new sln --name "MySolution"
dotnet new umbraco --force -n "MyProject" --friendly-name "Administrator" --email "admin@example.com" --password "1234567890" --connection-string "server=(local)\SQLEXPRESS;database=myDatabase;user id=myUser;password='myPassword';TrustServerCertificate=true;" --connection-string-provider-name "Microsoft.Data.SqlClient"
dotnet sln add "MyProject"

dotnet run --project "MyProject"
#Running

Umbraco 13 Tutorial - Episode 1 - Introduction: https://www.youtube.com/watch?v=xeWh9-56UzY
Umbraco 13 Tutorial - Episode 2 - Install Umbraco: https://www.youtube.com/watch?v=7XOU6hv2trI
	https://codeshare.co.uk/umbraco-13-tutorial/episode-2/
	User: Administrator
	Email: admin@example.com
	Pw: 1234567890

Umbraco 13 Tutorial - Episode 3 - Templates: Umbraco 13 Tutorial - Episode 3 - Templates
Umbraco 13 Tutorial - Episode 4 - Document Types : https://www.youtube.com/watch?v=i6fG5A0SBD0&t=1s
Umbraco 13 Tutorial - Episode 5 Part 1 - Block Grid Navigation: https://www.youtube.com/watch?v=_GXgP5Mr-4w
Umbraco 13 Tutorial - Episode 5 Part 2 - Block Grid Footer: https://www.youtube.com/watch?v=ki0DtyoYBhk
Umbraco 13 Tutorial - Episode 6 Part 1 - Block Grid Content: https://www.youtube.com/watch?v=yEzeKXY5SgE
Umbraco 13 Tutorial - Episode 6 Part 2 - Block Grid Image Links: https://www.youtube.com/watch?v=fifqN-V_dT8
Umbraco 13 Tutorial - Episode 6 Part 3 - Block Grid Icons and Links: https://www.youtube.com/watch?v=SPB1rOikzUY
Umbraco 13 Tutorial - Episode 6 Part 4 - Block Grid Previews: https://www.youtube.com/watch?v=ojXXF9wya6M