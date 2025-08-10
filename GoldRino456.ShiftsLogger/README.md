# Shifts Logger

A console application that allows a user to manage and track their working hours. Also included is a locally run API to interface with a SQL Server containing work shift records.

## Features

- Web API for handling CRUD operations with the SQL Server database.
- Easy to use and intuitive UI application for creating, viewing, and making changes to stored records via the API.
- Calculates total shift duration based on input Clock-In and Clock-Out times you provide.

## Tech Stack

**Runtime & Framework:** .NET 8, ASP.NET Core
**Database ORM:** Entity Framework
**Database:** SQL Server
**UI:** Spectre.Console

## Lessons Learned

- Previously I had used RestSharp to simplify API calls rather than utilizing the HttpClient class. With this project, I made a point to use that class over RestSharp to get some hands on experience working with it. I ran into a few issues with some of my async methods as I'm still learning about working with async code, but was able to figure out the timing issues with some trial and error. Going forward I'll be doing some more reading and experimentation with async, but otherwise HttpClient wasn't too difficult to get up and running.
- This is the first time I've built any kind of API. Between the Microsoft documentation, the CSharpAcademy website, and a few other resources I found online, I feel like I was able to understand the basics of building a Web API with ASP.NET. There's definitely a lot more to it that I'll have to build up my knowledge as it's needed, but at least as far as handling basic http requests and setting up the baseline response codes, that was all really straight forward with ASP.NET and painted a clearer picture of what goes on under the hood of a live web app.

## Acknowledgements

 - [The C# Academy](https://www.thecsharpacademy.com/) - I feel like I'm learning more and more daily because of y'all! Thank you for being such a great and supportive community!
 - [README Editor](https://readme.so/editor)
 - [Spectre Console](https://spectreconsole.net) 

