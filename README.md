cloudstack_dotnetsdk
====================

.NET client side SDK for CloudStack API
Build with Visual Studio 2012

NuGet packaging
===============

NuGet package is CloudStack.SDK

We push Release and Debug NuGet packages by using -sym option

E.g. 
nuget pack -sym CloudStack.SDK.csproj
nuget push CloudStack.SDK.2.2.0.4.nupkg

For more details on how to use the Debuggable package, see http://blog.davidebbo.com/2011/04/easy-way-to-publish-nuget-packages-with.html
