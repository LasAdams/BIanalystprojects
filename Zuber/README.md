# 🚖 Zuber Ride-Sharing Data Analysis (SQL Project)

This project was conducted as part of my Business Intelligence Analytics training and simulates work as a data analyst for Zuber — a new ride-sharing startup launching in Chicago. The objective was to explore patterns in ride data and assess how external factors like weather influence ride behavior.

---

## 📊 Project Overview

**Client:** Zuber (Chicago-based ride-sharing company)  
**Objective:** Identify ride behavior patterns, passenger preferences, and the impact of weather on trip frequency and duration.

---

## 🧩 Datasets Used

- **`trips`** – Detailed trip-level data including timestamps, locations, and duration
- **`weather_records`** – Hourly weather conditions at the time of each ride
- **`cabs`** – Information about the vehicle and associated company
- **`neighborhoods`** – Names and IDs of Chicago neighborhoods

---

## 🔍 Key Questions Answered

1. **How does weather impact trip durations and ride frequency?**
2. **Are there any observable differences in ride behavior on weekends?**
3. **Which neighborhoods see the most ride activity under different weather conditions?**

---

## 🛠️ SQL Techniques Applied

```sql
SELECT
    start_ts,
    T.weather_conditions,
    duration_seconds
FROM
    trips
INNER JOIN (
    SELECT
        ts,
        CASE
            WHEN description LIKE '%rain%' OR description LIKE '%storm%' THEN 'Bad'
            ELSE 'Good'
        END AS weather_conditions
    FROM
        weather_records
) T ON T.ts = trips.start_ts
WHERE
    pickup_location_id = 50
    AND dropoff_location_id = 63
    AND EXTRACT(DOW FROM trips.start_ts) = 6  -- Saturday
ORDER BY trip_id;
