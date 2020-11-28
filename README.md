The Rate of Suicides by Various Factors
================
Tutorial 3 Team 10

When we were first planning this project we had many ideas but
ultimately one stood out. For our project we decided to use a global
suicides statistics dataset, sourced from kaggle, a popular website
where data scientists can publish their datasets for others to use.

We decided to use the suicides dataset because it met all the
requirements with observations, columns etc, and we also thought it
would be an interesting topic to explore and present to the class.

The dataset we are using contains 27820 rows (observations) and 12
columns (variables) spanning 101 countries and 31 years. Each row
indicates an observation which is grouped by gender, age group, country
and year respectively. The rows are ordered first by country in
ascending order, then year in ascending order, then finally suicides per
100k population in descending order.

Some of our main columns are stated below:

  - `country`: Suicide in specific country. \[STRING\]
  - `year`: Year in which the group committed suicide. \[INTEGER\]
  - `sex`: Sex of group. \[STRING\]
  - `age`: Age of group. \[STRING\]
  - `suicides/100k pop`: Suicides per 100k of population grouped by
    country, year, sex, age. \[FLOAT\]

Our question for this project is to explore the effect of various
factors on the rate of suicide by country. Our question is relatively
broad and for good reasoning, this allows us to effectively use most of
the variables and data without missing out on key information. The
visualizations will be created using various packages including
tidyverse, and the use of many elements including filter, group and the
geom\_smooth, geom\_text and geom\_sf to name a few. We decided to use 4
main data visualizations for this dataset, these include:

Producing a heat map of the global suicide rates.

Visualization of how gdp per capita effects suicide rates.

Visualization of how the human development index (HDI) effects suicide
rates.

Comparing how suicide rates have differed throughout years, and
filtering for significant events.

When these visualizations were created, we found several interesting
outcomes in the dataset. When plotting the heat map we found that the
highest suicide rates generally came from eastern Europe, with Russia
having the highest suicide rates for a major country. By zooming in on
Europe and South America, two dense continents, we can see clearer, and
observe that Lithuania and Hungary are closely following. We can also
see the lowest suicides rates, with the United Kingdom and Brazil being
shown having the lightest shade of red.
