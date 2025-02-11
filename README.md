This covers a litany of stats from the 2000-01 NBA season up to the 2023-24 NBA season. I will be using it for my personal senior project on the economic impact of different team structures. Will post more updates but thought the aggregate spreadsheet could be useful for other people! Sources at the bottom:

Dimension: 717 x 51

Columns:
YEAR – The season year (e.g., 2023 for the 2022-23 season).

TEAM – The full name of the NBA team (e.g., "Golden State Warriors").

TEAM_short – The abbreviated team name (e.g., "Warriors" for Golden State Warriors), this was useful for data matching since sometimes datasets will use short or longer names. 

Payroll – The total team payroll (sum of all player salaries).

Salary Cap – The NBA’s salary cap for that specific season.

Ovr_salary_cap – 0/1 indicator of whether or not the payroll exceeded the salary cap.

Age_avg – The average age of players on the roster.

W – Total wins in the regular season.

L – Total losses in the regular season.

PW – Pythagorean expected wins (based on point differential).

PL – Pythagorean expected losses (based on point differential).

MOV – Margin of Victory (average point differential per game).

SOS – Strength of Schedule (difficulty based on opponent performance).

SRS – Simple Rating System (MOV adjusted for strength of schedule).

ORtg – Offensive Rating (points scored per 100 possessions).

DRtg – Defensive Rating (points allowed per 100 possessions).

NRtg – Net Rating (ORtg - DRtg).

Pace – Pace (estimated possessions per game).

FTr – Free Throw Rate (FT attempts per field goal attempt).

3PAr – Three-Point Attempt Rate (percentage of total shots that are 3-pointers).

TS% – True Shooting Percentage (efficiency considering FT, 2P, and 3P).

eFG% – Effective Field Goal Percentage (weights 3-pointers higher).

TOV% – Turnover Percentage (turnovers per 100 possessions).

ORB% – Offensive Rebound Percentage (percentage of available offensive rebounds secured).

FT/FGA – Free Throws made per Field Goal Attempt.

eFG% (Opponent) – Opponent’s Effective Field Goal Percentage.

TOV% (Opponent) – Opponent’s Turnover Percentage.

DRB% – Defensive Rebound Percentage (percentage of available defensive rebounds secured).

FT/FGA (Opponent) – Opponent’s Free Throws made per Field Goal Attempt.

Arena – Name of the team’s home arena.

Attend. – Total attendance for home games.

Attend./G – Average attendance per home game.

Champ – Binary (1 = Won NBA Championship, 0 = Did not).

Champ_cum – Cumulative number of championships won by the team over time.

Champ_cum_local – Cumulative championships won by the team since relocating AT THAT LOCATION (eg., Sac Kings have 1 championship, 0 local since the 1 championship was in Rochester)

MVP – Binary (1 = Team had league MVP, 0 = No MVP).

MVP_cum – Cumulative number of MVP awards won by players on the team over time.

All_star – Number of players from the team selected as All-Stars. (Need to double check this though, think it may be messed up)

All_NBA – Number of players from the team selected for an All-NBA team. (Need to double check this though, think it may be messed up)

Gs_H – Number of games started at home.

TOTAL_H – Total home games played.

AVG_H – Average home game attendance.

Gs_A – Number of games started away.

AVG_A – Average away game attendance.

TOTAL_overall – Total attendance for the season (home + away).

AVG_overall – Average attendance across all games.

TOTAL_H_YOY – Year-over-year change in total home attendance.

AVG_H_YOY – Year-over-year change in average home attendance.

AVG_A_YOY – Year-over-year change in average away attendance.

TOTAL_overall_YOY – Year-over-year change in total overall attendance.

AVG_overall_YOY – Year-over-year change in average overall attendance.

AVG_overall_YOY2 – Alternative measure for year-over-year change in average overall attendance (can just ignore this).
