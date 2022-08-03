UG LFB Map
====
[Live page](https://ninjalabs-dev.github.io/ug-lfb-map/)
This interactive (Google) map shows you the locations around the city for use with LFB.

## How to submit new locations
1. Right click on the map to add points.
2. Copy latest item in `locations.json`
3. If it's a single point like a hyrant, set `point` to `true` e.g. `point:true`
3. Replace `latlngarray` locations with location(s).
4. Replace the id with an unused id while trying to maintain the pattern in `locations.json`
5. Change the type, add a video or images, and change the color of the region/point.
6. Send the data to Ninja#4321 on Discord.

Alternatively a new issue can be created the region/point data and it will be added.

## How to host yourself

1. Clone this repository
2. Host the repository using Nginx, Apache, or another webserver.

To host the repository using Python 3 use in the root of the repository:
```
python -m http.server
```

## License

[WTFPL](LICENSE)

## Version

1.1.1

## Credits

To [danharper](https://github.com/danharper/) for [his work](https://github.com/danharper/GTAV) on the GTA V map.
To [gta5-map](https://github.com/gta5-map) for [their work](https://github.com/gta5-map/gta5-map.github.io) on the GTA V map.
To [skyrossm](https://github.com/skyrossm) for [their work](https://github.com/skyrossm/np-gangmap) on the Map System.
