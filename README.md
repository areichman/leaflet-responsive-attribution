# leaflet-responsive-attribution
Display a compact version of the Leaflet attribution control on small map sizes

## Usage
Simply include the stylesheet in your page header and include the JS code after you load Leaflet. Any map that includes the stock Leaflet attribution control will be upgraded to the responsive version, displayed in its compact form on map widths less than 600px.

Note: The default stylesheet assumes that FontAwesome is included on the page. If you are not using this icon set, you will need to modify the style appropriate to use your own content or image.

## About
Inspired initially by [Mapbox.js](https://github.com/mapbox/mapbox.js/commit/d895620400bd0c0ffb0144dc28699a1f2685eee1), this plugin uses the CSS checkbox hack instead to show and hide the attribution map sizes, removing the potential for sticky :hover states on touch devices that other plugins use.
