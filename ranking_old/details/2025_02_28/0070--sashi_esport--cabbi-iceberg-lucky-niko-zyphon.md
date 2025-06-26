### Roster Details<br />
Team Name: Sashi Esport<br />
Roster: Cabbi, IceBerg, Lucky, niko, Zyphon<br />
Global Rank: [70](../../standings_global_2025_02_28.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2025_02_28.md)<br />
Regional Rank: [48]( ../../standings_europe_2025_02_28.md)<br />
<br />
Final Rank Value:  943.5<br />
<br />
Final Rank Value (943.5) = Starting Rank Value (1026.6) + Head To Head Adjustments (-83.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.358[<sup>1</sup>](#table2)
- Bounty Collected: 0.398[<sup>2</sup>](#table1)
- Opponent Network: 0.321[<sup>2</sup>](#table1)
- LAN Wins: 0.136[<sup>2</sup>](#table1)

The average of these factors is 0.303<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1026.6
- 400 + ( ( 0.303 - 0.000 ) / ( 0.775 - 0.000 ) ) * 1600 = 1026.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           56 |        4 | 2025-02-28 | Zero Tenacity                             | L   | 1.000      | -            | -                | -                | -         |   -16.68 | Cabbi, IceBerg, Lucky, niko, Zyphon   |
|           55 |       70 | 2025-02-26 | GTZ.ESPORTS                               | L   | 1.000      | -            | -                | -                | -         |   -10.21 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           54 |      109 | 2025-02-25 | Betera Esports                            | L   | 1.000      | -            | -                | -                | -         |   -24.28 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           53 |      148 | 2025-02-24 | Nemiga Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -13.65 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           52 |      243 | 2025-02-20 | 9Pandas                                   | L   | 1.000      | -            | -                | -                | -         |   -13.41 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           51 |      297 | 2025-02-18 | CYBERSHOKE Esports                        | W   | 1.000      | 0.500        | -                | 0.859 (0.429)    | 0 (0.000) |    11.34 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           50 |      336 | 2025-02-16 | Natus Vincere Junior                      | W   | 1.000      | 0.435        | 0.108 (0.047)    | 1.000 (0.435)    | 0 (0.000) |    16.53 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           49 |      367 | 2025-02-15 | SINNERS Esports                           | W   | 1.000      | 0.435        | 0.033 (0.014)    | 0.633 (0.275)    | 0 (0.000) |    14.62 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           48 |      418 | 2025-02-13 | Nemiga Gaming                             | L   | 1.000      | -            | -                | -                | -         |   -12.66 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           47 |      435 | 2025-02-12 | Copenhagen Wolves (American organization) | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | 0 (0.000) |    12.04 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           46 |      484 | 2025-02-10 | RUSH B (Russian team)                     | L   | 1.000      | -            | -                | -                | -         |   -14.88 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           45 |      531 | 2025-02-09 | OG                                        | W   | 1.000      | 0.435        | 0.074 (0.032)    | 0.718 (0.312)    | 0 (0.000) |    16.26 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           44 |      666 | 2025-02-07 | TEAM NEXT LEVEL                           | L   | 1.000      | -            | -                | -                | -         |   -26.57 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           43 |      672 | 2025-02-07 | MoneyF                                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.75 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           42 |      758 | 2025-02-05 | 9INE                                      | W   | 1.000      | 0.435        | 0.044 (0.019)    | 0.747 (0.325)    | 0 (0.000) |    15.20 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           41 |      783 | 2025-02-03 | Monte                                     | L   | 1.000      | -            | -                | -                | -         |   -16.13 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           40 |      807 | 2025-02-02 | B8                                        | L   | 1.000      | -            | -                | -                | -         |    -7.94 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           39 |      939 | 2025-01-24 | Fire Flux Esports                         | L   | 0.965      | -            | -                | -                | -         |   -17.61 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           38 |      969 | 2025-01-23 | 500                                       | W   | 0.960      | 0.500        | 0.111 (0.053)    | 1.000 (0.480)    | 0 (0.000) |    15.79 | Altekz, Cabbi, IceBerg, Lucky, Zyphon |
|           37 |     1520 | 2024-12-15 | Chimera Esports                           | L   | 0.697      | -            | -                | -                | -         |   -12.25 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           36 |     1592 | 2024-12-14 | 9INE                                      | W   | 0.690      | 0.371        | 0.044 (0.011)    | 0.747 (0.191)    | -         |     9.10 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           35 |     1666 | 2024-12-13 | Natus Vincere Junior                      | L   | 0.685      | -            | -                | -                | -         |    -9.19 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           34 |     1756 | 2024-12-11 | Chimera Esports                           | W   | 0.671      | 0.371        | -                | 0.641 (0.159)    | -         |     8.82 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           33 |     1774 | 2024-12-10 | GUN5 Esports                              | L   | 0.667      | -            | -                | -                | -         |   -10.89 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           32 |     1811 | 2024-12-09 | Aurora Gaming                             | L   | 0.660      | -            | -                | -                | -         |   -14.47 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           31 |     1957 | 2024-12-07 | Alliance                                  | W   | 0.644      | -            | -                | -                | -         |     6.91 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           30 |     2123 | 2024-12-03 | 9INE                                      | W   | 0.617      | 0.371        | 0.044 (0.010)    | 0.747 (0.171)    | -         |     7.19 | Altekz, Cabbi, IceBerg, Lucky, MistR  |
|           29 |     2621 | 2024-11-24 | Team Spirit                               | L   | 0.557      | -            | -                | -                | -         |    -0.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           28 |     2727 | 2024-11-22 | Virtus.pro                                | L   | 0.549      | -            | -                | -                | -         |    -0.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           27 |     2808 | 2024-11-21 | Eternal Fire                              | W   | 0.543      | 0.143        | 0.699 (0.054)    | -                | 1 (0.543) |    16.98 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     2856 | 2024-11-21 | Astralis                                  | W   | 0.538      | 0.143        | 0.719 (0.055)    | -                | 1 (0.538) |    16.81 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           25 |     2869 | 2024-11-20 | BIG                                       | L   | 0.537      | -            | -                | -                | -         |    -1.31 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           24 |     3515 | 2024-11-09 | Dynamo Eclot                              | L   | 0.458      | -            | -                | -                | -         |    -4.67 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           23 |     3587 | 2024-11-08 | 500                                       | L   | 0.450      | -            | -                | -                | -         |    -5.83 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           22 |     3624 | 2024-11-07 | Endpoint                                  | W   | 0.445      | -            | -                | -                | -         |     3.54 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3627 | 2024-11-07 | OG                                        | W   | 0.445      | 0.384        | 0.074 (0.013)    | -                | -         |     6.33 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3730 | 2024-11-05 | Rebels Gaming                             | W   | 0.431      | -            | -                | -                | -         |     3.67 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3921 | 2024-11-02 | Wild Lotus                                | L   | 0.412      | -            | -                | -                | -         |    -9.59 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3960 | 2024-11-01 | AMKAL ESPORTS                             | L   | 0.406      | -            | -                | -                | -         |    -9.45 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3965 | 2024-11-01 | Insilio                                   | L   | 0.406      | -            | -                | -                | -         |   -11.41 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3988 | 2024-11-01 | Los kogutos                               | W   | 0.404      | -            | -                | -                | -         |     5.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     4167 | 2024-10-29 | GUN5 Esports                              | L   | 0.384      | -            | -                | -                | -         |    -6.49 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     4407 | 2024-10-24 | Dynamo Eclot                              | W   | 0.352      | -            | -                | -                | -         |     1.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     4711 | 2024-10-17 | 3DMAX                                     | L   | 0.306      | -            | -                | -                | -         |    -0.50 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     4769 | 2024-10-16 | PARIVISION                                | W   | 0.299      | -            | -                | -                | -         |     1.75 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     4841 | 2024-10-15 | HEROIC                                    | L   | 0.292      | -            | -                | -                | -         |    -3.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     5019 | 2024-10-12 | Fire Flux Esports                         | W   | 0.271      | -            | -                | -                | -         |     3.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     6500 | 2024-09-19 | Monte                                     | L   | 0.117      | -            | -                | -                | -         |    -2.57 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     6627 | 2024-09-17 | BC.Game Esports                           | L   | 0.106      | -            | -                | -                | -         |    -1.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     6634 | 2024-09-17 | Wild Lotus                                | L   | 0.105      | -            | -                | -                | -         |    -2.68 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     6645 | 2024-09-17 | BC.Game Esports                           | W   | 0.104      | -            | -                | -                | -         |     1.91 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     6778 | 2024-09-14 | Rebels Gaming                             | L   | 0.086      | -            | -                | -                | -         |    -2.06 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     6808 | 2024-09-14 | OG                                        | W   | 0.085      | -            | -                | -                | -         |     1.01 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     6932 | 2024-09-12 | TSM                                       | W   | 0.072      | -            | -                | -                | -         |     0.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     7051 | 2024-09-10 | GamerLegion                               | W   | 0.057      | -            | -                | -                | -         |     0.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     7546 | 2024-09-03 | Nemiga Gaming                             | L   | 0.011      | -            | -                | -                | -         |    -0.12 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,580.13)
- Divide that value by the 5th highest value among all rosters ($285,971.63)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-17 |      0.710 | $1,000.00      | $710.39         |
| 2024-11-10 |      0.466 | $2,500.00      | $1,165.57       |
| 2024-10-20 |      0.325 | $7,000.00      | $2,275.81       |
| 2024-09-14 |      0.086 | $5,000.00      | $428.36         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
