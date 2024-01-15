---
title: Electricity Demand Model
summary: Novel method to model electricity demand in the city of Oxford.
tags:
  - Demand
date: '2022-07-08T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart

links:
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''
slides: ''
---

Oxford’s building electricity demand is modeled using Elexon electricity settlement profiles. The Elexon profiles were constructed using half-hourly demand data sampled from Great Britain. There are 120 Elexon profiles, divided into eight classes of domestic and commercial consumers; example profiles are shown in Figure 1. Within each class, the profiles are further divided into five seasons: winter, spring, summer, high summer, and autumn. Additionally, within each season, the profiles are categorized into three types of days: Weekday, Saturday, and Sunday. For each of the eight Elexon profile classes, the profiles are compiled into an hourly demand profile spanning a year, based on the day of the week and the season.
{style="text-align: justify;"}

{{< figure src="figure-hourly-demand.jpg" caption="Elexon hourly electricity demand profiles." numbered="true" >}}

The BEIS (UK’s Department of Business, Energy and Industrial Strategy) provides statistics on the number of meters in each district. The number of domestic meters for Class 1 and 2 is provided individually. Thus, the annual profiles for Class 1 and 2 are scaled according to the number of meters in the city of Oxford. The number of non-domestic meters in Class 3 to 8 are lumped together. Since Class 3 to 8 model non-domestic consumers with increasing demand levels, the analysis assumes the demand level is related to the company size in terms of employees. For example, demands for small companies are modeled by Class 3, and demands for large companies are modeled by Class 8. The ONS (UK’s Office of National Statistics) provides statistics on the number of companies in each district and their sizes. The annual profiles for Class 3 to 8 are then scaled according to the number and the size of companies in the city of Oxford.
{style="text-align: justify;"}

Elexon profiles were initially developed in 1997. Since then, domestic demands have decreased due to more efficient appliances, while non-domestic demands have increased owing to new technologies and heightened business activities. To address these changes, correction factors are calculated using linear regression. Initially, demand profiles are compiled for all districts in the UK, and annual total demands are calculated from these profiles. Subsequently, the calculated demands and actual demands undergo linear regression to derive the correction factors, as illustrated in Table 1. The normal distribution of company sizes in each district induces high collinearity in company size data. To address this collinearity, annual demands from Class 3 to 8 are combined and processed through linear regression, resulting in a single correction factor. These correction factors substantially reduce the discrepancy between actual and calculated annual demands by more than 90%, as indicated by the R-Square values. The P-Values, being less than 0.05, show significant correlations between calculated and actual demands. The Lower and Upper 95% values define the lower and upper bounds of the 95% confidence interval within which correction factors reside.
{style="text-align: justify;"}

Table 1 : Correction factor from linear regression.
| Class | Correction Factor | R-Square | P-Value | Lower 95% | Upper 95% |
| :--- | :---: | :---: | :---: | :---: |  :---: |
| Profile Class 1 | 0.84 | 0.99 | 0 | 0.83 | 0.85 | 
| Profile Class 2 | 0.72 | 0.96 | 0 | 0.70 | 0.73 | 
| Profile Class 3 | 2.65 | 0.90 | 0 | 2.56 | 2.73 | 


These correction factors are applied to the previously determined scaling for each class. The scaled profiles from each class are then aggregated to form Oxford’s demand profile, as illustrated in Figure 2. The demand profile displays slight peaks at night due to Economy meters with a more affordable nightly electricity price. Demand subsequently rises in the morning, peaks at noon, and decreases in the afternoon. It peaks again at 5 pm when working hours conclude, then decreases in the evening. Demand is highest during weekdays and lowest on Sundays, primarily driven by non-domestic demands dominating in Oxford. Furthermore, demand is highest during winter and lowest during high summer, with demand variation also being more pronounced during winter. The present approach is benchmarked against an alternative method, where real-time national hourly demand data is scaled down based on Oxford’s population. Upon comparison, the present approach's annual demand is 9% closer to the actual value than the benchmark approach.
{style="text-align: justify;"}

{{< figure src="figure-annual-demand.jpg" caption="Hourly electricity demand profile for the city of Oxford." numbered="true" >}}
