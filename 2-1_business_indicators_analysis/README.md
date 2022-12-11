## business_indicators_analysis

The project is automatically checked in the SQL simulator. In an independent project of this course, work is carried out with a database that stores information about venture funds and investments in startup companies. This database is based on the Startup Investments dataset published on the popular Kaggle data research competition platform.

## Data:
### visits_log_short (server log with information about site visits):
- `User Id` — a unique user ID;
- `Device` — user's device category;
- `Session start` — date and time of the session start;
- `Session End` — date and time of the end of the session;
- `Channel` — ID of the advertising source from which the user came;
- `Region` - the user's country;

### orders_log_short (information about orders):
- `User Id` — the unique ID of the user who made the order;
- `Event Dt` — date and time of purchase;
- `Revenue` — revenue;

### costs_short (information about marketing costs):
- `Channel` — the identifier of the advertising source;
- `Dt` — date;
- `Costs` — costs for this advertising source on this day.

## Results
In the course of the work, it was determined that the total amount spent on marketing was 105497.3. The most expensive advertising costs in TipToc - 52% of the entire budget and "FaceBoom" - 31%. These two channels eat up more than 80% of the entire advertising budget. These are the most popular channels for attracting users both by number and by the share of paying users: "FaceBoom" - 3557 people, "TipTop" - 1878 people. Spending on "TipTop" advertising gradually increased during the period under review. The second channel for advertising spending is "FaceBoom". Costs by the 25th week reached the level of 1400 per week and kept at this level longer. The cost of attracting one user to TipTop is 2.79. This is more than 2 times more than the nearest successor - "FaceBoom" (1.11) and "AdNonSense" (1.01).

General advertising charts show that it does not pay off on day 14.ROI at the end of 2 weeks is about 80%.
CAC is growing at the beginning, from mid-May to early July there is a sharp jump up, but after the first week of September it stabilized.
The LTV indicator is quite stable, at the end of September a downward trend begins to form. Average CAC per user for the entire project: 1.1.Significantly higher than this value is the CAC on the channel "TipTop". "FaceBoom" and "AdNonSense" are in the area of this figure, all the others below. Dynamics of the cost of attracting users - "TipTop" stands out. The cost of which is growing rapidly every month. ROI calls that "TipTop", "FaceBoom", "AdNonSence" do not pay off on advertising.
Broken down by country , we have the following data:
- Advertising does not pay off in the USA. On the 14th day, the payback is slightly more than 0.6. In other countries, payback begins with 4-5 days of life time.
- The cost of attraction is stable and similar for all countries except the USA. There it is noticeably higher and changes abruptly with an upward trend, in mid-September the curve reached the pan.
- The dynamics of the US LTV is stable enough and is in the region of 1.0
The rest of the countries have major peaks and dips.

Based on the above , I can draw the following conclusions:
- The USA is a complete failure in payback, something needs to be changed here;
- the most expensive advertising in "TipTop", "FaceBoom", "AddNoSence" also does not pay off. Is it worth spending so much more on these channels?
- you can pay attention that at a lower cost FaceBomm brought more users than TipTop. Perhaps it makes sense to redistribute spending on these channels and spend most of it on a more profitable "FaceBoom".

Now we can say that three of "RocketSuperAds", "lambdaMediaAds", "MediaTornado" can be singled out as promising channels. They are arranged in the order of importance of the most promising - "RocketSuperAds". This channel has an average of three LTV and also an average LTV dynamics. But by the end of the research interval, the dynamics of the cost of attracting users drops to the level of the outsider of this three - "MediaTornado". ROI are close enough in terms of indicators to draw conclusions from them. But the dynamics of ROI increased significantly after mid-August. "RocketSuperAds" is better at retaining paying users than others. In terms of the number of paying "RocketSuperAds" is also the leader. Applying similar conclusions, I conclude that the most promising channel of attraction is "RocketSuperAds".

## Stage
Project is fully completed
