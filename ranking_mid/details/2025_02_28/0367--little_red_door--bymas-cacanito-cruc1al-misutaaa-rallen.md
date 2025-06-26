### Roster Details<br />
Team Name: Little Red Door<br />
Roster: Bymas, CacaNito, CRUC1AL, misutaaa, rallen<br />
Global Rank: [367](../../standings_global_2025_02_28.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2025_02_28.md)<br />
Regional Rank: [235]( ../../standings_europe_2025_02_28.md)<br />
<br />
Final Rank Value:  623.8<br />
<br />
Final Rank Value (623.8) = Starting Rank Value (549.4) + Head To Head Adjustments (74.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.262[<sup>2</sup>](#table1)
- Opponent Network: 0.028[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.072<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 549.4
- 400 + ( ( 0.072 - 0.000 ) / ( 0.775 - 0.000 ) ) * 1600 = 549.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |      552 | 2025-02-08 | Zero Tenacity              | L   | 1.000      | -            | -                | -                | -         |    -5.01 | Bymas, CacaNito, CRUC1AL, misutaaa, rallen |
|            4 |      558 | 2025-02-08 | NEVERMORE (Ukrainian team) | L   | 1.000      | -            | -                | -                | -         |    -6.66 | Bymas, CacaNito, CRUC1AL, misutaaa, rallen |
|            3 |      576 | 2025-02-08 | QPT                        | W   | 1.000      | 0.143        | 0.036 (0.005)    | 0.376 (0.054)    | 0 (0.000) |    30.20 | Bymas, CacaNito, CRUC1AL, misutaaa, rallen |
|            2 |      587 | 2025-02-08 | SINNERS Esports            | W   | 1.000      | 0.143        | 0.033 (0.005)    | 0.633 (0.090)    | 0 (0.000) |    28.39 | Bymas, CacaNito, CRUC1AL, misutaaa, rallen |
|            1 |      664 | 2025-02-07 | ALASKA                     | W   | 1.000      | 0.143        | 0.036 (0.005)    | 0.940 (0.134)    | 0 (0.000) |    27.44 | Bymas, CacaNito, CRUC1AL, misutaaa, rallen |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($285,971.63)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
