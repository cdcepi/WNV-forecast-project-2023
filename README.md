## 2023 CDC West Nile Virus Forecasting Challenge

This is the data repository for the 2023 CDC West Nile virus Forecasting Challenge. This is an _**open**_ forecasting challenge to predict **monthly** West Nile virus (WNV) neuroinvasive disease cases in **U.S. states** during the 2023 calendar year.

### Forecast Reports
Forecast summary reports are released monthly and are available [here]/(monthly-forecast-reports/). These reports aggregate submissions from modeling teams (submitted prior to the most recent as time of publishing), a forecast ensemble developed from individual model submissions, 10-year historical medians, and a baseline model built on historical data. All forecasts are provided at the state-month level through the end of the year and predict reported cases of West Nile virus neuroinvasive disease (WNND).

### Participation
To participate in the Challenge, please follow these steps:
1. [Request WNV data](Data-Human.md) by sending a signed Data Use Agreement to <vbd-predict@cdc.gov>.
2. Prepare [metadata](Forecast-Submission.md#Data-formatting) for your model.
3. [Submit forecasts](Forecast-Submission.md#Making-a-submission) by the deadlines.

For information on submitting forecasts to this project, please see the [submission instructions](Forecast-Submission.md). Participating teams provide their [forecasts](data-forecasts/) in a [quantile-based format](Forecast-Submission.md#Data-formatting) that will be evaluated according to [these criteria](Evaluation.md). 

### Timeline
- Project announcement and historical data release: January 31, 2023.
- Initial forecast submission due: April 30, 2023.
- Subsequent forecast submissions due at the end of each month through September: May 31st, June 30th, July 31st, August 31st, and September 30th, 2023.
    - Each forecast submission should include forecasts for all remaining months of 2023.

### Available and Suggested Data Resources
- Human WNV case data: state-month WNV case counts reported to the CDC are [available through request as detailed](Data-Human.md).
- Mosquito data: recent and historical county-month mosquito abundance and infection data is [available through our partners at VectorSurv and local public health agencies](Data-Mosquito.md).
- Environmental data: a list of optional resources for climate and other [environmental data](Data-Environmental.md) are provided. If you come across other resources, please let us know and we'll add them to the list.

## Background
[West Nile virus](https://www.cdc.gov/westnile/index.html) (WNV) is the leading cause of arboviral disease in the contiguous United States. An estimated 70–80% of WNV infections are asymptomatic; 20‒30% of infected persons develop an acute systemic febrile illness and <1% of infected persons develop neuroinvasive disease (e.g., meningitis, encephalitis, or myelitis). Among patients with neuroinvasive disease, the case-fatality ratio is approximately 10%. Because of its severity and distinctive clinical features, diagnosis and reporting of neuroinvasive disease is considered more consistent and complete than that of non-neuroinvasive disease.

The first cases of WNV disease in the United States were identified in New York City in 1999; the virus subsequently spread westward, reaching the Pacific coast in 2003. Since then, WNV has caused seasonal summer outbreaks that vary in size and location, with most areas having sporadic disease or intermittent outbreaks. No vaccine or specific treatment of WNV is currently available. Reducing mosquito exposure through vector control and personal protective behaviors are the primary forms of prevention. Predicting where and when WNV transmission will occur could help direct control efforts.

Previous WNV forecasting challenges were run in [2020](https://github.com/cdcepi/WNV-forecast-project-2020) and [2022](https://github.com/cdcepi/WNV-forecast-data-2022) to predict total WNV neuroinvasive disease cases in U.S. counties over those two calendar years. [Results from the 2020 challenge](https://parasitesandvectors.biomedcentral.com/articles/10.1186/s13071-022-05630-y) showed that models based on historical case data outperformed more sophisticated models. The 2023 challenge focuses on state-level outcomes (rather than county-level outcomes) to assess the ability of forecasts to predict larger scale differences between years. Moreover, the 2023 challenge focuses on monthly rather than yearly outcomes, so that models can be assessed for their ability to predict when cases will occur, not just how many are reported, and will have the opportunity to integrate real-time data within the season. 

The 2023 WNV forecasting challenge is partially supported through a partnership between NOAA (National Oceanic and Atmospheric Administration) and the CDC.

## Data License and Reuse
We are grateful to the teams who have generated forecasts and made their forecast data publicly available under different terms and licenses. By default, forecasts are available under the CC-BY 4.0 license, although teams may specify release under a different license in their metadata. You will find the licenses (when provided) within the metadata contained within model-specific folders in the [data-forecasts](data-forecasts/) directory. Please consult these licenses before using these data to ensure that you follow the terms under which these data were released.

