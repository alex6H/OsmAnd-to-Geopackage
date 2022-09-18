# OsmAnd GPX tracks to Geopackage
The purpose of this script is to aggregate a set of GPX files (traces only, not POI) create with [OsmAnd](https://osmand.net/). It allows to clean up the periods without move, to filter the too high or too low speeds, to determine a minimum displacement distance between two consecutive points and to remove the too abrupt turns (angles in degree).

When aggregating GPXs in a Geopackage, each track is numbered as well as each point of the tracks.
