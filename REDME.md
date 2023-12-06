# WHO COVID-19 Data
From the 31 December 2019 to the 21 March 2020, WHO collected the numbers of confirmed COVID-19 cases and deaths through official communications under the International Health Regulations (IHR, 2005), complemented by monitoring the official ministries of health websites and social media accounts. 

## Research Question

We can hardly disagree that COVID-19 spreads rapidly and causes significant harm. Here, I'll present the data in a more intuitive manner to stimulate further reflection. Additionally, let's review the impact of the pandemic on European countries during its first year, using the total confirmed cases throughout the year as an example.

* When was the first COVID-19 case reported in the Netherlands, and how long did it take for more than 10,000 cases to be reported?

* When did Belgium report its first COVID-19-related death, and how much time passed before more than 1,000 cases were reported?

* In the first year of the COVID-19 pandemic, which was in 2020, how did the cumulative cases vary across European Union countries?

## Data Download
Data are available for download as the following comma-separated values (CSV) files. For updated cases, deaths, and vaccine data please visit the following sources:

* [Daily cases and deaths by date reported to WHO](https://covid19.who.int/WHO-COVID-19-global-data.csv)

* [Latest reported counts of cases and deaths](https://covid19.who.int/WHO-COVID-19-global-table-data.csv)

* [Vaccination data](https://covid19.who.int/who-data/vaccination-data.csv)

* [Vaccination metadata](https://covid19.who.int/who-data/vaccination-metadata.csv)


## Vocabulary:
1. Date_reported: Date of reporting to WHO (type: date)

2. Country_code: ISO Alpha-2 country code (string)

3. Country: Country, territory, area (string)

4. WHO_region: WHO regional offices: WHO Member States are grouped into six WHO regions -- Regional Office for Africa (AFRO), Regional Office for the Americas (AMRO), Regional Office for South-East Asia (SEARO), Regional Office for Europe (EURO), Regional Office for the Eastern Mediterranean (EMRO), and Regional Office for the Western Pacific (WPRO). (string)

5. New_cases: New confirmed cases. Calculated by subtracting previous cumulative case count from current cumulative cases count.* (Integer)

6. Cumulative_cases: Cumulative confirmed cases reported to WHO to date. (Integer)

7. New_deaths: New confirmed deaths. Calculated by subtracting previous cumulative deaths from current cumulative deaths.* (Integer)

8. Cumulative_deaths: Cumulative confirmed deaths reported to WHO to date. (Integer)

 [*]Users should note that, in addition to capturing new cases and deaths reported on any given day, updates are made retrospectively to correct counts on previous days as needed based on subsequent information received. 



## Language:
The main language of all texts is English.

## Methodology:
This dashboard displays longitudinal measures of Public health and social measures（PHSM）severity and timing by country, territory or area against 7-day rolling average counts of confirmed cases and deaths reported, using the data and methodology developed by Oxford COVID-19 Government Response Tracker (OxCGRT). The OxCGRT data is collected and calculated by the team at the Blavatnik School of Government at the University of Oxford.





## Related resources:


[Public health surveillance for COVID-19: interim guidance](https://www.who.int/publications/i/item/who-2019-nCoV-surveillanceguidance-2020.7)

[Overview of Public Health and Social Measures in the context of COVID-19](https://www.who.int/publications/i/item/overview-of-public-health-and-social-measures-in-the-context-of-covid-19)

[Our World in Data(COVID-19)](https://ourworldindata.org/coronavirus)

