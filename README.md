# The Rollercoasters Project
Rollercoasters. Thrill, excitemente and fear. In order to identify the deadliest roller coasters, we will take the way to analyze if there is any relationship between accidents and rollercoasters' features - height, speed, material of construction, running time, location and other characteristics - which may shed some light to why some rollercoasters insist to fail more than others. Obviously maintenance is among the most important characteristics when it comes about rollercoster integrity but it is right now out of our scope - we will try to check correlation without causation for instance.

![Roller Coaster](https://i.ytimg.com/vi/p-fOfVsM7jE/maxresdefault.jpg)

## The source material

We will be using the Roller coasters API (https://github.com/german-alvarez-dev/api-coasters) and the Rides Database (https://ridesdatabase.org/saferparks/data/).
The first step of the work is focusing on cleaning both datasets and preparing them for a join, so we can have more information about the rollercoasters (through the API) which presented failures during the period studied (Rides Database) and hence establish (lack of) relationships between the features.

This work will span through some months and we will be employing various data cleaning, data analysis and hopefuly, some machine learning techniques to cluster data and predict patterns of our beloved rollercoasters.

So the steps will be:

1. Data Engineering:
  - Extract the data from the API with a Python file, storing it in a database (MySQL for instance).
  - Extract the data from the rides database, storing it in a database (MySQL as well).
  - Plug the database into PowerBI.
2. Data Science:
  - Analyzing correlations (with failures or within features) and trends.
  - Using machine learning techniques to predict:
    - Probability of failure.
    - Features of a rollercoaster based on other features.
    - Grouping rollercoasters based on their failure type.
    - Etc.
3. Business Intelligence:
  - Visualizing the rollercoasters based on their features.
    - The fastest ones.
    - The highest ones.
    - The deadliest ones.
  - The Most Common Failures.
  
  ## (Not so fun) Facts
  - Action Park in New Jersey is known as the most dangerous amusement park in the country, six people passed away from 1980 to 1987. From 1984 to 1985 there were 26 head injuries and 14 broken bones reported. The park closed in 1996 after several personal injury lawsuits were filed against it.
  - In 2008 a teenager was decapitated by the Batman roller coaster at Six Flags Over Georgia when he jumped the fence to retrieve his hat.
  Other interesting data on rollercoaster accidents: https://bmwlawgroup.com/amusement-park-injury-statistics/
  
