---
title: Demand Modelling
summary: Novel method to size storage with the aim of maximizing storage utilization and eliminating wasted storage capcacity.
tags:
  - Demand
date: '2016-04-27T00:00:00Z'

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

Oxford’s building electricity demand is modelled using Elexon electricity settlement profiles. The Elexon profiles were constructed using half-hourly demand data sampled from Great Britain. There are 120 Elexon profiles, divided into eight classes of domestic and commercial consumers, example profiles are shown in Figure 1. Within each class, the profiles are further divided into five seasons: winter, spring, summer, high summer, and autumn. Additionally, within each season, the profiles are categorized into three types of days: Weekday, Saturday, and Sunday. For each of the eight Elexon profile classes, the profiles are compiled into an hourly demand profile spanning a year based on the day of the week and the season.
{style="text-align: justify;"}

{{< figure src="figure-hourly-demand.jpg" caption="Elexon hourly electricity demand profiles." numbered="true" >}}

The BEIS (UK’s Department of Business, Energy and Industrial Strategy) provides statistics on the number of meters in each district. The number of domestic meters for Class 1 and 2 is provided individually. Elexon profiles for Class 1 and 2 are then scaled according to the number of meters in the city of Oxford. The number of non-domestic meters in Class 3 to 8 is lumped together. Since Class 3 to 8 model non-domestic consumers with increasing demand levels, the analysis assumes the demand level is related to the company size in terms of employees. For example, demands for small companies are modeled by Class 3, and large companies by Class 8. The ONS (UK’s Office of National Statistics) provides statistics on the number of companies in each district and their sizes. Elexon profiles for Class 3 to 8 are then scaled according to the number and size of the companies in the city of Oxford.
{style="text-align: justify;"}

Elexon profiles were originally developed in 1997. Since then, domestic demands have decreased due to more efficient appliances, while non-domestic demands have increased due to new technologies and increased business activities. To account for these changes, correction factors are calculated using linear regression. First, demand profiles are assembled for all districts in the UK, and annual demands are calculated from these profiles. Then, the calculated demands and actual demands are fed through linear regression to obtain the correction factors, as shown in Table 1. The normal distribution of company sizes in each district causes high collinearity in company size data. To work around this collinearity, annual demands from Class 3 to 8 are combined and fed through to linear regression, yielding a single correction factor. The correction factors reduce the discrepancy between actual and calculated annual demands by more than 90\%, as suggested by the R-Square values. The P-Values are less than 0.05, indicating significant correlations between calculated and actual demands. Lower and Upper 95% values define the lower and upper bounds of the 95% confidence interval within which correction factors reside.
{style="text-align: justify;"}

Table 1 : Correction factor from linear regression.
| Class | Correction Factor | R-Square | P-Value | Lower 95% | Upper 95% |
| :--- | :---: | :---: | :---: | :---: |  :---: |
| Profile Class 1 | 0.84 | 0.99 | 0 | 0.83 | 0.85 | 
| Profile Class 2 | 0.72 | 0.96 | 0 | 0.70 | 0.73 | 
| Profile Class 3 | 2.65 | 0.90 | 0 | 2.56 | 2.73 | 


These correction factors are applied to the previously determined scaling for each class. The scaled profiles from each class are then added together to form Oxford’s demand profile, as shown in Figure 2. The demand profile exhibits slight peaks at night from Economy meters that have cheaper nightly electricity price. Demand then rises in the morning, peaks at noon, and drops in the afternoon. It peaks again at 5 pm when working hours end, then decreases in the evening. Demand is highest during weekdays and lowest on Sundays because non-domestic demands dominate in Oxford. Furthermore, demand is highest during winter and lowest during high summer, with demand variation also greater during winter. The present approach is benchmarked against another approach, where real-time national hourly demand data is scaled down according to the district’s population. When compared, the present approach’s annual demand is 9% closer to the actual value than the benchmark approach.
{style="text-align: justify;"}

{{< figure src="figure-annual-demand.jpg" caption="Hourly electricity demand profile for the city of Oxford." numbered="true" >}}
