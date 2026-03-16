# SLV Allmaps

This repository contains documentation and data relating to the georeferencing of digitised maps in the State Library of Victoria's collection using Allmaps. It was created by [Tim Sherratt](https://timsherratt.au) during his time as [Creative Technologist-in-Residence](https://lab.slv.vic.gov.au/team/tim-sherratt) at the [SLV LAB](https://lab.slv.vic.gov.au/).

The repository includes a GitHub action that downloads data about newly georeferenced SLV maps from Allmaps every 2 hours. This data is used to update the georeferencing project dashboard.

## Documentation

- [Georeferencing maps from the State Library of Victoria](https://wragge.github.io/slv-allmaps/)
- [Project Dashboard – Georeferenced maps in the State Library of Victoria's collections](https://wragge.github.io/slv-allmaps/dashboard.html) (updated every two hours)

## Data

All the georeferencing data created through Allmaps is available as open data under a [CC0 licence](https://creativecommons.org/public-domain/cc0/).

- [georeferenced_maps.csv](https://github.com/wragge/slv-allmaps/blob/main/georeferenced_maps.csv) – aggregated data in CSV format
- [georeferenced_maps.geojson](https://github.com/wragge/slv-allmaps/blob/main/georeferenced_maps.geojson) – aggregated data in GeoJSON format
- [geojson](https://github.com/wragge/slv-allmaps/tree/main/geojson) directory – individual georeferencing data in GeoJSON format
- [maps](https://github.com/wragge/slv-allmaps/tree/main/maps) directory – individual georeferencing data as IIIF annotations in JSON

## Exploring the results

You can explore the georeferenced maps using these tools and apps:

- [Search the aggregated dataset in Datasette](https://glam-workbench.net/datasette-lite/?csv=https%3A%2F%2Fgithub.com%2Fwragge%2Fslv-allmaps%2Fblob%2Fmain%2Fgeoreferenced_maps_datasette.csv&install=datasette-homepage-table&install=datasette-json-html&fts=manifest_title%2Cmap_title)
- [Georeferenced maps explorer](https://slv.wraggelabs.com/geomaps/)
- [my place](https://slv.wraggelabs.com/myplace/)

