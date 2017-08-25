# divvy-analysis
This project contains an exploratory and predictive analysis of Chicago's ride share system (Divvy Bike) data from 2016. The analysis demonstrates how local data, like the cubs schedule, and weather data can be used to help Divvy Bike predict spikes in demand. 

## Getting Started

The complete R Markdown script and the knit HTML document can be found in the modelling directory. Note that compiling the entirely of the rmd script from scratch may take a long time because of the computational complexity of the random forests.

### Prerequisites

To run the rmd script on your system, a number of packages must be installed. To install them, the following command can be entered into an R script.

```
install.packages(c("boot", "glmnet", "MASS", "pscl", "randomForest"))
```

## Authors

* **Eric Weine** - ericweine@uchicago.edu

## Acknowledgments

Many of the visualizations were made with Tableau. The Map required use of the Google Maps API to lookup the zipcodes of bike stations based upon their geographic coordinates.
