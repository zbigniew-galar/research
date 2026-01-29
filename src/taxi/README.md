#### **Big data processing 10 analysis loop:**
Code 01_10_loop.py is processing Yellow Taxi Trip Records dataset extracting weekly average, median and sum of 5 metrics: passenger_count, total_amount, trip_distance, time, speed with 2nd version for each hour.

**Citation:**

Yellow Taxi Trip Records basic weekly processing. Retrieved January 29, 2026, from https://github.com/zbigniew-galar/research/blob/main/src/taxi/01_10_loop.py

#### **Big data processing 5&6 and 7&8 analysis decile deep dive loop:**
Code 05_08_decile_loop.py is processing Yellow Taxi Trip Records dataset extracting weekly deciles of trip_distance, time with 2nd version for each hour.

**Citation:**

Yellow Taxi Trip Records decile weekly processing. Retrieved January 29, 2026, from https://github.com/zbigniew-galar/research/blob/main/src/taxi/05_08_decile_loop.py

#### **Data cleaning operations:**

| **Analysis ID** | **Metric**      | **Resolution** | **Filters Applied**        |
| --------------- | --------------- | -------------- | -------------------------- |
| **01 / 02**     | Passenger Count | Week / Hour    | $1 <= P <= 5$              |
| **03 / 04**     | Total Amount    | Week / Hour    | $0.01 <= $ <= $1000$       |
| **05 / 06**     | Trip Distance   | Week / Hour    | $0.2 <= D <= 550$ miles    |
| **07 / 08**     | Trip Duration   | Week / Hour    | $1 <= T <= 720 minutes     |
| **09 / 10**     | System Speed    | Week / Hour    | Derived from D & T above   |


- **Analysis 1:** passenger_count sum and passenger_count mean and passenger_count median (3 metrics)
- **Analysis 2:** passenger_count sum and passenger_count mean and passenger_count median per hour (72 metrics)
- **Analysis 3:** total_amount sum and total_amount mean and total_amount median (3 metrics)
- **Analysis 4:** total_amount sum and total_amount mean and total_amount median per hour (72 metrics)
- **Analysis 5:** trip_distance sum and trip_distance mean and trip_distance median (3 metrics)
- **Analysis 6:** trip_distance sum and trip_distance mean and trip_distance median per hour (72 metrics)
- **Analysis 7:** time sum and time mean and time median (3 metrics)
- **Analysis 8:** time sum and time mean and time median per hour (72 metrics)
- **Analysis 9:** speed sum and speed mean and speed median (3 metrics)
- **Analysis 10:** speed sum and speed mean and speed median per hour (72 metrics)

#### **Yellow cab taxi trips source:**

https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

**Scope:** 
Years 2009 - 2026 ~ 1.8 billion records.

**Citation of the data source example:**

New York City Taxi and Limousine Commission. Yellow Taxi Trip Records. Retrieved January 29, 2026, from https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

**Author:**
Zbigniew Galar, PhD University of Lodz Department of Management
zbigniew.galar@wz.uni.lodz.pl
