# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html),
and is generated by [Changie](https://github.com/miniscruff/changie).

## dbt-snowflake-monitoring 1.2.2 - December 05, 2022

### Fixes

- Show only complete days in daily_spend and materialize as table ([#34](https://github.com/get-select/dbt-snowflake-monitoring/pull/34))



## dbt-snowflake-monitoring 1.2.1 - December 04, 2022

### Fixes

- Fix account_locator var ([#33](https://github.com/get-select/dbt-snowflake-monitoring/pull/33))



## dbt-snowflake-monitoring 1.2.0 - November 26, 2022

### Features

- Add get_query_comment macro for model metadata in query history ([#29](https://github.com/get-select/dbt-snowflake-monitoring/pull/29))
- Support overage usage type for PAYG accounts ([#24](https://github.com/get-select/dbt-snowflake-monitoring/pull/24))

### Fixes

- Division by zero in cost_per_query model ([#27](https://github.com/get-select/dbt-snowflake-monitoring/pull/27))

### Contributors
- [@aphethean1](https://github.com/aphethean1) (Features, Fixes)


## dbt-snowflake-monitoring 1.1.0 - October 28, 2022

### Features

- Add daily_spend model which aligns with monthly bill ([#13](https://github.com/get-select/dbt-snowflake-monitoring/pull/13))


## dbt-snowflake-monitoring 1.0.0 - October 17, 2022

### Features

- Add query_history_enriched model with additional dimensions and cost ([#12](https://github.com/get-select/dbt-snowflake-monitoring/pull/12))
- Add cost per query model ([#1](https://github.com/get-select/dbt-snowflake-monitoring/pull/1))


