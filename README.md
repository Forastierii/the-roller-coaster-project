# The Rollercoasters Project
Rollercoasters. Thrill, excitemente and fear. In order to identify the deadliest roller coasters, we will take the way to analyze if there is any relationship between accidents and rollercoasters' features - height, speed, material of construction, running time, location and other characteristics - which may shed some light to why some rollercoasters insist to fail more than others. Obviously maintenance is among the most important characteristics when it comes about rollercoster integrity but it is right now out of our scope - we will try to check correlation without causation for instance.

![Roller Coaster](https://i.ytimg.com/vi/p-fOfVsM7jE/maxresdefault.jpg)

## The source material

We will be using the Roller coasters API (https://github.com/german-alvarez-dev/api-coasters) and the Rides Database (https://ridesdatabase.org/saferparks/data/).
The first step of the work is focusing on cleaning both datasets and preparing them for a join, so we can have more information about the rollercoasters (through the API) which presented failures during the period studied (Rides Database) and hence establish (lack of) relationships between the features.

This work will span through some months and we will be employing various data cleaning, data analysis and hopefuly, some machine learning techniques to cluster data and predict patterns of our beloved rollercoasters.
