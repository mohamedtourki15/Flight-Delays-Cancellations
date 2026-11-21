# Flight Delays & Cancellations Analysis (Tableau)

**Project Goal:**
Analyze 2015 US domestic flight data to uncover cancellation patterns and communicate insights through interactive Tableau dashboards.

**Dataset:**
2015 US domestic flights operated by large carriers (Kaggle: https://www.kaggle.com/usdot/flight-delays). The raw CSVs are not stored in this repo due to size; the full analysis write-up, including design decisions, is in `Flight_Delays___Cancelation.pdf`.

**Dashboards (Tableau Public):**

1. **Flights Cancellation over USA** - map and bar chart of cancellations by state and day of week.
   - Insight: Texas has the most cancellations on most days; only on Sundays does Illinois overtake it.
   - https://public.tableau.com/app/profile/mohamed1902/viz/FlightsCancellationDashboard_16631860349350/FlightsCancellationOverUSA

2. **Cancellation Causes** - breakdown of cancellation reasons.
   - Insight: Weather is by far the largest cause (47,874 cancellations); Security is the smallest (22).
   - https://public.tableau.com/app/profile/mohamed1902/viz/CancellationCauses1/CancellationCauses

3. **Airlines with Most Cancelled Flights** - cancellations per airline and cause mix per airline.
   - Insight: Southwest Airlines Co. has the most cancellations (almost 16,000). Weather dominates overall, but for some carriers (e.g. Atlantic Southeast Airlines) National Air System issues are the top cause.
   - https://public.tableau.com/app/profile/mohamed1902/viz/Airlineswithmostcancelledflights/Airlineswithmostcancelledflights

**Design Notes:**
- Single-hue sequential color scales to encode cancellation magnitude on the map and bar charts.
- Color-blind-friendly palettes for categorical charts.
- Cancellation cause codes aliased to full names for readability.

**Tools:**
- Tableau Public (dashboard design & publishing)
- 2015 US DOT flight data (Kaggle)
