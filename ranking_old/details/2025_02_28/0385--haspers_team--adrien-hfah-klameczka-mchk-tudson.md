### Roster Details<br />
Team Name: Haspers Team<br />
Roster: AdrieN, hfah, Klameczka, mchk, tudsoN<br />
Global Rank: [385](../../standings_global_2025_02_28.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2025_02_28.md)<br />
Regional Rank: [247]( ../../standings_europe_2025_02_28.md)<br />
<br />
Final Rank Value:  615.6<br />
<br />
Final Rank Value (615.6) = Starting Rank Value (609.1) + Head To Head Adjustments (6.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.216[<sup>1</sup>](#table2)
- Bounty Collected: 0.187[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.101<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 609.1
- 400 + ( ( 0.101 - 0.000 ) / ( 0.775 - 0.000 ) ) * 1600 = 609.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     4851 | 2024-10-15 | GameAgents       | W   | 0.292      | 0.143        | 0.006 (0.000)    | 0.183 (0.008)    | 0 (0.000) |     6.33 | AdrieN, hfah, Klameczka, mchk, tudsoN    |
|           11 |     4978 | 2024-10-12 | AgenciUSB        | L   | 0.272      | -            | -                | -                | -         |    -5.59 | AdrieN, hfah, Klameczka, mchk, tudsoN    |
|           10 |     5005 | 2024-10-12 | GameAgents       | W   | 0.271      | 0.143        | 0.006 (0.000)    | 0.183 (0.007)    | 0 (0.000) |     6.03 | AdrieN, hfah, Klameczka, mchk, tudsoN    |
|            9 |     5351 | 2024-10-05 | Wolves eSports   | W   | 0.226      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.70 | AdrieN, hfah, Klameczka, mchk, tudsoN    |
|            8 |     6606 | 2024-09-17 | UNiTY esports    | L   | 0.106      | -            | -                | -                | -         |    -0.62 | AdrieN, hfah, Klameczka, Markoś, sk1tt   |
|            7 |     6814 | 2024-09-14 | X-CITY           | L   | 0.084      | -            | -                | -                | -         |    -1.82 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            6 |     6959 | 2024-09-11 | GameAgents       | L   | 0.066      | -            | -                | -                | -         |    -0.64 | AdrieN, hfah, Klameczka, sk1tt, woozzzi  |
|            5 |     6969 | 2024-09-11 | Lan Party Hotel  | W   | 0.066      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     0.68 | AdrieN, hfah, Klameczka, sk1tt, woozzzi  |
|            4 |     7145 | 2024-09-08 | Grannys Knockers | W   | 0.045      | 0.270        | 0.001 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     0.74 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            3 |     7234 | 2024-09-07 | Panica.Gaming    | W   | 0.038      | 0.270        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.28 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            2 |     7250 | 2024-09-07 | Lazer Cats       | L   | 0.037      | -            | -                | -                | -         |    -0.39 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            1 |     7275 | 2024-09-07 | Illuminar Gaming | L   | 0.037      | -            | -                | -                | -         |    -0.19 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($67.05)
- Divide that value by the 5th highest value among all rosters ($285,971.63)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-08 |      0.045 | $1,500.00      | $67.05          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
