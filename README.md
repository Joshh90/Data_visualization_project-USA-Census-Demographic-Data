# Data visualization project-USA Census Demographic Data
## Description
As a BI analyst, I decided to analyze US census demographic data sourced from
Kaggle dataset, which includes comprehensive census data for all counties in 2015.
This analysis aims to answer several key questions regarding transportation, income,
poverty, and employment across the United States.
### About dataset
The data was taken from the DP03 and DP05 tables of the 2015 American Community Survey 5-year estimates.
The project data file:
_acs2015_county_data.csv: Data for each county or county equivalent in the US, including DC and Puerto Rico._
[Dataset link](https://www.kaggle.com/datasets/muonneutrino/us-census-demographic-data/data?select=acs2015_county_data.csv)

### Screenshot of datasource in tableau
![Screenshot](https://github.com/Joshh90/Data-visualization-project-USA-Census-Demographic-Data/blob/main/Data%20soure%20screenshot.jpg)

### Visualization tool used
#### Tableau
Tableau is a powerful data visualization and business intelligence tool that allows users to analyze and visualize data interactively. It is widely used to turn raw data into actionable insights through visually appealing dashboards and reports.

#### Full Project resources
[Link]()

#### First visualization report
##### Question addressed with the dataset:
_How many people are employed in each state? What is the category of employment? And in
which percentage?_

A. Link to visualization that answer the question
[Dataset link](https://public.tableau.com/app/profile/joshua.adelakun/viz/USCensusDemographicDataProject_17348489952100/EmploymentCategoriesperstate?publish=yes)
![Screenshot](https://github.com/Joshh90/Data-visualization-project-USA-Census-Demographic-Data/blob/main/Employment%20categories%20per%20state.jpg)

B. Summary
California has the highest number of employed individuals, totaling 17,246,360.

C. Design

Chart Type:
* I used a symbol map to illustrate the state with the highest employment. Symbol
maps effectively convey geographic distributions of employment data.

Color:
* A blue-orange divergent color palette was employed, with the brightest orange
representing the state with the highest employment and the brightest blue for the
lowest.

Size Mark:
* The largest circle on the map indicates the state with the highest employment.
Tooltip:
* Tooltips provide a breakdown of employment categories within each state.
Filter:
* Filters enhance interactivity, allowing users to focus on specific states or regions.
Visual Summary:
After the thorough analysis of the census dataset, I gained a valuable insight about
employment across the United States.

#### Second visualization report
##### Question addressed with the dataset:

_Which State Has the Best Transportation?_

I. Link to visualization that answer the question:
[Dataset link](https://public.tableau.com/app/profile/joshua.adelakun/viz/USCensusDemographicDataProject_17348489952100/Meancommutetimeineachcounty?publish=yes)
![Screenshot link](https://github.com/Joshh90/Data-visualization-project-USA-Census-Demographic-Data/blob/main/Mean%20commute%20time%20in%20each%20county%20screenshot.jpg)

B. Summary
##### Analysis:
I selected the state with the least mean commute time as the one with the best
transportation, as shorter commute times can indicate more efficient transportation
systems.
Defining "Best Transportation"

Criteria for Evaluation:
* Lowest Mean Commute Times: This indicates how efficiently people can travel to
work. Shorter commute times often reflect better transportation systems.

Aggregation Method:
* Mean Commute Times: I calculated the average of the mean commute times for
all counties within each state. Based on my analysis, Alaska has the least average
mean commute time of 11.23 minutes.

Outlier Analysis:
* I identified Matanuska-Susitna Borough County in Alaska as an outlier with an
average mean commute time of 34 minutes. The preceding county, Kenai Peninsula
Borough, has an average mean commute time of 19.70 minutes. To prevent data skew,
I excluded Matanuska-Susitna Borough from my analysis. After exclusion, Alaska
remains the state with the best transportation, with an adjusted average mean commute
time of 10.4 minutes.

C. Design

Chart Type:

I used Bubble charts for the visualization.
Bubble charts allow viewers to quickly compare the commute times across different counties.
The visual proximity of the circles makes it easy to identify which counties have the shortest
commute times at a glance.
Color:
* I used different variant of colors support users of visualization that has color blindness. I
achieved these by using color marks in tableau.
Visualization Summary:
After the thorough analysis of the census dataset, I gained a valuable insight about mean
commune time in each county of USA.


#### DASHBOARD REPORT:
##### Question addressed with the dataset displayed in the dashboard:
A. _Which State Has the Best Transportation?_

I. DASHBOARD SCREENSHOT LINK:
[Dataset link](https://public.tableau.com/app/profile/joshua.adelakun/viz/USCensusDemographicDataProject_17348489952100/UScensusdemodash?publish=yes)
![Screenshot](https://github.com/Joshh90/Data-visualization-project-USA-Census-Demographic-Data/blob/main/Main%20dashboard1.jpg)

II. DASHBOARD SUMMARY

Analysis:
I selected the state with the least mean commute time as the one with the best
transportation, as shorter commute times can indicate more efficient transportation
systems.

Defining "Best Transportation"Criteria for Evaluation:
* Lowest Mean Commute Times: This indicates how efficiently people can travel to
work. Shorter commute times often reflect better transportation systems.

Aggregation Method:
* Mean Commute Times: I calculated the average of the mean commute times for
all counties within each state. Based on my analysis, Alaska has the least average
mean commute time of 11.23 minutes.

Outlier Analysis:
* I identified Matanuska-Susitna Borough County in Alaska as an outlier with an
average mean commute time of 34 minutes. The preceding county, Kenai Peninsula
Borough, has an average mean commute time of 19.70 minutes. To prevent data skew,
I excluded Matanuska-Susitna Borough from my analysis. After exclusion, Alaska
remains the state with the best transportation, with an adjusted average mean commute
time of 10.4 minutes.

B. _How does income-to-poverty ratio look across USA states and counties?_
I used a map to depict the median income-to-poverty ratio across US states. The
analysis reveals that the District of Columbia has the highest median income of$70,848,
with only 18% of its population living below the poverty level. I also drilled
down to show the income-to-poverty ratio in each county.

III. DESIGN

Chart Type:
* I used a bar chart for visualizing the states with the least commute time. Bar
charts allow for straightforward comparisons across categories, making it easy for
viewers to grasp differences in mean commute times.
* Maps provide a clear geographic representation of data, allowing viewers to see
variations in income and poverty levels across states. This spatial context helps identify
regional trends.

```Tooltip: ```
* Tooltips offer a breakdown of median income versus poverty for each state.
  
```Filter:```
* Filters allow users to interact with the map and bar chart, focusing on specific states or
regions, enhancing user engagement.

```Color:```
* I utilized a blue-orange divergent color palette for the bar chart and the graph
ensuring accessibility for viewers with color blindness.
Dashboard:
* Dashboards allow you to combine multiple visualizations into a single view. This helps
users see relationships and trends across different data sets at a glance.
Dashboards in Tableau can include interactive elements such as filters, parameters,
and tooltips. This interactivity allows users to explore the data more deeply and
customize their view based on their specific needs.
Visualization Summary:
After a thorough analysis of the census dataset, I gained a valuable insight about
transportation, income, poverty.
