#Getting Started with ASP.NET Web API
[Sample code for Code Magazine Article](http://www.west-wind.com/weblog/posts/2012/Aug/21/An-Introduction-to-ASPNET-Web-API)

This project is the source code for the above article and provides a small example application that demonstrates some of the core features of the ASP.NET Web API. It contains the code samples referenced in the article above.

Most of the examples are contained in the GetAlbums.htm/js pages with the AlbumApiController.cs and AlbumRpcApiController.cs providing the backend Web API controllers. Additional examples are shown
in the SamplesApiController.

### Solution Configuration###
This project currently works with the ASP.NET MVC RC using .NET 4.0 runtime. 

Even though this project contains the RC files, all of the dependencies 
are loaded via NuGet, so these examples should all work as is even if you
don't have a previous MVC4 installation.

I will update these examples again once MVC 4 hits RTM.
