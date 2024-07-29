---
layout: default
---

# Optimizing Fantasy Football Drafts: Insights from My Custom Draft Simulator
I developed a highly optimized Draft Simulator tool for personal analysis. This tool allows me to iterate over thousands of drafts and find optimal teams for different categories. Today, I want to share some interesting results from my simulations for a 12-team, 16-round draft, where I'm drafting from the 4th position.

## The Simulation Setup

My simulator allows input for team count, number of rounds, draft position, and optimization goal. For this analysis, I ran four different optimizations:

1. Highest Total Points (Week 1)
2. Lowest Average Fantasy Footballer's Player Tier
3. Highest Average Fantasy Footballer's Player Upside
4. Highest Average Points Above Replacement (PAR)

Each simulation ran through 100,000 draft scenarios in about 2.3-2.4 seconds.

## Results and Analysis

### 1. Optimized for Total Points (Week 1)

This team prioritizes immediate production in the first week of the season. It produced the highest projected total points (149.15) but had the highest average tier (8.13) and lowest average upside (3.95) and points above replacement (35.23).

Key strategy points:
- Grabbed Derrick Henry (RB) in round 1
- Prioritized TE early with Sam LaPorta in round 2
- Waited until round 8 for a QB (Jared Goff)
- Heavy focus on WRs in later rounds

Drafted players in order:
1. Derrick Henry (RB - BAL)
2. Sam LaPorta (TE - DET)
3. Mike Evans (WR - TB)
4. Joe Mixon (RB - HOU)
5. Amari Cooper (WR - CLE)
6. Jayden Reed (WR - GB)
7. Raheem Mostert (RB - MIA)
8. Jared Goff (QB - DET)
9. Ezekiel Elliott (RB - DAL)
10. Tyler Lockett (WR - SEA)
11. Ricky Pearsall (WR - SF)
12. Brandin Cooks (WR - DAL)
13. Justin Tucker (K - BAL)
14. Roman Wilson (WR - PIT)
15. Malachi Corley (WR - NYJ)

### 2. Optimized for Lowest Average Baller Tier

This strategy focuses on consistent, reliable players across positions. It resulted in the second-highest projected total points (145.36) with a better average tier (7.53), upside (4.88), and PAR (38.96) compared to the total points optimization.

Key strategy points:
- Started with Mike Evans (WR) in round 1
- Balanced approach between WRs and RBs in early rounds
- Waited until round 9 for a QB (Jared Goff)

Drafted players in order:
1. Mike Evans (WR - TB)
2. Derrick Henry (RB - BAL)
3. Amari Cooper (WR - CLE)
4. Joe Mixon (RB - HOU)
5. Keenan Allen (WR - CHI)
6. David Njoku (TE - CLE)
7. Raheem Mostert (RB - MIA)
8. Ezekiel Elliott (RB - DAL)
9. Jared Goff (QB - DET)
10. Tyler Lockett (WR - SEA)
11. Ricky Pearsall (WR - SF)
12. Justin Tucker (K - BAL)
13. Brandin Cooks (WR - DAL)
14. Roman Wilson (WR - PIT)
15. Malachi Corley (WR - NYJ)

### 3. Optimized for Highest Average Baller Upside

This strategy aims for players with the highest potential for breakout performances. It resulted in slightly lower total points (143.28) but achieved the highest average upside (4.9).

Key strategy points:
- Started with Derrick Henry (RB) in round 1
- Balanced approach between WRs and RBs in early rounds
- Latest QB pick (Deshaun Watson in round 12)
- Earliest K pick (Justin Tucker in round 8)

Drafted players in order:
1. Derrick Henry (RB - BAL)
2. Joe Mixon (RB - HOU)
3. Mike Evans (WR - TB)
4. Amari Cooper (WR - CLE)
5. Keenan Allen (WR - CHI)
6. David Njoku (TE - CLE)
7. Raheem Mostert (RB - MIA)
8. Justin Tucker (K - BAL)
9. Ezekiel Elliott (RB - DAL)
10. Tyler Lockett (WR - SEA)
11. Ricky Pearsall (WR - SF)
12. Deshaun Watson (QB - CLE)
13. Brandin Cooks (WR - DAL)
14. Roman Wilson (WR - PIT)
15. Malachi Corley (WR - NYJ)

### 4. Optimized for Highest Average Baller PAR (Points Above Replacement)

This strategy focuses on players who significantly outperform others at their position. It achieved the highest average PAR (40.0) but had the lowest total points (142.71) among all strategies.

