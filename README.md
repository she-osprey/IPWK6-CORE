# MCHEZOPESA FOOTBALL PREDICTION: A prediction result of a game between team 1 and team 2, based on who's home and who's away, and on whether or not the game is friendly

You have been recruited as a football analyst in a company - Mchezopesa Ltd and tasked to accomplish this: A prediction result of a game between team 1 and team 2, based on who's home and who's away, and on whether or not the game is friendly (include rank in your training).You have two possible approaches (as  shown below) given the datasets that will be provided

*****************
Input: Home team, Away team, Tournament type (World cup, Friendly, Other)

### Approach 1: Polynomial approach

- What to train given:
- Rank of home team
- Rank of away team
- Tournament type
- Model 1: Predict how many goals the home team scores.
- Model 2: Predict how many goals the away team scores.

### Approach 2: Logistic approach

Feature Engineering: Figure out from the home team’s perspective if the game is a Win, Lose or Draw (W, L, D)
## Context

A more detailed explanation and history of the rankings is available here: [https://en.wikipedia.org/wiki/FIFA_World_Rankings] 

An explanation of the ranking procedure is available here: [https://www.fifa.com/fifa-world-ranking/procedure/men.html]

## Dataset Columns

Some features are available on the FIFA ranking page [https://www.fifa.com/fifa-world-ranking/ranking-table/men/index.html].

- Rank
- Country Abbreviation
- Total Points
- Previous Points
- Rank Change
- Average Previous Years Points
- Average Previous Years Points Weighted (50%)
- Average 2 Years Ago Points
- Average 2 Years Ago Points Weighted (30%)
- Average 3 Years Ago Points
- Average 3 Years Ago Points Weighted (20%)
- Confederation
- Date - date of the match
- Home_team - the name of the home team
- Away_team - the name of the away team
- Home_score - full-time home team score including extra time, not including penalty-shootouts
- Away_score - full-time away team score including extra time, not including penalty-shootouts
- Tournament - the name of the tournament
- City - the name of the city/town/administrative unit where the match was played
- Country - the name of the country where the match was played
- Neutral - TRUE/FALSE column indicating whether the match was played at a neutral venue

## Assessment Expectation
In order to work on the above problem, you need to do the following:

- Define the question, the metric for success, the context, experimental design taken and the appropriateness of the available data to answer the given question
- Expected flow for the assessment:
- Perform your EDA
- Perform any necessary feature engineering 
- Check of multicollinearity
- Start building the model
- Cross-validate the model
- Compute RMSE
- Create residual plots for your models, and assess their heteroscedasticity using Bartlett’s test
- Perform appropriate regressions on the data including your justification
- Challenge your solution by providing insights on how you can make improvements.

## Dataset

The dataset and glossary to use for this project can be found here. [https://drive.google.com/open?id=1BYUqaEEnFtAe5lvzJh9lpVpR2MAvERUc] 

## License
[MIT](https://choosealicense.com/licenses/mit/)
