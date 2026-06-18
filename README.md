# Hotel Booking Analysis
An end-to-end data analysis project oncovering drivers of hotel cancellations and seasonal booking trends

...

## The Table of Contents
*[About the Project](#about-the-project)
*[Business Questions Answered](#Business-questions-answered)
*[Data & Tech Stack](#data-tech-stack)
*[Visual & Key Findings](#Visuals-key-findings)
*[Getting Started](#getting-started)
*[Executive Recommendation](#executive-recommendations)

...

## About the Project
This project acts as a strategic analysis for a simulated hotel chain. Using kaggle "Hotel Booking Demand" dataset (119k+ records), the goal was to identify the root causes of cancellation, map seasonal demand, and discover which customer segments provide the highest lifetime value.
This analysis moves from raw data cleaning and feature engineering to deep exploratory data analysis.

...

# Business Questions Answered

1. What is the overall baseline cancellation rate
2. WHich property tupe, in terms of City Vs Resort, faces the highest volatility.
3. How does booking in advance affect cancellation probability.
4. When are the peak booking seasons and how should pricing reflect this?
5. Which customer demographics, generates the most reliable revenue

...
## Data and Tech Stack
* **Dataset:[Hotel Booking Demand on Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
* **Language: **Python 3
* **Libraries"*`pandas` (Data manipulation and cleaning)
  * `numpy` (numerical computing)
  * `matplotlib & Seaborn` (Data visualization)

....

## Visuals and Key Findings
### 1. The impact of Lead Time on Cancellation
[!Lead Time Analysis](<img width="800" height="500" alt="leadtime" src="https://github.com/user-attachments/assets/2f2dfb27-3a1a-4cbb-81d9-d6dda4404a04" />)
> *Insight* The longer the time between booking and arrival, the higher the chance of cancellation.
Bookings made 90+ days in advance are highly volatile.

## 2. Seasonal Demand (Monthly Trends)
![Seasonal Demand](<img width="1200" height="600" alt="Monthlytrend" src="https://github.com/user-attachments/assets/98f8782c-6186-4aaf-8e93-deb6b3a390d2" />)

> *Insight* July and August are the peak demand months. The hotel has maximum pricing leverage during the European summer holidays.

## 3. Cancellation by Hotel Type
![Hotel Type Comparison](<img width="800" height="600" alt="Hoteltypw" src="https://github.com/user-attachments/assets/9a585af7-6e77-4974-8aea-6fce42c77926" />)

> *Insight* City Hotels experience higher cancellation rate compared to resort Hotels likely due to shorter, easily alterable bisiness trips or weekend getaways.


# Tools Used
Pandas, Matplotlib, Numpy, Seaborn, Visual Studio Code
