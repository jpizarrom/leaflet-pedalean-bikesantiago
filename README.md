# leaflet-pedalean-bikesantiago

## Quickstart Guide

Install this web component using [Bower](http://bower.io):

```
bower install jpizarrom/leaflet-pedalean-bikesantiago
```

Import the main component and start creating your map:

```html
  <head>
	<script type="text/javascript" src="../webcomponentsjs/webcomponents-lite.min.js"></script>
    <link rel="import" href="leaflet-map.html">
    <link rel="import" href="leaflet-pedalean-bikesantiago.html">
    <style>
      html, body {
        margin: 0;
        height: 100%;
      }
      leaflet-map {
        height: 100%;
      }
    </style>
  </head>
  <body unresolved>
    <leaflet-map latitude="-33.4377968" longitude="-70.6504451" zoom="13">
      <leaflet-pedalean-bikesantiago url="http://..." apikey=""></leaflet-pedalean-bikesantiago>
    </leaflet-map>
  </body>
```
## Status

Lists of demos: 
* http://app.pedalean.com/

## Dependencies
