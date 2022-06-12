
# Database


# Region Collection
```
regions: [
    {
        name: 'America',
        regionID: 'USA',
        sites: [SITES_COLLECTION],
        geoJSON: [{ type: 'Polygon', coordinates: [[[-73.935242, 40.730610], [-73.935242, 40.730610], [-73.935242, 40.730610], [-73.935242, 40.730610]]] }],
        teamID: '',
    }
]
```

# Sites Collection
```
sites: [
    {
        name: 'New York',
        siteID: 'NYC',
        regionID: 'USA',
        cameras: [CAMERAS_COLLECTION],
        geoJSON: [{ type: 'Polygon', coordinates: [[[-73.935242, 40.730610], [-73.935242, 40.730610], [-73.935242, 40.730610], [-73.935242, 40.730610]]] }],
        teamID: ''
    }
]
```


# Cameras Collection
```
cameras: [
    {
        siteID: 'NYC',
        regionID: 'USA',
        name: 'Camera 1',
        url: 'http://',
        img: [STORAGE_CAMERAS]
    }
]
```


# Camera Bucket

```
cameras: [
    {
        siteID: 'NYC',
        regionID: 'USA',
        teamID: '',
        img: 'FILE'
    }
]
```
