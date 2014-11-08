canada-geo-spatial-data
=======================

Canada's Province Geo-Spatial Data in JSON. Handy for mapping like GoogleMaps or Leaflet.

#### An Example ####
```
  "saskatchewen":{  
    "short":"SK",
    "name":"Saskatchewen",
    "center":{  
      "lat":51.75,
      "lng":-105.39,
      "zoom":6
    },
    "northEast":{  
      "lat":54.32,
      "lng":-95.64
    },
    "southWest":{  
      "lat":48.99,
      "lng":-116.23
    }
  }
```

The center property is an opinionated zoom on the most populated part of the province. The ***southWest*** and ***northEast*** are mapping bounds for that specific province, and can be used for the "Bounds" values in something like Leafet.
