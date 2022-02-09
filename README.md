# Retail-Centre-Indicators
### Patrick Ballantyne, Les Dolega, Alex Singleton

Related repository: https://github.com/patrickballantyne/CDRC-Retail-Indicators 

----

Welcome to the CDRC Retail Centre Indicators repository. Here we provide detailed supporting information about the creation of some additional indicators for the 2021 release of the CDRC Retail Centres data product.

## Indicators

Indicators are developed for the 2021 release of the CDRC 'Retail Centre Boundaries' data product.

You can explore our indicators on the new CDRC 'Mapmaker' platform; check it out [HERE](https://mapmaker.cdrc.ac.uk/#/retail-centres?m=pctclon&lon=-2.9737&lat=53.4065&zoom=13.42).

----

## Download the Indicators

You can download the indicators in two difference formats; Open-Access and SafeGuarded. For the latter, a formal application to the CDRC will be required, outlining how you intend to use the indicators.

### Open-Access - available [HERE](https://data.cdrc.ac.uk/dataset/retail-centre-boundaries). 

For a subset of the retail centres we provide:
- Clone town measure - presence of 'clone' retailers and retail categories.
- Updated E-resilience score - an updated version of the score developed in [Singleton et al. (2016)](https://www.sciencedirect.com/science/article/pii/S0016718515301500).
- Deprivation indices - Average deprivation of retail centre catchments, utilising a postcode-based method.

We also provide retail centre catchments, delineated using the HERE REST API:
- Drive-time catchments for all centres not classified as 'Small Local Centres'.
- Walking catchments for all centres not classified as 'Small Local Centres'.

### Safeguarded - available [HERE](https://data.cdrc.ac.uk/dataset/retail-centre-indicators). 

For a subset of the retail centres we also provide some Safeguarded, highly-sensitive indicators:
- Composition indicators: proportions of different types of retail (e.g. Comparison, Service).
- Diversity indicators: ownership (independent, chains), clone town likelihood score.
- Vacancy indicators: proportions of vacant units, short & long-term vacancy rates

----

## Code

Code is available to see how some of these indicators were assembled:

- [E-Resilience Score: Calculating Online Exposure](https://github.com/ESRC-CDRC/Retail-Centre-Indicators/blob/main/Analysis%20Code/Calculating%20Online-Exposure.R).
- [Drive-Time & Walking Catchments](https://github.com/ESRC-CDRC/Retail-Centre-Indicators/blob/main/Analysis%20Code/Retail%20Centre%20Catchments.R).
- [Deprivation: Calculating Deprivation Exposure](https://github.com/ESRC-CDRC/Retail-Centre-Indicators/blob/main/Analysis%20Code/Postcode-based%20Deprivation%20Profiles.R).

Code for the other Open-Access and Safeguarded indicators is unfortunately not available, as these indicators were derived using the secure LDC dataset in the UCL Data Safe Haven.

