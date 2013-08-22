Instagram Live Mapper
=====================

This little demo shows how to implement a live Instagram feed on an ArcGIS Js map.

How does it work ?

- Esri has just release an Instagram Connector for the New GeoEvent Processor Extension to ArcGIS for Server 10.2. With this connecteur and the GEP, one is able to connect to the popular media feed from the Instagram API and publish it as a live service of geo features on a Web Socket endpoint.
- The new version (3.6) of the ArcGIS Javascript API introduces Streamlayers. Streamlayers are map layers that are sourced from a live feed of geo features on a web socket endpoint. The feature just appear on the map as they are feeded to the web socket.

This demo is built on this architecture : Instagram -> ArcGIS Server/GeoEvent Processor -> Js App

At this time the Instagram connector to GeoEvent Processor seems hardcoded to the Instagram popular media feed, so be prepared for fashionistas, nail art, reality show heroes, ...

<a href="http://esrifrance.github.io/Instamap/">Let's play with the demo !</a>

Author : Christophe Tourret / <a href="http://twitter.com/ChrisTourret">@ChrisTourret</a>