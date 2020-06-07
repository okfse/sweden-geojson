# Sweden GeoJSON

This repository contains tiny GeoJSON files representing
- the Swedish municipalities
- the Swedish regions

I decided to publish them on Github because the only versions of the first one I could find returned an error message when importing in Metabase or were all incredibly detailed and around 25MB in size. Even the regional ones were featuring many small islands which I didn't need for what I wanted to do.

So I compressed two working files using [mapshaper](https://mapshaper.org) (the former to 2%, the latter to 10%) to get tiny files which will suit most visualisation needs while being much easier to load and process in a browser.

The original files I used are:
- [Swedish municipalities](https://public.opendatasoft.com/explore/dataset/sverige-kommuner-municipalities-of-sweden/information/?flg=fr) (originally converted from Valmyndigheten's data)
- [Swedish provinces](https://github.com/jnordgren/swedish_data_map_geojson)

There are a few other GeoJSON of Swedish areas on Github (for example these ultralight ones [here](https://github.com/deldersveld/topojson/tree/master/countries/sweden)) but unfortunately they got me an error message when importing in Metabase.

Feel free to reuse. You can even load them remotely from Github by selecting the file and clicking on **Raw**.
