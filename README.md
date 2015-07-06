# angular-backtotop

## Usage

```
bower install -g angular-backtotop
```

>
```html
<!doctype html>
<html ng-app="myApp">
<head>
    <script src="//ajax.googleapis.com/ajax/libs/angularjs/1.2.28/angular.min.js"></script>
    <script src="bower_components/angular-backtotop.min.js"></script>
    <script>
        var myApp = angular.module('myApp', ['angular-backtoptop']);
        // For Component users, it should look like this:
        // var myApp = angular.module('myApp', [require('angular-ui-router')]);
    </script>
    ...
</head>
<body>
    <div style="margin-top: 1000px"/>
    <a href back-to-top>Back to top</a>
</body>
</html>
```

## License

MIT
