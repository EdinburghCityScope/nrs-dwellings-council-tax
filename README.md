# nrs-dwellings-council-tax
Number of dwellings in Edinburgh by Council Tax band.

Statistics provided by National Records of Scotland. http://statistics.gov.scot/data/dwellings-council-tax

## License

Data is licensed under the Open Government License: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/2/

## Requirements

- NodeJS
- npm

## Installation

Clone the repository

```
git clone https://github.com/EdinburghCityScope/nrs-dwellings-council-tax.git
```

Install npm dependencies

```
cd nrs-dwellings-council-tax
npm install
```

Run the API (from the nrs-dwellings-council-tax directory)

```
node .
```

Converting the extracted data into loopback data.

```
node scripts/featureCollectionToLoopbackJson.js
```

Re-build data files from the statistics.gov.scot API

```
node scripts/build-data.js
```
