### Roster Details<br />
Team Name: ATOX Esports<br />
Roster: flyNN, kabal, MiQ, nuka, yAmi<br />
Global Rank: [192](../../standings_global_2025_02_28.md)<br />
<br />
Region: [Asia]( ../../standings_asia_2025_02_28.md)<br />
Regional Rank: [21]( ../../standings_asia_2025_02_28.md)<br />
<br />
Final Rank Value:  743.9<br />
<br />
Final Rank Value (743.9) = Starting Rank Value (740.6) + Head To Head Adjustments (3.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.333[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.075[<sup>2</sup>](#table1)

The average of these factors is 0.165<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 740.6
- 400 + ( ( 0.165 - 0.000 ) / ( 0.775 - 0.000 ) ) * 1600 = 740.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     3870 | 2024-11-02 | Lynn Vision Gaming      | L   | 0.416      | -            | -                | -                | -         |    -4.17 | flyNN, kabal, MiQ, nuka, yAmi   |
|           13 |     3929 | 2024-11-02 | TYLOO                   | L   | 0.411      | -            | -                | -                | -         |    -4.35 | flyNN, kabal, MiQ, nuka, yAmi   |
|           12 |     4692 | 2024-10-17 | Chinggis Warriors       | L   | 0.309      | -            | -                | -                | -         |    -2.26 | cool4st, kabal, MiQ, sk0R, yAmi |
|           11 |     4738 | 2024-10-17 | Clutch Gaming           | W   | 0.303      | 0.333        | 0.000 (0.000)    | 0.060 (0.006)    | 1 (0.303) |     2.55 | cool4st, kabal, MiQ, sk0R, yAmi |
|           10 |     4793 | 2024-10-16 | Lynn Vision Gaming      | W   | 0.298      | 0.417        | 0.020 (0.003)    | 0.445 (0.055)    | 0 (0.000) |     6.31 | flyNN, kabal, MiQ, nuka, yAmi   |
|            9 |     4804 | 2024-10-16 | Chinggis Warriors       | L   | 0.297      | -            | -                | -                | -         |    -2.15 | cool4st, kabal, MiQ, sk0R, yAmi |
|            8 |     4857 | 2024-10-15 | Chinggis Warriors       | W   | 0.291      | 0.417        | 0.019 (0.002)    | 0.753 (0.091)    | 0 (0.000) |     7.17 | flyNN, kabal, MiQ, nuka, yAmi   |
|            7 |     4869 | 2024-10-14 | The QUBE Esports        | W   | 0.289      | 0.333        | 0.000 (0.000)    | 0.178 (0.017)    | 1 (0.289) |     3.68 | cool4st, kabal, MiQ, sk0R, yAmi |
|            6 |     5710 | 2024-09-30 | Nomads (Mongolian team) | L   | 0.191      | -            | -                | -                | -         |    -2.99 | flyNN, kabal, MiQ, nuka, yAmi   |
|            5 |     5713 | 2024-09-30 | Nomads (Mongolian team) | L   | 0.191      | -            | -                | -                | -         |    -3.04 | flyNN, kabal, MiQ, nuka, yAmi   |
|            4 |     5848 | 2024-09-28 | The Huns Esports        | L   | 0.178      | -            | -                | -                | -         |    -0.70 | flyNN, kabal, MiQ, nuka, yAmi   |
|            3 |     5851 | 2024-09-28 | The Huns Esports        | L   | 0.178      | -            | -                | -                | -         |    -0.71 | flyNN, kabal, MiQ, nuka, yAmi   |
|            2 |     6183 | 2024-09-24 | The QUBE Esports        | W   | 0.151      | 0.417        | 0.000 (0.000)    | 0.178 (0.011)    | 0 (0.000) |     1.98 | flyNN, kabal, MiQ, nuka, yAmi   |
|            1 |     6190 | 2024-09-24 | The QUBE Esports        | W   | 0.151      | 0.417        | 0.000 (0.000)    | 0.178 (0.011)    | 0 (0.000) |     2.00 | flyNN, kabal, MiQ, nuka, yAmi   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,858.28)
- Divide that value by the 5th highest value among all rosters ($285,971.63)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-03 |      0.417 | $5,000.00      | $2,085.07       |
| 2024-10-17 |      0.309 | $2,500.00      | $773.21         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
