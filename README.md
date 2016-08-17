# angular-ui-switch version 1.0.0
AngularJS toggle-switch styled completely in css.

[angular-ui-switch demo](http://dwleke.info/angular-ui-switch.html)


## Usage
The template used by this directive is embeded within as well as it's controller.

## Dependencies
* AngularJS 1.5.8 was used to test this version.
You could try other versions of AngularJS and let me know if anything goes wrong.

### ui-switch
Inject this module into your angular app to use the switch.

### uiswitch
This is the name of the directive and can be used as an element or an attribute to an element.
<uiswitch></uiswitch> or <div uiswitch></div>

### mode
This is the directive's model that your model needs to bind to.
Your model gets updated to "true" or "false" as the switch is turned on or off.

## Example
Make sure you have the angular-ui-switch.js file referenced. You could use the minified version in production.

```html
  <!-- your angular script -->
  <script>
      // inject ui-switch
      angular.module('app', ['ui-switch'])
          .controller('ctrl',['$scope', function($scope){
                $scope.likeCoffee = false;
                $scope.likeSugar = false;
          }])
  </script>
  
  <div ng-app='app' ng-controller='ctrl'>
  
      <!-- ui-switch in action -->
      <label>Like coffee? ({{likeCoffee}})</label> <uiswitch mode="likeCoffee"></uiswitch>
      <label>Like sugar? ({{likeSugar}})</label> <uiswitch mode="likeSugar"></uiswitch>
      
  </div>
```

## License
angular-ui-switch is released under the MIT license.

## What does this mean:
* It requires you to keep the license and copyright information in all files when you use them in your works.
* Freely download and use angular-ui-switch, in whole or in part, for personal, private, company internal, or commercial purposes.
* Use angular-ui-switch in packages or distributions that you create.
* Modify the source code.
* Grant a sublicense to modify and distribute angular-ui-switch to third parties not included in the license.

## What you can't do:
* Hold the authors and license owners liable for damages as angular-ui-switch is provided without warranty.
* Hold the creators or copyright holders of angular-ui-switch liable.
* Redistribute any piece of angular-ui-switch without proper attribution.
* Use any marks owned by dwleke.info in any way that might state or imply that dwleke.info endorses your distribution.
* Use any marks owned by dwleke.info in any way that might state or imply that you created the dwleke.info software in question.

## Cut the story short:
* Use at your own risk, however, it's a simple and beautiful piece.

## Donation
Support this project by giving a great meal to a homeless or hungry child or person.
And I will be thankful you did.
