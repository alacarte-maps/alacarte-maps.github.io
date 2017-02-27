# Documentation on updating the leaflet js files etc.

cd themes/alacarte-bootblog-journal/assets/
mkdir -p css
mkdir -p images
mkdir -p js

curl -o css/leaflet.css https://unpkg.com/leaflet@1.0.0/dist/leaflet.css
#replace images/layers.png with /assets/images/layers.png
#replace images/layers-2x.png with /assets/images/layers-2x.png
curl -o images/layers.png https://unpkg.com/leaflet@1.0.0/dist/images/layers.png
curl -o images/layers-2x.png https://unpkg.com/leaflet@1.0.0/dist/images/layers-2x.png
curl -o js/leaflet.js https://unpkg.com/leaflet@1.0.0/dist/leaflet.js

curl -o js/leaflet.fullscreen.min.js https://api.mapbox.com/mapbox.js/plugins/leaflet-fullscreen/v1.0.1/Leaflet.fullscreen.min.js
curl -o css/leaflet.fullscreen.css https://api.mapbox.com/mapbox.js/plugins/leaflet-fullscreen/v1.0.1/leaflet.fullscreen.css
#replace fullscreen.png with /assets/images/fullscreen.png
#replace fullscreen@2x.png with /assets/images/fullscreen@2x.png
curl -o images/fullscreen.png https://api.mapbox.com/mapbox.js/plugins/leaflet-fullscreen/v1.0.1/fullscreen.png
curl -o images/fullscreen@2x.png https://api.mapbox.com/mapbox.js/plugins/leaflet-fullscreen/v1.0.1/fullscreen@2x.png
