# SportsStore-ASP.NET-MVC
WebApp made using MVC pattern in ASP.NET


In this app most important are separate of concerns, good coding practices and proper execution of MVC pattern.
UI is humble, yet sufficient for exposing core functionalities to the user.
Solution consists of 3 projects: Domain,UnitTests and WebUI.
Ninject,Moq and EntityFramework are also used in this project

In this app You are able to browse products from categories and add them to cart.
When You add products to Your cart, You're able to view them in Your cart section and checkout. 
After filling out the form data is sent by e-mail or saved to file.

Admin panel in /Admin/Index is available after logging in with login: admin/ password: secret
In admin panel You can edit products and categories. You are also able to upload pictures.

//After loading a project I found that restarting VS removes errors. Change startup project to WebUI//
