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

leaflet-pedalean-bikesantiago is under development

Lists of demos: 
* http://app.pedalean.com/

## Dependencies

## License

Copyright (c) 2015
Juan Pizarro

All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are
permitted provided that the following conditions are met:

   1. Redistributions of source code must retain the above copyright notice, this list of
      conditions and the following disclaimer.

   2. Redistributions in binary form must reproduce the above copyright notice, this list
      of conditions and the following disclaimer in the documentation and/or other materials
      provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY
EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE
COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR
TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
