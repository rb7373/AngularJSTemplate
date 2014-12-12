AngularJSTemplate
=================

Basic structure of a project in angular

app/
----- shared/   // acts as reusable components or partials of our site
---------- module/
--------------- moduleDirective.js
--------------- moduleView.html

----- components/   // each component is treated as a mini Angular app
---------- home/
--------------- homeController.js
--------------- homeService.js
--------------- homeView.html

----- app.module.js
----- app.routes.js

assets/
----- img/      // Images and icons for your app
----- css/      // All styles and style related files (SCSS or LESS files)
----- js/       // JavaScript files written for your app that are not for angular
----- libs/     // Third-party libraries such as jQuery, Moment, Underscore, etc.

index.html
