# For the developers

Our app is hosted firebase.google.com. The analysis of the data is done on a local machine after getting the data from the database and then the results
are published to github. Then the frontend can use "github raw content" to make the most recent views.

- frontend: vue.js
- backend: serverless functions on firebase
- [analysis scripts](https://github.com/ch-covid-19/analysis-scripts): python

## Data output

The analysed data are published to a repository by country ([example](https://github.com/ch-covid-19/datasets)).


## Geocoding 

We need a geo locations file for post code for every targeted country.
One [repository](https://github.com/ch-covid-19/geo-locations) is hosting all the geo-location data.
