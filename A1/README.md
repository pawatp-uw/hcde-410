# A1 — Working with Open Data

**Dataset:** Burke-Gilman Trail counter north of NE 70th St (bicycle and pedestrian counts)

**Source:** https://data.seattle.gov/Transportation/Burke-Gilman-Trail-north-of-NE-70th-St-Bicycle-and/2z5v-ecg8

**Data file used:** `bg_traffic_bike_ped_2019.csv` (2019 totals for each hour of the day, by direction)

**License / terms of use:**
- Data: Public Domain, published by the City of Seattle (Seattle Open Data)
- Course materials adapted from https://wiki.communitydata.science/Seattle_open_data (cdsw-2020),
  licensed under Creative Commons Attribution-ShareAlike (CC BY-SA)
- Code in this folder: MIT License (see `LICENSE`)

## Questions I asked
- **Q1:** When is the trail busiest and quietest? --> 5pm is busiest (46,997 people in 2019); 2am is quietest (147).
- **Q2:** Do cyclists and pedestrians use the trail at different times? --> Yes: bikes peak at 5pm, pedestrians at 9am.
- **Q3:** Is there evidence of commuting? --> Cyclists show morning (8am) and evening (5pm) rush-hour peaks; pedestrians don't.
- **Q4:** Does direction flip between morning and evening? --> Yes for bikes: 68% northbound in the morning, 64% southbound in the evening.

## How to re-run
Open `A1.ipynb` and run all cells (needs `requests`, `pandas`, `matplotlib`).
The Q1–Q4 analysis reads `bg_traffic_bike_ped_2019.csv`, which must be in the same folder.

## Use of AI
I used Claude to help write the analysis code. I checked the outputs against the CSV and wrote the answers in my own words having Claude double check the spelling and grammar. For more information please check the bottom of A1.ipynb file.
