Leaflet.legend.interactive
==========================

A layer and legend control for the Leaflet web mapping API

The goals of this project are to fill some gaps in the default legend and layer controls in Leaflet to make them more functional for web apps that go beyond a single layer visualization.

Must haves:

* Layer control with legend built in so you can tell which layer you're controlling at a glance
* User controlled layer ordering that sticks
* Change layer display properties on the fly - color, line thickness, transparency, etc.
* Disabling of layer modification capabilities by developer
* Naming/Renaming of layers
* Removing layers
* Show/hide layers

Nice to haves:

* Export / View dynamically generated legend based on which layers are visible and their current display properties.
* Compatible with Leaflet v0.8 to come soon - being mindful that v0.8 most likely breaks current plugins.
* A searchable list of base layers
* Add layers on the fly usign standard formats (GeoJSON)
* Custom color 'blank' base layer


Inspiration and proof of concept projects:

* https://github.com/yohanboniface/Leaflet.TileLegend
* http://elesdoar.github.io/leaflet-control-orderlayers/