Key strategy points:
- Started with two WRs in the first two rounds
- Latest RB pick (Derrick Henry in round 3)
- Mid-round QB (Dak Prescott in round 6)
- Latest TE pick (Ben Sinnott in round 12)

Drafted players in order:
1. Mike Evans (WR - TB)
2. Amari Cooper (WR - CLE)
3. Derrick Henry (RB - BAL)
4. Joe Mixon (RB - HOU)
5. Keenan Allen (WR - CHI)
6. Dak Prescott (QB - DAL)
7. Raheem Mostert (RB - MIA)
8. Ezekiel Elliott (RB - DAL)
9. Justin Tucker (K - BAL)
10. Tyler Lockett (WR - SEA)
11. Ricky Pearsall (WR - SF)
12. Ben Sinnott (TE - WAS)
13. Brandin Cooks (WR - DAL)
14. Roman Wilson (WR - PIT)
15. Malachi Corley (WR - NYJ)

## Key Takeaways

1. **QB Strategy**: There's significant variation in QB draft strategy. The total points and tier optimizations wait until round 8-9 for Jared Goff, the PAR optimization selects Dak Prescott in round 6, while the upside optimization waits until round 12 for Deshaun Watson.

2. **TE Strategy**: The total points optimization prioritizes TE early (Sam LaPorta in round 2), while others select David Njoku in round 6. The PAR optimization waits until round 12 for Ben Sinnott.

3. **First Round Pick**: Two optimizations start with Derrick Henry (RB), while two prefer Mike Evans (WR), showing a split between RB and WR priority.

4. **WR vs RB Balance**: All strategies show a more balanced approach between WRs and RBs in the early rounds compared to traditional draft strategies.

5. **Late Round Consensus**: All simulations agree on several late-round picks: Raheem Mostert (RB) in round 7, Ezekiel Elliott (RB) in round 8-9, Tyler Lockett (WR) in round 10, and Justin Tucker (K) between rounds 8-13. This suggests these players might be undervalued in my league and could be smart late-round targets.

6. **Rookie WRs**: All strategies select multiple rookie WRs in the last few rounds (Ricky Pearsall, Roman Wilson, Malachi Corley), indicating potential value in late-round rookie selections.

## Interesting Note on Team Similarities

Despite different optimization goals, there are fascinating similarities between the teams:

- The core of each team is remarkably similar, with players like Derrick Henry, Joe Mixon, Mike Evans, and Amari Cooper appearing in all four optimizations.
- The main differences lie in the draft order of these core players and the selections for QB and TE positions.
- The upside and tier optimizations produced nearly identical teams, differing only in draft order and QB selection.
- The PAR optimization stands out with its unique early-round WR focus and late TE selection.

These similarities suggest that regardless of the specific optimization goal, certain players offer value across different metrics in my league settings. The differences in draft order and positional prioritization highlight the nuances of each strategy.

## Raw Results Returned from Simulations 

### Optimized for Team Total Points Week 1
```json
{
  "optimizationType": "HighestTotalPoints",
  "optimizationMetric": 149.15,
  "optimizationMetricDescription": "Total Points",
  "numberOfDraftsSimulated": 100000,
  "simulationTimeSeconds": 2.3917294,
  "totalPoints": 149.15,
  "averageTier": 8.133333333333333,
  "averageUpside": 3.953333333333333,
  "averagePointsAboveReplacement": 35.23417777777778,
  "playersDrafted": {
    "RB": [
      {
        "playerId": "3198",
        "fullName": "Derrick Henry",
        "team": "BAL",
        "roundSelected": 1
      },
      {
        "playerId": "4018",
        "fullName": "Joe Mixon",
        "team": "HOU",
        "roundSelected": 4
      },
      {
        "playerId": "2749",
        "fullName": "Raheem Mostert",
        "team": "MIA",
        "roundSelected": 7
      },
      {
        "playerId": "3164",
        "fullName": "Ezekiel Elliott",
        "team": "DAL",
        "roundSelected": 9
      }
    ],
    "TE": [
      {
        "playerId": "10859",
        "fullName": "Sam LaPorta",
        "team": "DET",
        "roundSelected": 2
      }
    ],
    "WR": [
      {
        "playerId": "2216",
        "fullName": "Mike Evans",
        "team": "TB",
        "roundSelected": 3
      },
      {
        "playerId": "2309",
        "fullName": "Amari Cooper",
        "team": "CLE",
        "roundSelected": 5
      },
      {
        "playerId": "10222",
        "fullName": "Jayden Reed",
        "team": "GB",
        "roundSelected": 6
      },
      {
        "playerId": "2374",
        "fullName": "Tyler Lockett",
        "team": "SEA",
        "roundSelected": 10
      },
      {
        "playerId": "11638",
        "fullName": "Ricky Pearsall",
        "team": "SF",
        "roundSelected": 11
      },
      {
        "playerId": "2197",
        "fullName": "Brandin Cooks",
        "team": "DAL",
        "roundSelected": 12
      },
      {
        "playerId": "11630",
        "fullName": "Roman Wilson",
        "team": "PIT",
        "roundSelected": 14
      },
      {
        "playerId": "11617",
        "fullName": "Malachi Corley",
        "team": "NYJ",
        "roundSelected": 15
      }
    ],
    "QB": [
      {
        "playerId": "3163",
        "fullName": "Jared Goff",
        "team": "DET",
        "roundSelected": 8
      }
    ],
    "K": [
      {
        "playerId": "1264",
        "fullName": "Justin Tucker",
        "team": "BAL",
        "roundSelected": 13
      }
    ]
  }
}
```

