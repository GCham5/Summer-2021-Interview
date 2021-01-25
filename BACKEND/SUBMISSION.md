## Repository: 

https://github.com/GCham5/OutStem-Back-End-Challenge-2021

## Run Instructions

Clone the repo
`git clone https://github.com/GCham5/OutStem-Back-End-Challenge-2021.git`

### Windows
It is preferable to open and run using Visual Studio. However, if using cmd line, simply navigate to the folder and run `dotnet tool install --global dotnet-ef` to install EF Core (if not already installed). Next, run `dotnet add package Microsoft.EntityFrameworkCore.Design` (again, if not already installed). Next run `dotnet ef database update` to create the database on your local machine. Finally, run `dotnet run`. It should start listening at 5001. 

### Mac
If on macOS, a few steps need to be completed. You need to install SQL Server on macOS using a Docker container. Steps can be followed here [ASP.NET Core Development with macOS](https://gist.github.com/jeremymaya/a36c1de8220d76beca85a2804a2cecc4)

### Testing
It is preferable to test the API using Postman. I have included a sample Postman collection. [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/8be5d3f16e1ed46b7bde)

## Additional Information
Name: Georges Chamoun

As this was built using a local SQL db, there is no sample data present in my submission. However, running the requests in the Postman collection should provide some sample data.
