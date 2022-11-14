# Crowd_sourcing
# Kickstarting with Excel

### Overview of Project
We are helping a playwright find the best time to launch a kickstarter campaign for their play. The main factors we will be looking at are launch date and funding goal.


### Analysis and Challenges
Before diving into our analysis we'll format and clean a few things. On campaigns with no backers we replace the blank fields with zeros. Then we break down the data by category and subcategory. Using a pivot table we cam see for each month how many campaigns that launched were successful, failed or cancelled. Following that we group the campaigns by whether their goals fall into a dollar amount range bins.

## Results
### Analysis of Outcomes Based on Launch Date
![Resources/Theater_Outcomes_vs_Launch](/Resources/Theater_Outcomes_vs_Launch.png)

Looking at the chart above we can see that the total amount of campaigns is the greatest durring May with a steady decline until arount the end of summer. There is also a small jump in October before it contiues to decline through to the end of the year. May is also when the greatest portion of total campaigns were successful. Going by launcn date we can come to the conclusion that we will face the greatest success launching a campaign durring the Summer.

### Analysis of Outcomes Based on Goals
![Resources/Outcomes_vs_Goals](/Resources/outcomes_vs_goals.png)
From this chart we can see that it is more likely to find success with a smaller funding goal. On average goals higher than $10000 has less than a 50% chance of getting succesully funded.

### Limitations
We are missing a fair amount of data that could give us context about how a campaign reached their goal. The successful ones may have done things to generate traffic to their kickstarter while unsucessful ones may have not promoted theirs as much. The successful campaigns could also simply be for plays with about a generally liked thing while the unsuccessful ones could be about something more obscure.

