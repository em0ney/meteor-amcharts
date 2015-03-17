## Overview 

This is a meteorite package of the [AmCharts](http://www.amcharts.com/) free version for meteor projects.

## Installation

Install by typing `meteor add em0ney:amcharts`

## Usage

Within your chart initialization, if referencing any images (e.g. 'export.png'), please prepend the path with the package path.  E.g.

    "exportConfig":{
      "menuTop":"20px",
          "menuRight":"20px",
          "menuItems": [{
          "icon": '/packages/amcharts/lib/images/export.png',
          "format": 'png'   
          }]  
      }
