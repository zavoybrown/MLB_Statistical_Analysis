# MLB_Statistical_Analysis
## This project was created in collaboration with members of my cohort in the Data Science Bootcampo at Southern Methodist University.
### The complete analysis, including all visualizations and notebooks can be found here: https://github.com/Focused79/project_slytherinteger

## project_slytherinteger
# MLB statistics analysis

In 1977, Bill James revolutionized Major League Baseball with the release of what came to be known as Sabermetrics. These advanced statistics became widely utilized across the league as a way to more accurately appraise player performance. In 2002, the Oakland Athletics were the first team in Major League Baseball to adopt this new scouting philosophy by recruiting players that were undervalued from a salary standpoint, but could contribute to the overall success of their team by succeeding in key statistical areas, like on-base-percentage, the amount of times that a player reaches first base per total number of batting appearances. A small market team, the Oakland Athletics appeared in the American League Championship Series in 2002 with one of the lowest payrolls in baseball. 

This analysis takes a deep dive to examine is there a direct correlation between spending and a teams overall success using key statistical metrics. Many teams in the MLB must run on strict budgets because of the market that the team is located in, and with the MLB being a soft-cap league, spending is not equal for each team. We zoom in on three areas, pitching, batting, and overall win-rate through the lens of salary. By analyzing key metrics in offensive and defensive statistics versus salary, we will find out how much success costs.

the mlb_offense notebook covers hits, home runs, and wins, all through the lens of salary. 

The mlb_defense notebook takes a look at defensive metrics. Strikeouts, ERA, and wins are broken down by salary in pre and post "Moneyball" eras.

Finally, the mlb_salaries notebook breaks down average salaries for all teams from 1985-2016, identifies outliers to the average salaries, adjusts all salaries to 2016 inflation using BLS CPI data, looks at distributions of salaries in pre and post "Moneyball" eras, and has independent T-Test results for pre and post "Moneyball" era salaries.

Sources:
Lahman MLB data via kaggle.com:
[kaggle.com](https://www.kaggle.com/datasets/deeley/lahman-mlb)https://www.kaggle.com/datasets/deeley/lahman-mlb
