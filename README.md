# Cyclistic - Case Study

Analysis of how annual members and casual riders use Cyclistic bikes differently, aiming to support a marketing strategy to convert casual riders into annual members.

## Data

Last 12 months of trip data (August/2025 to July/2026) from the Divvy bike-share system (Chicago), publicly provided by Motivate International Inc: https://divvy-tripdata.s3.amazonaws.com/index.html

The `.csv` files are not included in this repository. To reproduce the analysis, download the files for the desired period from the link above and place them in the `data/tcc/` folder.

## How to run

```bash
pip install -r requirements.txt
jupyter notebook main.ipynb
```

## Notebook structure

- Introduction and business task
- Data cleaning and preparation
- Processing (monthly loop calculating duration, distance, day of week and stations)
- Visualizations
- Analysis summary
- Recommendations

## Key findings

- Members concentrate usage on weekdays, mostly departing from stations in the business district (the Loop); casual riders concentrate usage on weekends, mostly departing from touristic/recreational spots (Navy Pier, the lakefront).
- A portion of members adopt casual-like behavior on weekends, shifting toward touristic stations.
- Both groups prefer electric bikes over classic ones, despite similar distances traveled between the two types — the difference lies in speed, not distance.
- Strong seasonality: usage drops in winter (Dec-Feb) and peaks in summer (Jun-Jul).
