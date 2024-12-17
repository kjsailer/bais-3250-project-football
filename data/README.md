# Data
---

### Folder Meanings
* Raw - unclean data from the source
* Cleaned - data ready to be analyzed and visualized (cleaned and merged)

### Data Dictionary
| Field       | Type              | Source         | Description                                   |
|-------------|-------------------|----------------|-----------------------------------------------|
| team_name   | Text              | All            | Name of team                                  |
| team_level  | Text              | All            | Level of play (HS, College, NFL)             |
| conference  | Text              | College, NFL   | The conference the team is in (e.g., AFC)    |
| state       | Text              | HS, NFL        | What state the team is located in (e.g., IA) |
| ypg         | Numeric           | All            | Offensive yards per game                     |
| ppg         | Numeric           | All            | Points per game                              |
| ppg_a       | Numeric           | All            | Points per game allowed                      |
| ppg_diff    | Numeric, derived  | All            | ppg – ppg_a                                  |
| off_tds     | Numeric           | All            | Touchdowns scored on offense                 |
| W           | Numeric           | All            | Wins                                         |
| L           | Numeric           | All            | Losses                                       |
| rush_ypg    | Numeric           | All            | Rushing yards per game                       |
| pass_ypg    | Numeric           | All            | Passing yards per game                       |
| rush_tds    | Numeric           | All            | Rushing Touchdowns                           |
| pass_tds    | Numeric           | All            | Passing touchdowns                           |
| win_pct     | Numeric, derived  | All            | Wins/Games Played                            |