### Optimized for Lowest Average Fantasy Footballer's Player Tier
```json
{
  "optimizationType": "LowestAverageTier",
  "optimizationMetric": 7.533333333333333,
  "optimizationMetricDescription": "Average Tier",
  "numberOfDraftsSimulated": 100000,
  "simulationTimeSeconds": 2.2963418,
  "totalPoints": 145.36,
  "averageTier": 7.533333333333333,
  "averageUpside": 4.875555555555555,
  "averagePointsAboveReplacement": 38.9564,
  "playersDrafted": {
    "WR": [
      {
        "playerId": "2216",
        "fullName": "Mike Evans",
        "team": "TB",
        "roundSelected": 1
      },
      {
        "playerId": "2309",
        "fullName": "Amari Cooper",
        "team": "CLE",
        "roundSelected": 3
      },
      {
        "playerId": "1479",
        "fullName": "Keenan Allen",
        "team": "CHI",
        "roundSelected": 5
      },
      {
        "playerId": "2374",
        "fullName": "Tyler Lockett",
        "team": "SEA",
        "roundSelected": 10
      },
      {
        "playerId": "11638",
        "fullName": "Ricky Pearsall",
        "team": "SF",
        "roundSelected": 11
      },
      {
        "playerId": "2197",
        "fullName": "Brandin Cooks",
        "team": "DAL",
        "roundSelected": 13
      },
      {
        "playerId": "11630",
        "fullName": "Roman Wilson",
        "team": "PIT",
        "roundSelected": 14
      },
      {
        "playerId": "11617",
        "fullName": "Malachi Corley",
        "team": "NYJ",
        "roundSelected": 15
      }
    ],
    "RB": [
      {
        "playerId": "3198",
        "fullName": "Derrick Henry",
        "team": "BAL",
        "roundSelected": 2
      },
      {
        "playerId": "4018",
        "fullName": "Joe Mixon",
        "team": "HOU",
        "roundSelected": 4
      },
      {
        "playerId": "2749",
        "fullName": "Raheem Mostert",
        "team": "MIA",
        "roundSelected": 7
      },
      {
        "playerId": "3164",
        "fullName": "Ezekiel Elliott",
        "team": "DAL",
        "roundSelected": 8
      }
    ],
    "TE": [
      {
        "playerId": "4033",
        "fullName": "David Njoku",
        "team": "CLE",
        "roundSelected": 6
      }
    ],
    "QB": [
      {
        "playerId": "3163",
        "fullName": "Jared Goff",
        "team": "DET",
        "roundSelected": 9
      }
    ],
    "K": [
      {
        "playerId": "1264",
        "fullName": "Justin Tucker",
        "team": "BAL",
        "roundSelected": 12
      }
    ]
  }
}
```

