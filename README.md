# Investigate_a_Dataset

### Description

I was intrigued by the Corruption Perception Index that I found on Gapminder and figured it would be a good opportunity to practice choropleth maps to visualize potential correlations with other variables. This project compares global and regional differences in the following metrics for 2017:

[Corruption Perception Index (CPI)](https://www.transparency.org/news/pressrelease/explanation_of_how_individual_country_scores_of_the_corruption_perceptions): Downloadable csv from Gapminder. Draws on 13 surveys from independent institutions specialising in governance and business climate analysis covering expert assessments and views of businesspeople. The CPI generally defines corruption as "the misuse of public power for private benefit." A high CPI equates to less corruption.

[Human Development Index (HDI)](http://hdr.undp.org/en/data#): Downloadable csv from UN Human Development Report. HDI is a three-dimensional index of health level, educational level, and standard of living. A high HDI equates to better quality of life.

[Child Mortality](https://www.gapminder.org/data/documentation/gd005/): Downloadable csv from Gapminder. Defined as the death of children under five years of age per 1,000 live births.

[Total Fertility](https://www.gapminder.org/data/documentation/gd008/): Downloadable csv from Gapminder. Defined as the number of children that would be born to a woman by summing age specific fertility rates over her lifetime.

Questions to consider:
* What does the distribution of data look like for each variable?
* Is there a correlation between CPI and HDI?
* Is there a correlation between child mortality and total fertility?
* Which regions and countries rank highest and lowest in these categories?

### Notes
* Limited rendering in `Investigate_a_Dataset.ipynb`. Plotly features can be seen with nbviewer here.

### To Do
* Choropleth doesn't have legend titles for different categories.
* Revisit conclusions based off level system from Hans Rosling's *Factfulness* instead of outdated "developed vs. developing".
