# Kickstarting with Excel

## Overview of Project
Our customer, Louise and her Team, ran a fundraiser for its play "Fever". Although she came close to the established goal, the team was not able to achieve it. Louise's team wants to know how they did compared to some other fundraisers.

### Purpose
Determine the effectivenes of fundraisers related to the "Theater" category, "Plays" sub category. We want to know how the "Fever" play did comparing to some other plays, using the launch date and the established goals for the different fundraisers we have record of.

## Analysis and Challenges
To determine how "Fever" did, we have performed two different analysis:

1. Outcomes based on launch date.
2. Outcomes based on goals

### 1. Analysis of Outcomes Based on Launch Date
We have analyzed the tends for "plays" based on the launch date. 

![Outcomes based on launch date](/resources/Theater_Outcomes_vs_Launch.png)

As we can see in the graph above, the "failed" projects trend is pretty much steady. This statement applies for all years and year 2016, the year "Fever" fundraiser was launched. The trend for "successful" projects is different along the year. 

There is a good chance a fundraiser success during the first five months of the year. We can see an upwards trend when it comes to successful projects. Starting the month on June, the trend is downward. Although we cannot explain why this happens (we do not have that data), there is a correlation between the time of the year and the probability of a project to succeed. 

### 2. Analysis of Outcomes Based on Goals
For the analysis based on goals, we can observe the following

![Outcomes based on goals](/resources/Outcomes_vs_Goals.png)

There is a correlation between the goal and the project's probability of success. We can see in te graph that the larger the goal, the bigger the chances of failure. This trend is inverted when it comes to projects with a goal between $35,000 and $44,999. It is unclear for us why this happens, but for the rest of our ranges, our statement holds true.

### Challenges and Difficulties Encountered
- We are unsure about why the projects launched later than June, have a biggest chance of failure. We may overcome this by asking people why they do not feel supportive around that time of year.
- We cannot explain why projects with a goal between $35,000 and $44,999 have a  increased chance of success. To overcome this, we need more data about the projects: how they managed their campaigns, any target populations, payment methods, campaign channels.

Technical difficulties:
1. When implementing the COUNTIFS formula, I was unsure about how to establish a range for the goal.
2. When creating the pivot table for the "outcomes by launch date" analysis, the column "Years" we created using the YEAR() formula, was duplicating the Year field created by Excel when selecting the "Date Created Conversion" as a row.

## Results
### What are two conclusions you can draw about the Outcomes based on Launch Date?
1. There is an upward trend for fundraises between January and May. This may suggest these are good months to start a project
2. From June to december, the trend goes down. This means the chances of success for a fundraiser diminish as we move along the year.
3. There is almost no variation for failed projects when it comes to launch date analysis. The same goes for canceled projects.

### What can you conclude about the Outcomes based on Goals?
It is clearly visible that the larger the goal, the biggest the chances of failure. It is recommended not to set a very high goal. What is outstanding is the success rate for projects between $35,000 and $44,999. That trends seems not to be valid. The "Fever" Team may want to try its luck, but I would not recommend that. 

### What are some limitations of this dataset?
The data we currently have does not explain why the data behaves this way:
1. We canot explain why projects fail when launched by June or after
2. We cannot explain why projects with a goal between $35,000 and $44,999 have a bigger success rate than projects with a goal at $25,000, for instance.
3. It would be ideal to know where the backers are coming from. That would allow us to target those populations better.

### What are some other possible tables and/or graphs that we could create?
1. Success rate per Category/sub-category: If we identify a sub-category with a high success rate, we can ask what they are doing to do so well.
2. Success rate by Country: Do we have cultural differences when it comes to different kind of projects? What is the population in GB more likely to support Vs the population in the US?
3. Staff pick Vs Spotlight: Do movies with this recommmendations have a higher chances of success?
