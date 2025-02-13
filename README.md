# Date Picker Week View

## Overview
**Date Picker Week View** is a bundle of [AngularJS](http://angularjs.org) directives that allows you date pickers with
week view.

## Demo
**https://nicomendoza274.github.io/datepicker-week-view/**

## Installation
### Bower
````
bower install nicomendoza274/datepicker-week-view#0.0.6
````

### Insert dependency in angular module
````
var app = angular.module("myApp", ["dtp-week-view"]);
````

### Includes files in index.html (if necessary)

**Include js file (after angular.js script tag):**
````
<script type="text/javascript" src="../bower_components/datepicker-week-view/src/js/datepicker-week-view.js"></script>
````

**Include css file:**
````
<link rel="stylesheet" type="text/css" href="../bower_components/datepicker-week-view/src/css/style.css">
````


## Usage

````
<dtp-week-view num-weeks="1" ng-model="appC.selectedDay"></dtp-week-view>
````


## Options
| Option  | Default Value | Description|
| ------------- | ------------- | ------------------------ |
| num-weeks  | 1  | Number of weeks to be displayed  |
| start-date  | now  | Date that will get selected   |
| min-date  | 2000-01-01  | Lowest possible date to be selected (previous dates will be disabled)   |
| max-date  | 3000-01-01  | Highest possible date to be selected (next dates will be disabled)  |
| invalid-dates  | []  | Array of values that are disabled. It use moment format "YYYY-MM-DD"       |

## Dependencies
**TODO**


## License
[MIT](LICENSE)
