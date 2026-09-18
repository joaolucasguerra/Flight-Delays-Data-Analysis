# Flight-Delays-Data-Analysis
Data analysis of US flight delays from January 2019 using Tableau

# The Domino Effect: Where Flight Delays Begin and How They Spread

This project explores the root causes, propagation, and recovery of flight delays within the U.S. domestic aviation network, using a comprehensive dataset of U.S. flights from January 2019.

## Project Overview

When a flight is delayed, passengers often hope the pilot can simply "make up time in the air." Using a dataset of 583,985 flight records across 346 airports and 17 carriers, our team set out to map the true structural lifecycle of a delay. 

Our analysis investigates where delays originate (time of day vs. volume vs. weather), how a single morning delay can create a "cascade effect" through an aircraft's daily schedule, and whether airborne recovery is actually a viable operational strategy or just an illusion.

## Repository Contents

*   `Project 1 - Joao.twbx`: The Tableau packaged workbook containing the analytical visualizations, including recovery rates by distance, cancellation outliers, and downstream outcomes. *(Note: As a .twbx file, the data extract is already included).*
*   `Flight-Delays Project Presentation.pdf`: The presentation slides detailing our visual journey and findings.

## Data Analysis Approach

To truly understand the delay epidemic, we analyzed the following key metrics and concepts:
*   **Departure Delays:** Flights departing at least 15 minutes after the scheduled time.
*   **Airborne Recovery:** Flights that departed late but managed to arrive on time.
*   **Aircraft-Day (Tail Number Tracking):** Following a specific aircraft throughout its daily schedule to track how early delays infect later flights.
*   **Distance Brackets & Cancellations:** Evaluating how route length impacts recovery odds and how aggressive cancellation policies can mask an airline's true performance.

We examined these metrics to separate volume-based congestion from structural inefficiencies and weather anomalies.

## How to Explore the Data

1.  **View Visualizations:** Open the `.twbx` file using Tableau Desktop or the free Tableau Reader.
2.  **Read the Findings:** View the included `Flight-Delays Project Presentation.pdf` for a high-level executive summary of our insights and recommendations.
3.  **Explore the Article:** Check out our LinkedIn Article for a broader narrative analysis and breakdown of this data.

## Data Source

The dataset used in this project consists of U.S. domestic flight records from January 2019 (`(https://www.kaggle.com/code/hsingc/predicting-flight-delays)`). To avoid skewing the data, airports with fewer than 1,000 monthly flights were excluded from the primary analysis.

## Credits

This project was developed as part of MATH 2327 - Introduction to Data Analysis, taught by Professor Paul Savala at St. Edward's University.

Special thanks to my teammates **Yael Abbo** and **Jacqueline Perales** for their foundational contributions to this analysis, covering the origin of delays and the cascade effect.
