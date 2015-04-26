## Overview 

This is a meteor package of the [AmCharts](http://www.amcharts.com/) free version for meteor projects.

-[Demo site](http://em0ney-amcharts-example.meteor.com)
-[Example code from demo site](https://github.com/thesaucecode/meteor-amcharts-example)

## Installation

Install by typing `meteor add em0ney:amcharts`

This version replaces 'mrt:amcharts'

## Usage

Take example charts from [AmCharts Demos](http://www.amcharts.com/demos/).  Simply place all javascript initialisation code inside of a `Template.rendered = function() {}` callback.  E.g. https://github.com/thesaucecode/meteor-amcharts-example/blob/master/client/example2.js

Within your chart initialization, if referencing any images (e.g. 'export.png'), please prepend the path with the package path.  E.g.

    "exportConfig":{
      "menuTop":"20px",
          "menuRight":"20px",
          "menuItems": [{
          "icon": '/packages/amcharts/lib/images/export.png',
          "format": 'png'   
          }]  
      }

