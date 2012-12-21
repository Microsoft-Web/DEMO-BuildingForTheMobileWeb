DEMO - Building for the Mobile Web
==========================
###Prerequisites
You'll need a mobile emulator - Windows Phone 8 works but is a difficult to use against localhost. The Opera Mobile emulator (linked to from [http://asp.net/mobile](http://asp.net/mobile) works pretty well.


##Adaptive Rendering
1. Create a new MVC 4 Internet application **or** a new Web Forms 4.5 application
1. Run the application and resize the browser below 850px width to demonstrate changes to header, bulleted items
1. Show the site CSS and search for @media to show the media query
1. Browse to [http://asp.net](http://asp.net) and show that the UI responds to narrow screen width
1. Browse to [http://mediaqueri.es](http://mediaqueri.es) to explain show how some designers are using media queries

##Display Modes
1. Run completed project
1. Resize browser to show that the new display mode does not respond to screen width - it's based on user agent
1. Browse to the site in the Opera Mobile emulator and show that /Views/Home/Index.Mobile.cshtml is displayed
1. Time permitting, use the Windows 8 Emulator and browse to [http://displaymodewinphone.azurewebsites.net/](http://displaymodewinphone.azurewebsites.net/). Explain that this is the exact same code as the demo, deployed to Azure Web Sites. Show that the WinPhone device mode view is displayed. *If time doesn't allow for this demo, there's a slide that shows a screenshot.*

##Mobile Template
1. File / New Project / MVC 4 / Mobile
1. Run the project and show that it doesn't work all that well on a desktop browser - that's not what it's designed for.
1. Show the site in a mobile emulator.
1. Edit /Views/Shared/_Layout.cshtml and change the data-theme value in <div data-role="page" data-theme="a"> to a different letter (a-e) to show the themes that are built into the jQuery Mobile template.    
1. In a desktop browser, browse to [http://www.asp.net/mvc/tutorials/mvc-4/aspnet-mvc-4-mobile-features](http://www.asp.net/mvc/tutorials/mvc-4/aspnet-mvc-4-mobile-features) and scroll down to the section that shows the list features.