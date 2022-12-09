## business_indicators_analysis

The project is automatically checked in the SQL simulator. In an independent project of this course, work is carried out with a database that stores information about venture funds and investments in startup companies. This database is based on the Startup Investments dataset published on the popular Kaggle data research competition platform.

## Data:
visits_log_short (server log with information about site visits):
- `User Id` — a unique user ID;
- `Device` — user's device category;
- `Session start` — date and time of the session start;
- `Session End` — date and time of the end of the session;
- `Channel` — ID of the advertising source from which the user came;
- `Region` - the user's country;

orders_log_short (information about orders):
- `User Id` — the unique ID of the user who made the order;
- `Event Dt` — date and time of purchase;
- `Revenue` — revenue;

costs_short (information about marketing costs):
- `Channel` — the identifier of the advertising source;
- `Dt` — date;
- `Costs` — costs for this advertising source on this day.
