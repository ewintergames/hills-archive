# How to add hill?
Create file `hills.json` in the directory e.g. `POL/Zakopane/hills.json`
Then add all hills from that place, then add profiles for the hills in that place. 

```json
{
    "place": "Zakopane",
    "hills": [
        {
            "name": "Wielka Krokiew",
            "profiles": [
                {
                    "constructionYear": 1977,
                    "type": 0,
                    "gates": 24,
                    "w": 85.0,
                    "hn": 0.523,
                    "gamma": 35.0,
                    "alpha": 10.0,
                    "e": 79.0,
                    "es": 11.0,
                    "t": 6.0,
                    "r1": 79.0,
                    "betaP": 34.1,
                    "betaK": 33.0,
                    "betaL": 30.4,
                    "s": 2.2,
                    "l1": 3.0,
                    "l2": 9.0,
                    "rL": 208.38,
                    "r2L": 85.0,
                    "r2": 85.0,
                    "a": 100.0,
                    "rA": 0.0,
                    "betaA": 0.0,
                    "b1": 2.0,
                    "b2": 10.0,
                    "bK": 25.0,
                    "bU": 30.0,
                    "d": 0.0,
                    "q": 0.0,
                    "gateStairsLeft": true,
                    "gateStairsRight": true,
                    "inrunStairsLeft": true,
                    "inrunStairsRight": true,
                    "inrunStairsAngle": 0
                },
                {
                    "constructionYear": 2000,
                    ...
                },
                {
                    "constructionYear": 2017,
                   ...
                }
            ]
        },
        {
            "name": "Srednia Krokiew",
            ...
        },
        {
            "name": "Mala Krokiew",
            ...
        }
    ]
}
```
