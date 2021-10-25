# leaflet-bootstrap-marker-mixin

> SCSS mixins for [FCOO/leaflet-bootstrap-marker](https://github.com/FCOO/leaflet-bootstrap-marker)

## Description

SCSS functions to create classes for different colors for marker created using [FCOO/leaflet-bootstrap-marker](https://github.com/FCOO/leaflet-bootstrap-marker)


## Installation
### bower
`bower install https://github.com/FCOO/leaflet-bootstrap-marker-mixin.git --save-dev`

## Usage

In any scss-file in the `\src` directory include

	@import "../bower_components/leaflet-bootstrap-marker-mixin/dist/leaflet-bootstrap-marker-mixin";


### mixin


    //lbm-marker-and-icon-classes
    //Create class for bsMarkerCircle named $name with color and color-border
    @include lbm-marker-and-icon-classes( $name, $color, $border-color: $color )


    //fa-lbm-color
    //Create class for color and border-color used by L.bsMarkerAsIcon (and $.bsMarkerAsIcon)
    //to create fa-icon looking like the marker
    @include fa-lbm-color( $name, $color: $white, $border-color: $black )


## Copyright and License
This plugin is licensed under the [MIT license](https://github.com/FCOO/leaflet-bootstrap-marker-mixin/LICENSE).

Copyright (c) 2015 [FCOO](https://github.com/FCOO)

## Contact information

[Niels Holt](http://github.com/NielsHolt)


