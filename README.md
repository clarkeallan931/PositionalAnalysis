
# Fantasy Football

-- Slide Deck -- https://docs.google.com/presentation/d/1d8KF98Wnp8bUQS28Q3JNc9CPUW60VjPkxbK3phd-biY/edit?usp=sharing

Fantasy Football is a popular math-based game that engages 29 million participants each year. The standard league involves assembling a roster of real-life athletes whose on-field performances determine the scoring of your team. Competing head-to-head against league members, the goal is to compile the team with the most points to secure weekly victories. Win enough weeks and you make the playoffs. Win the Playoffs to become Champion!

A Fantasy season begins on draft day, when teams take turns selecting players to fill out their roster. Drafting strategy is crucial as it lays the foundation for your season.

![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/4e46c4ce-04de-4256-8c28-52c78dd4570c)
![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/6da89ae8-59e2-47b4-b084-566f3587e3b3)

Once teams are set, the real action begins. Teams face off against each other weekly, setting the lineup that they think will score the most points. 

![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/b2f8edc9-8a4f-4e20-ad5d-cd43a37c4b30)

With the actions taken on field reflected in the scores, Fantasy players spend endless time analyzing the available data to try and find an edge. Matchups, injuries, recent performances, bye weeks, weather and location, Offensive and Defensive philosophies are just some of the factors that can impact how many points a player may score.

One of the great data gathering events for Football is the NFL Combine. It is a week-long invitation only showcase where college football players perform physical and mental test in front of NFL coaches, General Managers, and Scouts.  Some of the events include: 40 yard dash, Bench Press, Vertical Jump, Broad Jump, 3 Cone Drill, Shuttle Run. 

An athletes performance can affect their draft status, salary, and ultimately their career. So we decided to investigate, using the Combine data, if there was any correlation between Combine performance and Fantasy Points (PPR) scored.

## Analysis
### Are Combine results correlated to an increase in Fantasy Points?

**Combine Athlete by Position:**
![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/5abcb179-75da-4257-9285-2036bd13a389)

**Fantasy Points Scored by Year Breakdown:**
![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/efac36a2-e073-4f26-b31f-2d30b32a94a8)

Fantasy Pts Scored has a pvalue 0.0 and does not follow a normal distribution.

A dip in points occured in 2017 and 2020. 2017 had low QBR and rushing yards per attempt. 2020 had special Covid rules enacted.


![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/034d7e8a-49d4-4a46-a27d-6dccfd773339)
![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/36a10283-44f3-45a5-a04e-612170c3e853)


Kicking data is lacking, while the althetic profiles of various positions is similar.
The 40 yard dash has a pvalue= 3.657943670686471e-49. A lower 40 time is good, leaving to potentially skewed data.

**Fantasy Points per Combine Event:**

![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/a45b8c39-27a7-42c4-a155-c9ba4790eac1)

![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/5451a75f-726e-4bd6-8561-5fd125fa3cb9)
![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/0f98ad52-4d6f-48ff-8f6d-0542ceb52133)
![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/9fc71ee7-e5ed-44cd-b384-1e4b005f4d1d)

After scatter plot and regression the analysis of combine results measured against fantasy points: 
- WR Fantasy Production by Shuttle Time: 
R-squared = .004
- WR Fantasy Production by 3 Cone Drill
R-squared = .006
- WR Fantasy Production by 40 Time 
R-squared = .006
- RB Fantasy Production by Shuttle Time
R-Squared= .005
- RB Fantasy Production by 3 Cone Drill:
R-Squared= .002 
- RB Fantasy Production by 40 Time:
R-Squared= .002 

With the R-Squared at less than .00 for the charts. There is little correlation between Combine results and Fantasy points.

Without much correlation to Career points, we began breaking the data down further by age range.

**Age and Fantasy Points:**

Using the Top 16 highest scorers for WR and RB. You can see a trend of the top scorers becoming younger. 

![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/95d8b9b6-9ec0-42a0-9660-1e9b6cba95f9)

Comparing this across postions, RB age is much lower than WR or TE.

![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/e8057dfe-295f-42a5-812f-02f8dbef7f32)

This is also visible when you compare Age 22 and 28 Wrs and RBs.

![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/beee2a1c-655e-4cc8-9e6b-670516837043)
![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/414aca6a-5b70-4b9f-8b5a-6f2bf6cb242a)

# Conclusions

**Do Combine results lead to more fantasy points?**

With R-Squared scores under .00, we did not find correlation between Combine results and Total Fantasy Points.

- WR Fantasy Production by Shuttle Time: 
R-squared = .004
- WR Fantasy Production by 3 Cone Drill:
R-squared = .006
- WR Fantasy Production by 40 Time: 
R-squared = .006
- RB Fantasy Production by Shuttle Time:
R-Squared= .005
- RB Fantasy Production by 3 Cone Drill:
R-Squared= .002 
- RB Fantasy Production by 40 Time:
R-Squared= .002


**Does the age of player lead to more fantasy points?**

Yes, the mean age for top performing RB (over 150 fantasy points in a season) has dropped since 2000. The standard deviation has also declined for both RB’s and WR’s meaning that there are fewer exceptions than there were in 2000 and 2010.
![image](https://github.com/AiMO-MO-MO/Project-_FF/assets/130156500/78cac6ad-a82f-43fc-b57a-d73027e2d161)

According to our results, Combine results do not correlate to the amount of fantasy points a player may score. However, the age of the player did correlate to more points. With trends pointing to more younger players, especially in RBs, being included in the Top 16 highest scorers. Athleticism generally declines as a player gets older. This could still matter, but the Combine may not be the best metric to determine this.

**Limitations**
- Combine is invite only and once per year
- All positions are eligible, only certain used in fantasy
- Events are athletically specific, not football specific
- Different positions have different athletic needs
- Fantasy Points may not be reflective of Team goals
- Fantasy Leagues have many scoring setups/settings

**Misc Observations**
- Bench by 40 had largest R-Squared .22
- 2017 and 2020 had large Total Points drops
- 2020 data had the most outliers
- WR R-Squareds the largest of any position
- TEs are late bloomers compared to RB and WR
- Slowest kickers are not as slow as the slowest QBs
- QBs have the longest careers and greatest total points


## Group Members:
- Avani Patel
- Clarke Allan
- Matt Owens
- Banesa Casillas

## Data Sets: 
- Fantasy Points: Fantasy CSV Data https://github.com/bendominguez0111/fantasy-csv-data?tab=readme-ov-file
- NFL Combine Results: Kaggle NFL Combine Results https://www.kaggle.com/datasets/mitchellweg1/nfl-combine-results-dataset-2000-2022

## Technologies:
- Python
- Jupyter Notebook
- ChatGPT
