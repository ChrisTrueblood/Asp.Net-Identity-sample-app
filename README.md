Asp.Net-Identity-sample-app
===============================

<strong>Asp.Net Identity sample app</strong> <br>

WebApplication solution <br>
WebCustomUser project demonstrates use of UserManage.UserConfirmationTokens to generate user account activation tokens.
Note that this project require the use of aspnetwebstack nightly builds.
See this for how to configure VS2013 to get the nightly builds:
http://blogs.msdn.com/b/webdev/archive/2013/10/09/asp-net-identity-nuget-packages-for-the-nightly-builds-are-available-on-myget.aspx

MongoUser project <br>
MongoDb based UserStore. A ASP.NET Identity implementation with no dependencies on Microsoft.AspNet.Identity.EntitFramework.
Only Identity.Core needed.

CustomUser solution <br>
Shows how to use ASP.NET Identity using a regular DbContext (no need for IdentityDbContext)
