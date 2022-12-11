## Comparison of music preferences in Moscow and St. Petersburg based on Yandex.Music data.
Three hypotheses are to be tested in the project:
* Users activity depends on the day of the week. Moreover, in Moscow and St. Petersburg, this manifests itself in different ways.
* On Monday morning, some genres prevail in Moscow, and others in St. Petersburg. Similarly, on Friday evening, different genres prevail — depending on the city.
* Moscow and St. Petersburg prefer different genres of music. In Moscow, pop music is more often listened to, in St. Petersburg - Russian rap.

Before starting the analysis, it is necessary to check the quality of the data.

## Data:
- `userID` — user id;
- `Track` — track name;
- `artist` — name of an artist;
- `genre` — genre bame;
- `City` — city name;
- `time` — listening start time;
- `Day` — day of a week.

## Resulsts
Hypothesis testing showed:

1. The day of the week has different effects on user activity in Moscow and St. Petersburg.

The first hypothesis was fully confirmed.

2. Musical preferences do not change much during the week — be it Moscow or St. Petersburg. Small differences are noticeable at the beginning of the week, on Mondays:
* in Moscow, they listen to music of the “world” genre,
* in St. Petersburg — "jazz" and "classics".

Thus, the second hypothesis was only partially confirmed. This result could have been different if not for the omissions in the data.

3. There are more similarities than differences in the tastes of Moscow and St. Petersburg users. Contrary to expectations, genre preferences in St. Petersburg resemble those in Moscow.

The third hypothesis was not confirmed. If there are differences in preferences, they are invisible to the majority of users.

## Stage

Project is completed
