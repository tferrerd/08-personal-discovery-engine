# Committed dataset

**Source dataset:** goodbooks-10k

**Selection:** Complete ratings.csv and books.csv tables; ratings split into source-order CSV shards without invented rows.

**Data license:** [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). This applies to the data, independently of the project code.

## Sources

- https://github.com/zygmuntz/goodbooks-10k
- https://raw.githubusercontent.com/zygmuntz/goodbooks-10k/master/LICENSE

## CSV files

| File | Rows | Bytes |
|---|---:|---:|
| [book_ratings_001.csv](raw/book_ratings_001.csv) | 2,000,000 | 23,503,126 |
| [book_ratings_002.csv](raw/book_ratings_002.csv) | 2,000,000 | 24,368,411 |
| [book_ratings_003.csv](raw/book_ratings_003.csv) | 1,976,479 | 24,255,335 |
| [books.csv](raw/books.csv) | 10,000 | 3,286,659 |

Attribution: Zygmunt Zając and the goodbooks-10k contributors / Goodreads-derived dataset. Replaces MovieLens because the latter restricts public redistribution. Ratings are published as time-ordered but contain no explicit timestamps, so preserve shard/row order and do not claim calendar-based backtesting. Unrated books are not observed negative preferences.

The CSV files contain published observations or their documented format conversion; no training records were invented. Source formats and raw CSV exports are distinguished by the manifest. File checksums and schemas are recorded in [csv-manifest.json](csv-manifest.json).
