### Roster Details<br />
Team Name: Immigrants Peek<br />
Roster: bezymecc, H0NeST, myline, nico1ajus, Termina<br />
Global Rank: [283](../../standings_global_2025_02_28.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2025_02_28.md)<br />
Regional Rank: [191]( ../../standings_europe_2025_02_28.md)<br />
<br />
Final Rank Value:  673.6<br />
<br />
Final Rank Value (673.6) = Starting Rank Value (659.5) + Head To Head Adjustments (14.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.266[<sup>1</sup>](#table2)
- Bounty Collected: 0.215[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.126<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 659.5
- 400 + ( ( 0.126 - 0.000 ) / ( 0.775 - 0.000 ) ) * 1600 = 659.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |      402 | 2025-02-13 | BLUEJAYS            | L   | 1.000      | -            | -                | -                | -         |    -6.34 | bezymecc, H0NeST, myline, nico1ajus, Termina    |
|           13 |      472 | 2025-02-10 | Vagrants            | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.547 (0.078)    | 0 (0.000) |    22.36 | bezymecc, H0NeST, myline, nico1ajus, Termina    |
|           12 |      476 | 2025-02-10 | SUPER EVIL GANG     | W   | 1.000      | 0.143        | 0.011 (0.002)    | 0.432 (0.062)    | 0 (0.000) |    19.90 | bezymecc, H0NeST, myline, nico1ajus, Termina    |
|           11 |      508 | 2025-02-09 | Mythic              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.025 (0.004)    | 0 (0.000) |     9.86 | bezymecc, H0NeST, myline, nico1ajus, Termina    |
|           10 |      565 | 2025-02-08 | Vagrants            | L   | 1.000      | -            | -                | -                | -         |    -7.69 | bezymecc, H0NeST, myline, nico1ajus, Termina    |
|            9 |      625 | 2025-02-07 | Chill Guys          | L   | 1.000      | -            | -                | -                | -         |    -6.47 | bezymecc, H0NeST, myline, nico1ajus, sential    |
|            8 |     1621 | 2024-12-13 | MarcaRegistrada     | L   | 0.688      | -            | -                | -                | -         |   -11.52 | bezymecc, H0NeST, marekiew, nico1ajus, Valter0k |
|            7 |     2027 | 2024-12-04 | SUPER EVIL GANG     | L   | 0.629      | -            | -                | -                | -         |    -7.23 | bezymecc, H0NeST, nico1ajus, Termina, Valter0k  |
|            6 |     2073 | 2024-12-03 | MIGHT               | W   | 0.622      | 0.372        | 0.002 (0.000)    | 0.276 (0.064)    | 0 (0.000) |    12.21 | bezymecc, H0NeST, nico1ajus, Termina, Valter0k  |
|            5 |     2143 | 2024-12-02 | Orbital vsat online | W   | 0.615      | 0.372        | 0.000 (0.000)    | 0.030 (0.007)    | 0 (0.000) |     3.94 | bezymecc, H0NeST, nico1ajus, Termina, Valter0k  |
|            4 |     2211 | 2024-12-01 | LOSTHILLS           | W   | 0.609      | 0.372        | 0.000 (0.000)    | 0.029 (0.006)    | 0 (0.000) |     4.02 | bezymecc, H0NeST, nico1ajus, Termina, Valter0k  |
|            3 |     2494 | 2024-11-26 | MCS Gaming          | L   | 0.575      | -            | -                | -                | -         |    -9.11 | bezymecc, H0NeST, nico1ajus, Termina, Valter0k  |
|            2 |     2740 | 2024-11-22 | Make Your Mind      | L   | 0.548      | -            | -                | -                | -         |    -6.92 | bezymecc, H0NeST, nico1ajus, Termina, Valter0k  |
|            1 |     6402 | 2024-09-20 | Kinship             | L   | 0.128      | -            | -                | -                | -         |    -2.94 | bezymecc, H0NeST, nakaznyi, nico1ajus, Rulik    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($491.44)
- Divide that value by the 5th highest value among all rosters ($285,971.63)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.655 | $750.00        | $491.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
