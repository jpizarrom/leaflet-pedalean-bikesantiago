# leaflet-pedalean-bikesantiago

An element providing a starting point for your own reusable Polymer elements.

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

leaflet-pedalean-bikesantiago is under development

Lists of demos: 
* http://app.pedalean.com/

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Playing With Your Element

If you wish to work on your element in isolation, we recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview your element at
`http://localhost:8080/components/leaflet-pedalean-bikesantiago/`, where `leaflet-pedalean-bikesantiago` is the name of the directory containing it.


## Testing Your Element

Simply navigate to the `/test` directory of your element to run its tests. If
you are using Polyserve: `http://localhost:8080/components/leaflet-pedalean-bikesantiago/test/`

### web-component-tester

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester).
Install it via:

    npm install -g web-component-tester

Then, you can run your tests on _all_ of your local browsers via:

    wct

#### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).

`wct test/some-file.html` will test only the files you specify.
