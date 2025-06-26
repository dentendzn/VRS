### Roster Details<br />
Team Name: Flashback Gaming<br />
Roster: clouda, Defaulter, EmbeR, Mcg1LLzZz, reV3nnnn<br />
Global Rank: [142](../../standings_global_2025_02_28.md)<br />
<br />
Region: [Asia]( ../../standings_asia_2025_02_28.md)<br />
Regional Rank: [15]( ../../standings_asia_2025_02_28.md)<br />
<br />
Final Rank Value:  803.4<br />
<br />
Final Rank Value (803.4) = Starting Rank Value (821.6) + Head To Head Adjustments (-18.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.254[<sup>2</sup>](#table1)

The average of these factors is 0.204<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 821.6
- 400 + ( ( 0.204 - 0.000 ) / ( 0.775 - 0.000 ) ) * 1600 = 821.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |        9 | 2025-02-27 | Gods Reign        | L   | 1.000      | -            | -                | -                | -         |   -15.16 | clouda, Defaulter, EmbeR, Mcg1LLzZz, reV3nnnn      |
|           12 |       32 | 2025-02-26 | Big W             | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.078 (0.011)    | 1 (1.000) |    11.23 | clouda, Defaulter, EmbeR, Mcg1LLzZz, reV3nnnn      |
|           11 |      681 | 2025-02-07 | The Huns Esports  | L   | 1.000      | -            | -                | -                | -         |    -9.17 | clouda, Defaulter, EmbeR, Mcg1LLzZz, reV3nnnn      |
|           10 |     1120 | 2024-12-29 | Gods Reign        | L   | 0.793      | -            | -                | -                | -         |   -10.78 | clouda, DiceDealer, EmbeR, PokemoN, reV3nnnn       |
|            9 |     1123 | 2024-12-29 | Victores Sumus    | W   | 0.792      | 0.143        | 0.007 (0.001)    | 0.169 (0.019)    | 0 (0.000) |     7.56 | clouda, DiceDealer, EmbeR, PokemoN, reV3nnnn       |
|            8 |     1867 | 2024-12-08 | Gods Reign        | L   | 0.652      | -            | -                | -                | -         |    -9.68 | clouda, DiceDealer, EmbeR, Mcg1LLzZz, reV3nnnn     |
|            7 |     1940 | 2024-12-07 | WahWah            | W   | 0.646      | 0.270        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.69 | clouda, DiceDealer, EmbeR, Mcg1LLzZz, reV3nnnn     |
|            6 |     2114 | 2024-12-03 | Harizma           | L   | 0.618      | -            | -                | -                | -         |   -10.33 | clouda, Defaulter, EmbeR, Mcg1LLzZz, reV3nnnn      |
|            5 |     2130 | 2024-12-02 | DogEvil           | L   | 0.617      | -            | -                | -                | -         |    -9.74 | clouda, Defaulter, EmbeR, Mcg1LLzZz, reV3nnnn      |
|            4 |     2134 | 2024-12-02 | The Huns Esports  | W   | 0.616      | 0.143        | 0.029 (0.003)    | 0.854 (0.075)    | 0 (0.000) |    13.52 | clouda, Defaulter, EmbeR, Mcg1LLzZz, reV3nnnn      |
|            3 |     2140 | 2024-12-02 | Kadiliman Esports | W   | 0.616      | 0.143        | 0.000 (0.000)    | 0.031 (0.003)    | 0 (0.000) |     1.54 | clouda, Defaulter, EmbeR, Mcg1LLzZz, reV3nnnn      |
|            2 |     3104 | 2024-11-16 | Big W             | W   | 0.510      | 0.143        | 0.006 (0.000)    | 0.078 (0.006)    | 1 (0.510) |     5.54 | clouda, Defaulter, DiceDealer, Mcg1LLzZz, reV3nnnn |
|            1 |     3144 | 2024-11-16 | Victores Sumus    | W   | 0.505      | 0.143        | 0.007 (0.001)    | 0.169 (0.012)    | 1 (0.505) |     5.64 | clouda, Defaulter, DiceDealer, Mcg1LLzZz, reV3nnnn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,962.51)
- Divide that value by the 5th highest value among all rosters ($285,971.63)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-28 |      1.000 | $572.64        | $572.64         |
| 2024-12-29 |      0.793 | $231.42        | $183.43         |
| 2024-11-16 |      0.510 | $2,367.49      | $1,206.43       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
