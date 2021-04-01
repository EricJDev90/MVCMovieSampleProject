# MVCMovieSampleProject
Written with C# and ASP.NET, this webpage uses the Entity Framework to access a database for movies. It is a small project I built and used as a school assignment

# To Run
Download the files and open the .sln file in Visual Studio. You may need to re-migrate the seed data into your database. Use the NuGet package manager:
Tools --> NuGet Package Manager --> Package Manager Console (PMC).

In the PMC, enter the following commands:

```Add-Migration InitialCreate```
```Update-Database```

This should re-seed the database.
