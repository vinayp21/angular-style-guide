+++
date = "2016-10-12T02:18:19-04:00"
draft = false
title = "Routing"

+++
AngularJS routes enable you to create different URLs for different content in your application. Having different URLs for different content enables the user to bookmark URLs to specific content, and share those URLs. In AngularJS each such bookmarkable URL is called a route.

AngularJS routes enables you to show different content depending on what route is chosen. A route is specified in the URL after the # sign. Thus, the following URL's all point to the same AngularJS application, but each point to different routes.

The routing in the angular application can be achieved by using:

   * ngRoute is a module developed by the Angular.js team which was earlier part of the Angular core.
   * ui-router is a framework which was made outside the Angular.js project to improve and enhance routing capabilities.

<b>ngRoute</b>

The ngRoute module routes your application to different pages without reloading the entire application.

Your application needs a container to put the content provided by the routing.This container is the ng-view directive. Applications can only have one ng-view directive, and this will be the placeholder for all views provided by the route.

<b>Example and Reference</b>

[Angular Routing](http://www.w3schools.com/angular/angular_routing.asp)

<b>ui-router</b>

ui-router allows for nested views and multiple named views. This is very useful with larger app where you may have pages that inherit from other sections. ui-router allows for you to have strong-type linking between states based on state names. Change the url in one place will update every link to that state when you build your links with ui-sref. Very useful for larger projects where URLs might change. states allow you to map and access different information about different states and you can easily pass information between states via $stateParams. You can easily determine if you are in a state or parent of a state to adjust UI element (highlighting the navigation of the current state) within your templates via $state provided by ui-router which you can expose via setting it in $rootScope on run.

<b>Example and Reference</b>

[Angular ui-router](http://angular-ui.github.io/ui-router/sample/#/)
