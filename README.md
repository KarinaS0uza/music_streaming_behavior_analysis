# music_streaming_behavior_analysis
This project explores music streaming data to compare user activity in **Springfield** and **Shelbyville** and weekdays. The analysis was done in Python with pandas using a Jupyter notebook.

## What I did
- Loaded the dataset with pandas
- Inspected the first rows and dataset structure
- Cleaned column names
- Filled missing values in `track`, `artist`, and `genre` with `"unknown"`
- Removed duplicate rows
- Standardized genre labels by replacing `hip`, `hop`, and `hip-hop` with `hiphop`
- Compared song plays by city
- Compared song plays by day of the week, focusing on **Monday**, **Wednesday**, and **Friday**

## Dataset columns
- `user_id`
- `track`
- `artist`
- `genre`
- `city`
- `time`
- `day`

## Key findings
After cleaning, the analysis showed that **Springfield had more total plays than Shelbyville**. I also compared listening activity across Monday, Wednesday, and Friday for both cities.

## Tools used
- Python
- pandas
- Jupyter Notebook
