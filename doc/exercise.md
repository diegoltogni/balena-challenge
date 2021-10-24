# Balena - Simulation and Modeling Engineer Exercise

## Overview

Hi there future balenista :)
This assignment includes a sample of anonymized production data from our platform.
It is all about the fleets (devices belonging to individual users) and their sizes over time.
Your goal is to freely explore some (possibly unorthodox) angles of how fleets grow and to come up with useful insights, models, or simulations.


## Description of data

The information is provided in the form of two datasets - `fleet_metadata.csv.gz` and `daily_device_counts.csv.gz`.
These are standard CSV files with headers, compressed as `gzip` archives for convenience.

### Description of `fleet_metadata.csv`

In `fleet_metadata.csv` you have some general metadata of fleets such as their predominant device type (`device_type`) as well as the industry they're operating in (`industry`).
This dataset is sorted by `uuid`, which is the unique fleet identifier.

| Field         | Type   | Description             |
|---------------|--------|-------------------------|
| `uuid`        | STRING | Unique identifier       |
| `device_type` | STRING | Predominant device type |
| `industry`    | STRING | Business industry       |

### Description of `daily_device_counts.csv`

In `daily_device_counts.csv` you have the number of active devices (`devices`) observed on a given day (`date`).
This dataset is sorted by `uuid` (same as before) and then by `date`.

| Field     | Type    | Description        |
|-----------|---------|--------------------|
| `uuid`    | STRING  | Unique identifier  |
| `date`    | DATE    | Day of observation |
| `devices` | INTEGER | Number of devices  |


## Tasks

We encourage people at balena to be creative and show their strengths as we believe it creates the most long-term value for the team.

### Task 1 - Assessing the data

Get the initial feeling of data.
Feel free to count, plot, or do whatever you feel needed to explore the datasets.

Is there anything that caught your attention (amount of data, its quality, immediate insights)?

You can enrich the data in any way if needed, e.g. see https://balena.io/pricing to reason about the pricing plans.
You can also explain additional analysis that you would like to do if you had more data and more time.

### Task 2 - Modeling the growth

We'd like you to use the data to come up with useful business insights and explain how the fleets of devices grow.
It can come down to system modeling, regression analysis, time-series exploration, or something else altogether.

Please explain your reasoning along the way:
- Why did you decide to approach the problem like this?
- What assumptions did you make?
- What drawbacks do you see in your approach (if any)?


## Asking questions

Feel free to ask us any questions you have about this exercise.
We'll be more than happy to assist you along the way.

Best of luck!