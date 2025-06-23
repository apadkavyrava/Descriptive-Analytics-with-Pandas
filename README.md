####  About
A company distributing intelligent toothbrushes wanted to understand user behavior on their platform. 
The goal was to extract actionable insights from brushing activity data to inform product and engagement strategies.

#### Business Context
Business stakeholders were interested in core usage metrics. 
However, traditional SQL-based analysis proved insufficient due to the conditional and cumulative nature of the usage definitions 
(e.g., brushing patterns, side durations, session validation). As a result, the analysis was conducted using Python, Pandas.

#### Data 
User infomation
| id      | timestamp           | left        | right       | top         | down        |
|---------|---------------------|-------------|-------------|-------------|-------------|
| user id | session start time  | duration sec| duration sec| duration sec| duration sec|

Group information 
| id      | group           |
|---------|-----------------|
| user id | activity group  |


#### Analysis 
The analysis.ipynb file aggregates raw brushing data and group information to compute user-level usage metrics and group-level 
activity rankings, answering key stakeholder questions

#### Outcome 
The analysis results were delivered in the form of two Excel files: one containing detailed usage metrics for each user, 
and the other presenting aggregated group-level activity rankings
