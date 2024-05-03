# TV’s Golden Age


``` python
import polars as pl

url = "https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2019/2019-01-08/IMDb_Economist_tv_ratings.csv"

pl.read_csv(url)
```

<div><style>
.dataframe > thead > tr,
.dataframe > tbody > tr {
  text-align: right;
  white-space: pre-wrap;
}
</style>
<small>shape: (2_266, 7)</small>

| titleId     | seasonNumber | title        | date         | av_rating | share | genres           |
|-------------|--------------|--------------|--------------|-----------|-------|------------------|
| str         | i64          | str          | str          | f64       | f64   | str              |
| "tt2879552" | 1            | "11.22.63"   | "2016-03-10" | 8.489     | 0.51  | "Drama,Mystery,… |
| "tt3148266" | 1            | "12 Monkeys" | "2015-02-27" | 8.3407    | 0.46  | "Adventure,Dram… |
| "tt3148266" | 2            | "12 Monkeys" | "2016-05-30" | 8.8196    | 0.25  | "Adventure,Dram… |
| "tt3148266" | 3            | "12 Monkeys" | "2017-05-19" | 9.0369    | 0.19  | "Adventure,Dram… |
| "tt3148266" | 4            | "12 Monkeys" | "2018-06-26" | 9.1363    | 0.38  | "Adventure,Dram… |
| …           | …            | …            | …            | …         | …     | …                |
| "tt3250026" | 3            | "Zoo"        | "2017-07-31" | 7.4132    | 0.09  | "Drama,Mystery,… |
| "tt3501584" | 1            | "iZombie"    | "2015-04-28" | 8.4296    | 0.59  | "Comedy,Crime,D… |
| "tt3501584" | 2            | "iZombie"    | "2016-01-07" | 8.5641    | 0.43  | "Comedy,Crime,D… |
| "tt3501584" | 3            | "iZombie"    | "2017-05-16" | 8.4077    | 0.23  | "Comedy,Crime,D… |
| "tt3501584" | 4            | "iZombie"    | "2018-04-13" | 8.1214    | 0.32  | "Comedy,Crime,D… |

</div>
