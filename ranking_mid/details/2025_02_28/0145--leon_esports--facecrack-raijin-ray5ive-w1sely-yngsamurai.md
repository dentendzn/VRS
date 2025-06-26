### Roster Details<br />
Team Name: LEON Esports<br />
Roster: facecrack, Raijin, RaY5ive, w1sely, yngsamurai<br />
Global Rank: [145](../../standings_global_2025_02_28.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2025_02_28.md)<br />
Regional Rank: [102]( ../../standings_europe_2025_02_28.md)<br />
<br />
Final Rank Value:  799.9<br />
<br />
Final Rank Value (799.9) = Starting Rank Value (799.6) + Head To Head Adjustments (0.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.273[<sup>2</sup>](#table1)
- Opponent Network: 0.069[<sup>2</sup>](#table1)
- LAN Wins: 0.087[<sup>2</sup>](#table1)

The average of these factors is 0.193<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 799.6
- 400 + ( ( 0.193 - 0.000 ) / ( 0.775 - 0.000 ) ) * 1600 = 799.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |     1501 | 2024-12-15 | Chimera Esports       | L   | 0.698      | -            | -                | -                | -         |    -5.74 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           27 |     1573 | 2024-12-14 | K27                   | W   | 0.692      | 0.143        | 0.010 (0.001)    | 0.634 (0.063)    | 1 (0.692) |    13.67 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           26 |     1598 | 2024-12-13 | FORZE Reload          | L   | 0.690      | -            | -                | -                | -         |    -7.46 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           25 |     1633 | 2024-12-13 | WOPA Esport           | W   | 0.687      | 0.333        | 0.037 (0.009)    | 0.845 (0.193)    | 0 (0.000) |    12.84 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           24 |     1654 | 2024-12-13 | FORZE Reload          | L   | 0.686      | -            | -                | -                | -         |    -7.11 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           23 |     1847 | 2024-12-08 | PCIFIC Espor          | L   | 0.653      | -            | -                | -                | -         |   -11.38 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           22 |     1991 | 2024-12-06 | Chimera Esports       | L   | 0.639      | -            | -                | -                | -         |    -6.96 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           21 |     2043 | 2024-12-04 | WOPA Esport           | W   | 0.627      | 0.333        | 0.037 (0.008)    | 0.845 (0.176)    | 0 (0.000) |    10.97 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           20 |     2176 | 2024-12-02 | SINNERS Academy       | W   | 0.612      | 0.333        | 0.001 (0.000)    | 0.111 (0.023)    | 0 (0.000) |     8.46 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           19 |     2346 | 2024-11-30 | Ex-eClub Brugge       | W   | 0.599      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.32 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           18 |     2444 | 2024-11-28 | VP.Prodigy            | W   | 0.586      | 0.333        | 0.000 (0.000)    | 0.130 (0.025)    | 0 (0.000) |     4.50 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           17 |     2661 | 2024-11-23 | FLuffy Gangsters      | L   | 0.553      | -            | -                | -                | -         |    -6.94 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           16 |     2716 | 2024-11-23 | FLuffy Gangsters      | W   | 0.550      | 0.143        | 0.017 (0.001)    | 1.000 (0.079)    | 0 (0.000) |    10.70 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           15 |     3060 | 2024-11-17 | XP Academy            | W   | 0.512      | 0.143        | -                | 0.220 (0.016)    | 0 (0.000) |     4.52 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           14 |     3073 | 2024-11-17 | RUSH B (Russian team) | W   | 0.511      | 0.143        | 0.033 (0.002)    | 0.935 (0.068)    | 0 (0.000) |    11.92 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           13 |     3090 | 2024-11-17 | INDINDA               | L   | 0.510      | -            | -                | -                | -         |   -12.83 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           12 |     4037 | 2024-10-31 | ARCRED                | L   | 0.398      | -            | -                | -                | -         |    -5.43 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           11 |     4430 | 2024-10-23 | QUAZAR                | L   | 0.346      | -            | -                | -                | -         |    -6.13 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|           10 |     4548 | 2024-10-20 | ENJOY (Russian team)  | L   | 0.326      | -            | -                | -                | -         |    -8.60 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            9 |     4588 | 2024-10-20 | ПuBo3aBpbI            | W   | 0.324      | -            | -                | -                | 0 (0.000) |     1.03 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            8 |     4591 | 2024-10-20 | Donstu Esports        | W   | 0.324      | -            | -                | -                | -         |     1.64 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            7 |     4982 | 2024-10-12 | NOTTODAY              | L   | 0.272      | -            | -                | -                | -         |    -6.25 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            6 |     4995 | 2024-10-12 | Nuclear TigeRES       | W   | 0.271      | 0.215        | 0.005 (0.000)    | 0.531 (0.031)    | -         |     4.97 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            5 |     5007 | 2024-10-12 | Dragon Esports Club   | W   | 0.271      | 0.215        | 0.008 (0.000)    | 0.336 (0.020)    | -         |     3.21 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            4 |     5689 | 2024-09-30 | Ex-ESC Gaming         | L   | 0.193      | -            | -                | -                | -         |    -4.11 | facecrack, Raijin, RaY5ive, w1sely, yngsamurai |
|            3 |     6810 | 2024-09-14 | EC BANGA              | L   | 0.084      | -            | -                | -                | -         |    -2.24 | Chill, facecrack, Raijin, w1sely, znxxX        |
|            2 |     7442 | 2024-09-04 | Devils.one            | L   | 0.019      | -            | -                | -                | -         |    -0.42 | eightz, facecrack, JIaYm, Raijin, w1sely       |
|            1 |     7457 | 2024-09-04 | T0X1CandCR1T1C        | W   | 0.019      | -            | -                | -                | -         |     0.06 | eightz, facecrack, JIaYm, Raijin, w1sely       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,533.58)
- Divide that value by the 5th highest value among all rosters ($285,971.63)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.699 | $1,936.87      | $1,353.97       |
| 2024-12-15 |      0.698 | $2,200.00      | $1,536.59       |
| 2024-11-03 |      0.420 | $1,532.61      | $643.02         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
