# React Leaflet Web Map Demo

A ~~bare bones vanilla~~ [Leaflet.JS](http://leafletjs.com/examples/quick-start.html) map created using <a href="https://facebook.github.io/react/">React</a>, [Gulp](http://gulpjs.com/), [qwest](https://github.com/pyrsmk/qwest.git), and [Browserify](http://browserify.org/). No jQuery.

View it live at [leaflet-react.clhenrick.io](http://leaflet-react.clhenrick.io/)

This demo instantiates a Leaflet Map with a Tile Layer, then loads a GeoJSON layer. It implements React components to filter the data and update the map.

To view the bare bones example that doesn't do anything GeoJSON related, take a look at the `bare-bones` branch.

Read the comments in `gulpfile.js` and `src/js/` to see what is going on.

## Install:
Make sure you have Node.JS installed and Gulp installed globally. 

Then do: `npm install`

## To Run
Do `gulp` in the root of this repo and run a local server in the `dist/` directory. Gulp will update `dist/` with necessary files as you make changes, though currently you must manually refresh the page to see the changes implemented. 

Alternatively do `gulp production` to generate minified production code.