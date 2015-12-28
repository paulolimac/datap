# Introduction

The Datapackage examplified is a complete datapackage to show all possibilites os data records and configurations.

## Datapackage description

It was created to show all sort of possibilities when using a dataset tool or to see how to write a datapackage.
Yet was stablished a simple table with latitude and longitude, a map to plot these coordinates, and another table with all official field types supported.
Plus that, a simple view was coded to plot a graph in proper tools.

# Data

This dataset contains [files](https://github.com/paulolimac/datap/tree/master/data "data") to ilustrate the usage of opendata.
There are compose by the follow data files:

- [Simple table](https://github.com/paulolimac/datap/blob/master/data/simpleCoordinates.csv "csv") with latitude and longitude.
- [Simple geographical points](https://github.com/paulolimac/datap/blob/master/data/simpleCoordinates.geojson "GeoJson") derivated from simple table.
- [Field Types](https://github.com/paulolimac/datap/blob/master/data/fieldTypes.csv "csv") with all kinds of data types and formats.

All recorded data were only random data.
So you may use it to organize your own datapackage from scratch.
And to understand how to fill all data types and formats supported officialy.

# Preparation

The official tools validated this datapackage and facilites to view it.
The tools are:

- [Data Package Validator](http://data.okfn.org/tools/validate "Official Validator"): this tool is useful to validade the datapackage configuration.
More specificaly, it validates if `datapackage.json` file is write properly by the official OKFN protocols and standards.
To use, follow these steps:
  1. Open it [Data Package Validator](http://data.okfn.org/tools/validate "Official Validator").
  2. Type the link to your `datapackage` or the `datapackage.json` file; in our case can be `https://github.com/paulolimac/datap` or `https://raw.github.com/paulolimac/datap/master/datapackage.json`.
  3. It will show a [message](http://data.okfn.org/tools/validate?url=https%3A%2F%2Fgithub.com%2Fpaulolimac%2Fdatap "results") that can be:
    - `valid` if it is correct or,
    - `invalid` plus the error message to be corrected.
- [DataPackage Viewer](http://data.okfn.org/tools/view "Official viewer"): this tool permits to view all data in a easy way.
All tables, graphs and maps will stay well formated.
To use, follow these steps:
  1. Open it [Data Package Validator](http://data.okfn.org/tools/view "Official viewer").
  2. Type the link to your `datapackage`; in our case can be `https://github.com/paulolimac/datap`.
  3. It will show the [datapackage](http://data.okfn.org/tools/view?url=https%3A%2F%2Fgithub.com%2Fpaulolimac%2Fdatap "datapackage") well formated.
- [Datapackage Explorer](http://explorer.okfnlabs.org/ "Experimental explorer"): it is a experimental tool to edit or show your `csv files` more easly.
To use, follow these steps:
  1. Open it [Data Explorer Loader](http://explorer.okfnlabs.org/#load "Experimental explorer").
  2. Upload the `csv files` or type the link to your `csv file`; in our case can be `https://raw.githubusercontent.com/paulolimac/datap/master/data/simpleCoordinates.csv`.
  3. After see a preview from your csv file, click on at `save button`.
  4. Finally, you can edit the csv file and see the results by tables, graphs and maps.

# License

## ODC-PDDL-1.0

This Data Package and these datasets are made available under the Public Domain Dedication and License v1.0.
The full text can be found [here](http://www.opendatacommons.org/licenses/pddl/1.0/ "license").

# References

Bellow are listed references used to prepare a complete datapackage.

- [OKFN core datasets](https://github.com/datasets "core datasets")
- [OKFN comunity datasets](http://data.okfn.org/data "comunity datasets")
- [OKFN tools](http://data.okfn.org/tools "tools")
- [OKFN datapackage viewer](http://data.okfn.org/tools/view "viewer")
- [OKFN datapackage json creator](http://data.okfn.org/tools/create "datapackage.json creator")
- [OKFN datapackage json validator](http://data.okfn.org/tools/validate "datapackage.json validator")
- [OKFN explorer](http://explorer.okfnlabs.org/ "experimental editor explorer")
- [Recline project graph viewer](http://okfnlabs.org/recline/docs/views.html "viewer graph and plot tool")
- [OKFN lab projects](http://okfnlabs.org/projects/#featured=true "experimental projects")
- [OKFN data standards](http://data.okfn.org/standards "standards")
- [OKFN datapackage doc](http://data.okfn.org/doc/data-package "data package doc")
- [OKFN tabular datapackage doc](http://data.okfn.org/doc/tabular-data-package "tabular data package doc")
- [OKFN CSV doc](http://data.okfn.org/doc/csv "csv doc")
- [How to publish](http://data.okfn.org/doc/publish-online "how to publish online")
- [How to publish geodata](http://data.okfn.org/doc/publish-geo "how to publish geographical data")
- [How to publish general data](http://data.okfn.org/doc/publish-any "how to publish any kind of data")
- [FAQ about how to publish](http://data.okfn.org/doc/publish-faq "faq about how to publish")
- [Protocol of datapackage](http://dataprotocols.org/data-packages/ "datapackage protocol")
- [Protocol of Tabular datapackage](http://dataprotocols.org/tabular-data-package/ "tabular datapackage protocol")
- [Protocol of json table schema](http://dataprotocols.org/json-table-schema/ "json schema protocol")
- [Protocol of CSV dialect](http://dataprotocols.org/csv-dialect/ "csv dialect protocol")
- [Protocol of datapackage identifier](http://dataprotocols.org/data-package-identifier/ "datapackage identifier protocol")
- [JSON official website](http://www.json.org/ "json website")
- [GEOJSON official website](http://geojson.org/ "geojson website")
- [GEOJSON specification](http://geojson.org/geojson-spec.html "geojson specification")
- [Open Definition license](http://licenses.opendefinition.org/ "opendefinition license")
