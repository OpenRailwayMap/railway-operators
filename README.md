railway-operators
=================

 This repository contains a machine-readable list of railway operators including trains, trams, metros, subways and light rails.

 It is not intended to collect any detailled information about the lines. Such information can be found in OpenStreetMap.

 The initial goal was to maintain an up to date list of railway companies around the world for quality assurance of OpenStreetMap data, such as detecting misspelled operators.

## Datasets

This repository contains two datasets in CSV format. For easier maintanance, the lists are sorted by `country` and `operator_short_name`.

### infrastructure-operators.csv

Companies operating railway lines (also known as [Eisenbahninfrastrukturunternehmen (EIU)](https://de.wikipedia.org/wiki/Eisenbahninfrastrukturunternehmen) in German speaking countries).

Columns:

 * `operator_official_name`: The official name of the company including the corporation form.
 * `operator_short_name`: The short name of this company.
 * `country`: The [ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) two letter country code in upper case. Indicates the country in which the infrastructure operated by this company is located. If a company operates infrastructure in more than one country, there are duplicate entries in the table, one per country.

### traffic-operators.csv

Companies operating railway traffic (also known as [Eisenbahnverkehrsunternehmen (EVU)](https://de.wikipedia.org/wiki/Eisenbahnverkehrsunternehmen) in German speaking countries).

_(will be added in future)_

## Maintainer

 * Alexander Matheisen [@rurseekatze](https://github.com/rurseekatze) <alex@matheisen.org>

## Contribute

 Your support to keep this list up to data is welcome. You can contribute by either adding an Issue or a Pull Request.

## License

 This data is licensed under CC0 1.0 Universal.