### Optimized for Highest Average Fantasy Footballer's Player Upside
```json
{
  "optimizationType": "HighestAverageUpside",
  "optimizationMetric": 4.9,
  "optimizationMetricDescription": "Average Upside",
  "numberOfDraftsSimulated": 100000,
  "simulationTimeSeconds": 2.3424109,
  "totalPoints": 143.28,
  "averageTier": 7.533333333333333,
  "averageUpside": 4.9,
  "averagePointsAboveReplacement": 37.71546666666667,
  "playersDrafted": {
    "RB": [
      {
        "playerId": "3198",
        "fullName": "Derrick Henry",
        "team": "BAL",
        "roundSelected": 1
      },
      {
        "playerId": "4018",
        "fullName": "Joe Mixon",
        "team": "HOU",
        "roundSelected": 2
      },
      {
        "playerId": "2749",
        "fullName": "Raheem Mostert",
        "team": "MIA",
        "roundSelected": 7
      },
      {
        "playerId": "3164",
        "fullName": "Ezekiel Elliott",
        "team": "DAL",
        "roundSelected": 9
      }
    ],
    "WR": [
      {
        "playerId": "2216",
        "fullName": "Mike Evans",
        "team": "TB",
        "roundSelected": 3
      },
      {
        "playerId": "2309",
        "fullName": "Amari Cooper",
        "team": "CLE",
        "roundSelected": 4
      },
      {
        "playerId": "1479",
        "fullName": "Keenan Allen",
        "team": "CHI",
        "roundSelected": 5
      },
      {
        "playerId": "2374",
        "fullName": "Tyler Lockett",
        "team": "SEA",
        "roundSelected": 10
      },
      {
        "playerId": "11638",
        "fullName": "Ricky Pearsall",
        "team": "SF",
        "roundSelected": 11
      },
      {
        "playerId": "2197",
        "fullName": "Brandin Cooks",
        "team": "DAL",
        "roundSelected": 13
      },
      {
        "playerId": "11630",
        "fullName": "Roman Wilson",
        "team": "PIT",
        "roundSelected": 14
      },
      {
        "playerId": "11617",
        "fullName": "Malachi Corley",
        "team": "NYJ",
        "roundSelected": 15
      }
    ],
    "TE": [
      {
        "playerId": "4033",
        "fullName": "David Njoku",
        "team": "CLE",
        "roundSelected": 6
      }
    ],
    "K": [
      {
        "playerId": "1264",
        "fullName": "Justin Tucker",
        "team": "BAL",
        "roundSelected": 8
      }
    ],
    "QB": [
      {
        "playerId": "4017",
        "fullName": "Deshaun Watson",
        "team": "CLE",
        "roundSelected": 12
      }
    ]
  }
}
```

### Optimized for Highest Average Player PAR (Points Above Replacement)
```json
{
  "optimizationType": "HighestAveragePointsAboveReplacement",
  "optimizationMetric": 39.99911111111111,
  "optimizationMetricDescription": "Average Points Above Replacement",
  "numberOfDraftsSimulated": 100000,
  "simulationTimeSeconds": 2.3714588,
  "totalPoints": 142.71,
  "averageTier": 7.8,
  "averageUpside": 4.522222222222222,
  "averagePointsAboveReplacement": 39.99911111111111,
  "playersDrafted": {
    "WR": [
      {
        "playerId": "2216",
        "fullName": "Mike Evans",
        "team": "TB",
        "roundSelected": 1
      },
      {
        "playerId": "2309",
        "fullName": "Amari Cooper",
        "team": "CLE",
        "roundSelected": 2
      },
      {
        "playerId": "1479",
        "fullName": "Keenan Allen",
        "team": "CHI",
        "roundSelected": 5
      },
      {
        "playerId": "2374",
        "fullName": "Tyler Lockett",
        "team": "SEA",
        "roundSelected": 10
      },
      {
        "playerId": "11638",
        "fullName": "Ricky Pearsall",
        "team": "SF",
        "roundSelected": 11
      },
      {
        "playerId": "2197",
        "fullName": "Brandin Cooks",
        "team": "DAL",
        "roundSelected": 13
      },
      {
        "playerId": "11630",
        "fullName": "Roman Wilson",
        "team": "PIT",
        "roundSelected": 14
      },
      {
        "playerId": "11617",
        "fullName": "Malachi Corley",
        "team": "NYJ",
        "roundSelected": 15
      }
    ],
    "RB": [
      {
        "playerId": "3198",
        "fullName": "Derrick Henry",
        "team": "BAL",
        "roundSelected": 3
      },
      {
        "playerId": "4018",
        "fullName": "Joe Mixon",
        "team": "HOU",
        "roundSelected": 4
      },
      {
        "playerId": "2749",
        "fullName": "Raheem Mostert",
        "team": "MIA",
        "roundSelected": 7
      },
      {
        "playerId": "3164",
        "fullName": "Ezekiel Elliott",
        "team": "DAL",
        "roundSelected": 8
      }
    ],
    "QB": [
      {
        "playerId": "3294",
        "fullName": "Dak Prescott",
        "team": "DAL",
        "roundSelected": 6
      }
    ],
    "K": [
      {
        "playerId": "1264",
        "fullName": "Justin Tucker",
        "team": "BAL",
        "roundSelected": 9
      }
    ],
    "TE": [
      {
        "playerId": "11596",
        "fullName": "Ben Sinnott",
        "team": "WAS",
        "roundSelected": 12
      }
    ]
  }
}
```