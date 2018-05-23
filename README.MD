AngularJS is used to develop WEB UI application using MVC

## Helloworld html 
```html
<!DOCTYPE html>  
<html lang="en">  
<head>  
    <meta chrset="UTF 8">
    <title>Testing</title>     
</head>  
<body ng-app="app">
<h1 ng-controller="HelloWorldCtrl">{{message}}</h1>
<script src="https://code.angularjs.org/1.6.9/angular.js"></script>
<script>  
    angular.module("app", []).controller("HelloWorldCtrl", function($scope) {  
    $scope.message="Hello World" 
    } )
</script> 

</body>  
</html>
```

## Keywords
__ng_app__  - application is angular application
__ng-controller__ defining the controller
__scope__  JavaScript object which basically binds the "controller" and the "view". One can define member variables in the scope within the controller which can then be accessed by the view
__ng-repeat__  for lists
__ng-model__ represents model
    
[Tutorial](https://www.guru99.com/angularjs-tutorial.html)