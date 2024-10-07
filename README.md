# Understanding ArcGIS Platform: Location Services, APIs, and Tools for Developers

Welcome to the repository for my presentation at the Developer Summit during the Esri FedGIS 2024 conference. This repo contains the demos and slides from my talk, where I explored various location services, APIs, and tools within the ArcGIS Platform.

## Requirements

- **ArcGIS Location Platform Account**: You can sign up for an account [here](https://location.arcgis.com/).
- **ArcGIS Access Token**: Instructions for generating an access token can be found [here]([https://developers.arcgis.com/rest/security/overview.htm](https://developers.arcgis.com/documentation/security-and-authentication/)).
- **Cesium Access Token**: You can obtain a Cesium access token by signing up [here](https://cesium.com/platform/cesiumjs/).

## Demos

### [Basemaps Demo](https://github.com/cyatteau/FedGIS2024-PlatformOS-Talk/blob/main/basemaps-demo.html)
- **Description**: A MapLibre map centered on Washington, D.C., showcasing the ability to switch between over 25 different basemap styles, including OpenStreetMap and ArcGIS options. The demo highlights how to add points of interest, localize map labels, and explore different worldviews using the ArcGIS Basemap Styles Service.
- **Technologies Used**: MapLibre GL JS, ArcGIS Basemap Styles Service

### [Geocoding Demo](https://github.com/cyatteau/FedGIS2024-PlatformOS-Talk/blob/main/geocoding-demo.html)
- **Description**: A Leaflet map utilizing Esri Leaflet to access ArcGIS location services. This demo demonstrates geocoding and reverse geocoding capabilities, as well as searching for feature layer data (community gardens in D.C.) through the geosearch tool.
- **Technologies Used**: Leaflet, Esri Leaflet

### [Routing Demo](https://github.com/cyatteau/FedGIS2024-PlatformOS-Talk/blob/main/routing-demo.html)
- **Description**: An OpenLayers map centered on Fairfax County, VA, enhanced with the ArcGIS Routing Service using ArcGIS REST JS. The demo showcases basic routing, closest facility routing to hospitals, and service areas based on drive times.
- **Technologies Used**: OpenLayers, ArcGIS REST JS

### [GeoEnrichment Demo](https://github.com/cyatteau/FedGIS2024-PlatformOS-Talk/blob/main/geoenrichment-demo.html)
- **Description**: A CesiumJS app centered on D.C. connected to the ArcGIS GeoEnrichment service via ArcGIS REST JS. Users can choose between global or local demographic data, displaying various statistics based on a 1-mile search radius.
- **Technologies Used**: CesiumJS, ArcGIS GeoEnrichment Service, ArcGIS REST JS

## Slides

The slides from the presentation can be found in the [slides directory](https://github.com/cyatteau/FedGIS2024-PlatformOS-Talk/blob/main/FedGIS2024Platform-Talk.pdf). You can view or download them for your reference.

## Contact

For questions or feedback, please reach out at [cyatteau@esri.com](mailto:cyatteau@esri.com) or connect with me on [LinkedIn](https://www.linkedin.com/in/courtneyyatteau/).
