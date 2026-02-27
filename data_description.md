# Dataset Description

## Overview

The dataset contains Fitbit smart device usage data from 33 participants. It includes daily activity tracking and sleep metrics.

The dataset was used to identify user behavior patterns and generate marketing insights for Bellabeat.

---

## Key Variables

### Activity Metrics
- Total Steps
- Total Distance
- Calories Burned
- Very Active Minutes
- Fairly Active Minutes
- Lightly Active Minutes
- Sedentary Minutes

### Sleep Metrics
- Total Sleep Time
- Time in Bed

### Time Variables
- Activity Date
- Sleep Date

---

## Data Preparation Steps

- Cleaned column names using `janitor`
- Converted date columns using `lubridate`
- Removed duplicate rows
- Checked for missing values
- Aggregated daily activity measures
- Calculated engagement metrics

---

## Analytical Purpose

The dataset was used to:

- Identify user activity patterns
- Segment users by engagement levels
- Examine consistency of behavior
- Translate insights into strategic product and marketing recommendations

---

## Limitations

- Small sample size (33 participants)
- Limited demographic information
- Short time window

Despite these limitations, the dataset provides meaningful insight into behavioral trends and user engagement patterns.