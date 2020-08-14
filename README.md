geojson-path-finder-junctions
-----------------------------

Wraps Per Liedman's [GeoJSON Path Finder](https://github.com/perliedman/geojson-path-finder) to insert a list of POIs into a GeoJSON network, and find and group routes from junctions within the GeoJSON network to these POIs.

This can be useful for applications such as generating virtual signposts to show direction and distance to nearby POIs, as in [Hikar](https://hikar.org) or to calculate the routes between adjacent panoramas, as in [OpenTrailView](https://opentrailview.org).

**Please note this contains a bundled, modified version of GeoJSON Path Finder.** This contains a [bug fix](https://github.com/perliedman/geojson-path-finder/pull/64) which is necessary for the routing to work correctly; when this PR has been integrated into the main GeoJSON Path Finder repository, this bundled version will be renoved and replaced by a `geojson-path-finder` dependency.
