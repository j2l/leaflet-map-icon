# leaflet-map-icon
A saltcorn view plugin that: 
- adds an openstreetmap map and markers from a table having icon (File type field), latitude and longtitude fields (both of type Float)
- can popup a show view at eack marker
- can limit the number of markers (row) shown on the map

Actually, icon must be 56x60 pixels and pinpoint is located at 40,59 pixels, popup at 0,0 (relative to pinpoint).

You'll need to study this code and leaflet icon (https://leafletjs.com/reference-1.7.1.html#icon) if you want to change the size, add shadow, etc.
