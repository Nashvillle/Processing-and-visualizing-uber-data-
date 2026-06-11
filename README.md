# Processing-and-visualizing-uber-data-
Uber Trip Data Analysis - This project performs Exploratory Data Analysis (EDA) on an Uber trip dataset containing 1,156 rides. The goal is to uncover patterns in trip behaviour, timing, purpose, and distance using Python's data visualisation libraries.
<br><br>
- Dataset <br>
The dataset includes 7 features: trip start and end datetime, category (Business/Personal), start and stop locations, miles travelled, and trip purpose.<br><br><br>
📊 Visualisations & Findings<br>
Category & Purpose — The account is overwhelmingly used for business travel. Meetings and Meal/Entertainment are the most frequent trip purposes, while personal use is minimal.<br>
Day-Night Distribution — Afternoon (34.3%) and Evening (33.1%) are the busiest periods, together accounting for over 67% of all trips. Morning sees the least activity at just 15.2%.<br>
Monthly Trends — Ride volume peaks toward October and November, suggesting busier end-of-year business activity. A significant spike in maximum miles during April points to an extreme long-distance outlier that month.<br>
Trip Duration — Most trips are completed in under 30 minutes, confirming the account is used primarily for short, local journeys. A small number of long-distance trips skew the distribution to the right.<br>
Hour of Day — Trip activity is almost non-existent in the early morning hours. It picks up sharply at 08:00, peaks at 17:00 with 40 trips, and tapers off after 20:00 — a clear 9-to-5 business pattern.<br><br>
- Libraries Used<br>
pandas | matplotlib | seaborn <br><br>
  - Conclusion<br>
This dataset tells the story of a corporate travel account with predictable, work-driven patterns. The analysis provides clear insights into when, why, and how far trips are taken.
