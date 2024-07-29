---
layout: default
---

# Draft Simulations for Optimized Results
I wrote a very efficient Draft Simulator tool for doing some personal analysis.

The simulation iterates over thousands of drafts and finds optimal teams for different categories. You input your team count, rounds, which draft position you are, and what you want to optimize for. 

Here are the results for my 12 team/16 round draft which I am drafted out of the #4 draft slot:

## Optimized for Team Total Points Week 1
```json
{
  "optimizationType": "HighestTotalPoints",
  "optimizationMetric": 113.58,
  "optimizationMetricDescription": "Total Points",
  "numberOfDraftsSimulated": 100000,
  "simulationTimeSeconds": 1.4046905,
  "totalPoints": 113.58,
  "averageTier": 7.1,
  "averageUpside": 4.88,
  "averagePointsAboveReplacement": 51.935933333333345,
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
        "roundSelected": 8
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
        "roundSelected": 10
      }
    ]
  }
}
```

## Optimized for Lowest Average Fantasy Footballer's Player Tier
```json
{
  "optimizationType": "LowestAverageTier",
  "optimizationMetric": 6.1,
  "optimizationMetricDescription": "Average Tier",
  "numberOfDraftsSimulated": 100000,
  "simulationTimeSeconds": 1.5334854,
  "totalPoints": 107.92,
  "averageTier": 6.1,
  "averageUpside": 6.35,
  "averagePointsAboveReplacement": 59.524,
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
        "roundSelected": 8
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
        "playerId": "2374",
        "fullName": "Tyler Lockett",
        "team": "SEA",
        "roundSelected": 9
      }
    ],
    "TE": [
      {
        "playerId": "4033",
        "fullName": "David Njoku",
        "team": "CLE",
        "roundSelected": 5
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
        "roundSelected": 10
      }
    ]
  }
}
```

## Optimized for Jighest Average Fantasy Footballer's Player Upside
```json
{
  "optimizationType": "HighestAverageUpside",
  "optimizationMetric": 6.35,
  "optimizationMetricDescription": "Average Upside",
  "numberOfDraftsSimulated": 100000,
  "simulationTimeSeconds": 1.5461014,
  "totalPoints": 107.91999999999999,
  "averageTier": 6.1,
  "averageUpside": 6.35,
  "averagePointsAboveReplacement": 59.524,
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
        "roundSelected": 5
      },
      {
        "playerId": "2374",
        "fullName": "Tyler Lockett",
        "team": "SEA",
        "roundSelected": 9
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
    "QB": [
      {
        "playerId": "3294",
        "fullName": "Dak Prescott",
        "team": "DAL",
        "roundSelected": 3
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
        "roundSelected": 10
      }
    ]
  }
}
```

## Optimized for Highest Average Fantasy Footballer's Player PAR (Points Above Replacement)
```json
{
  "optimizationType": "HighestAveragePointsAboveReplacement",
  "optimizationMetric": 59.524,
  "optimizationMetricDescription": "Average Points Above Replacement",
  "numberOfDraftsSimulated": 100000,
  "simulationTimeSeconds": 1.5972123,
  "totalPoints": 107.91999999999999,
  "averageTier": 6.1,
  "averageUpside": 6.35,
  "averagePointsAboveReplacement": 59.524,
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
        "roundSelected": 5
      },
      {
        "playerId": "2374",
        "fullName": "Tyler Lockett",
        "team": "SEA",
        "roundSelected": 9
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
    "QB": [
      {
        "playerId": "3294",
        "fullName": "Dak Prescott",
        "team": "DAL",
        "roundSelected": 3
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
        "roundSelected": 10
      }
    ]
  }
}
```