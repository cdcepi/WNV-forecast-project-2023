### Locations

This folder contains a comma-separated file `locations.csv` that contains location-specific data for all US counties included in the forecasting challenge. US Census 2020 population estimates were retrieved from [census.gov](https://www2.census.gov/programs-surveys/popest/datasets/2020-2022/state/totals/).

Columns:

- `fips` is the two digit state FIPS code. Please note that when writing FIPS codes, they are written as a character string to preserve any leading zeroes.
- `location` is the state name as a character string and is the variable that should be included in forecast submissions. For example, “Colorado” or “Wisconsin”. Forecast submissions will be checked to ensure that location names match those found in this csv file.
- `population` is the county population size from the 2020 US Census.
