# Majority Judgment Datasets

Datasets of votes that can be used with Majority Judgment.


## Directory `profiles`

Holds CSV (or other formats?) files with the amounts of judgments per grade and per proposal:

```csv
     , reject, poor, fair, good, very good, excellent
Pizza,      3,    2,    1,    4,         4,        2
Chips,      2,    3,    0,    4,         3,        4
Pasta,      4,    5,    1,    4,         0,        2
```

The first line defining the grades is optional, and grades MUST be ordered from "worst" to "best".


## Directory `ballots`

Holds CSV (or other formats?) files with the judgments per proposal of each judge:

```csv
    Pizza,  Pasta, Chips
excellent,   good,  poor
very good, reject,  poor
        …,      …,     …
```

This data is more complete than just the tallies and should be preferred when available.
