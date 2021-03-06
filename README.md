Instagram Live Mapper
=====================

This little demo shows how to implement a live Instagram feed on an ArcGIS Js map.

How does it work ?

- Esri has just released an Instagram Connector for the new GeoEvent Processor Extension to ArcGIS for Server 10.2. With this connector and the GEP, one is able to connect to the popular media feed from the Instagram API and publish it as a live service of geo features on a Web Socket endpoint.
- The new version (3.6) of the ArcGIS Javascript API introduces Streamlayers. Streamlayers are map layers that are sourced from a live feed of geo features on a web socket endpoint. The features just appear on the map as they are feeded to the web socket.

This demo is built on this architecture : Instagram -> ArcGIS Server/GeoEvent Processor -> Js App

At this time the Instagram connector to GeoEvent Processor seems hardcoded to the Instagram popular media feed, so be prepared for fashionistas, nail art, reality show heroes, ...

Some GeoEvent Processor / Instagram resources :
- <a href="https://github.com/Esri/instagram-for-geoevent" target='_blank'>The Instagram connector on Esri's Github</a>
- <a href="http://www.arcgis.com/home/item.html?id=4e33fdcd50f8493286973d412c6c73ba" target='_blank'>The tutorial to the Instagram connector on ArcGIS Online</a>

<a href="http://esrifrance.github.io/InstaMap/" target='_blank'>Let's play with the demo !</a>

Author : Christophe Tourret / <a href="http://twitter.com/ChrisTourret">@ChrisTourret</a>