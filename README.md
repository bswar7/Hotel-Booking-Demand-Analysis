# Hotel-Booking-Demand-Analysis
City Hotel (Lisbon) vs Resort Hotel (Algarve)



<img width="731" height="379" alt="image" src="https://github.com/user-attachments/assets/f1774202-68e2-4572-a0db-5d51e3dc45d3" />



## Project Overview

This project analyzes 119,390 hotel bookings collected from two real hotels in Portugal:

- A City Hotel located in Lisbon
- A Resort Hotel located in the Algarve region

The dataset, extracted from internal PMS systems between 2015–2017, provides insights into guest behavior, booking patterns, pricing trends, and cancellation drivers.
The goal is to understand what affects cancellations, how booking behavior changes between hotel types, and how hotels can improve pricing, operations, and revenue stability.


## Objectives

#### - Analyze booking behavior
Understand demand trends, customer segments, and pricing patterns.

#### - Compare City and Resort hotels
Evaluate differences in booking volume, revenue, and cancellation behavior.

#### - Identify factors influencing cancellations
Determine what drives customers to cancel their reservations.

#### - Analyze ADR & seasonality trends
See how pricing (ADR) and timing affect customer behavior.


## Target Audience

### - Hotel management teams
### - Revenue & marketing analysts
### - Hospitality / tourism researchers
### - Operations managers & front-office teams

This project supports strategic decisions on pricing, demand planning, staffing, and cancellation policies.


## Dataset Description

### The dataset includes:

* Guest behavior (adults, children, repeated guests)
* Booking details (lead time, stay duration, arrival dates)
* Pricing information (ADR, deposit type)
* Distribution channels
* Reservation status (Canceled / Not canceled)

*Total rows:* 119,390
*Time period:* 2015–2017

### Hotels included:

* City Hotel — Lisbon
* Resort Hotel — Algarve


## Key Findings
### 1) City hotels generate more bookings & revenue
City Hotel revenue: €25.3M
Resort Hotel revenue: €17.4M
<img width="866" height="292" alt="image" src="https://github.com/user-attachments/assets/f3a1ccfe-bde5-469d-990b-eaf20bf28972" />


### 2) City Hotels have a higher cancellation rate
City: 40.4%
Resort: 27%
Unpredictable behavior affects forecasting and planning.
<img width="940" height="268" alt="image" src="https://github.com/user-attachments/assets/6979f3e1-e962-4493-9352-9212861ca79a" />


### 3) ADR peaks in Q3 (summer season)
Note:
2017 shows a drop because dataset stops at Q3, not full-year data.
<img width="958" height="398" alt="image" src="https://github.com/user-attachments/assets/e72eeab0-5d6c-42e9-b516-69beebf77aa5" />


### 4) Longer lead times increase cancellation likelihood
Early bookings = higher risk of cancellation.
<img width="923" height="368" alt="image" src="https://github.com/user-attachments/assets/e845a4d7-b909-4409-8fdd-c55c1a380f41" />


### 5) Families with children form a small segment
Lower family demand in both hotel types.
<img width="722" height="391" alt="image" src="https://github.com/user-attachments/assets/c6bff823-e9a4-470c-bdc8-7c053c0e5a89" />


### 6) Transient guests dominate the market
They form the largest customer group.
<img width="828" height="354" alt="image" src="https://github.com/user-attachments/assets/cbe232a6-f83e-4203-a3ac-16d6dfac5493" />


### 7) Repeated guests = only 3%
Indicates low loyalty and unstable long-term demand.
<img width="920" height="387" alt="image" src="https://github.com/user-attachments/assets/ef5ec198-aea5-46b9-b37b-41453f772635" />


### 8) Non-refundable bookings show extremely high cancellations (99.1%)
<img width="989" height="344" alt="image" src="https://github.com/user-attachments/assets/a8551332-683f-4a21-a2aa-690fffd9d70b" />

Explanation:
OTAs sometimes allow bookings with invalid or unverifiable card details.
Hotels later try to charge → authorization fails → booking gets canceled.
System still tags them as “Non Refund,” causing inflated cancellation rates.

This explanation is based on industry discussions, not a confirmed academic source.


## Recommendations

* Create family-friendly packages
Boost demand from guests with children.

* Strengthen cancellation policies
Incentivize guaranteed bookings to reduce last-minute cancellations.

* Use dynamic pricing
Raise ADR during peak periods; offer bundle deals in off-season.

* Introduce loyalty rewards
Increase repeated guests and revenue stability.

* Clarify deposit rules & validate cards earlier
Reduce fake bookings and invalid non-refundable reservations.


## Tools Used

- Power BI — dashboards and visualizations


## References

1- [Dataset Source]([https://doi.org/10.1016/j.dib.2019.104123](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
Antonio, Almeida & Nunes (2019). Hotel Booking Demand Dataset.
Kaggle.
https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand

2- [Data in Brief Paper (dataset documentation)]([https://doi.org/10.1016/j.dib.2019.104123](https://doi.org/10.1177/1938965519851466)
Antonio, N., de Almeida, A., & Nunes, L. (2019).
Big Data in Hotel Revenue Management: Exploring Cancellation Drivers to Gain Insights Into Booking Cancellation Behavior.
 Cornell Hospitality Quarterly.
https://doi.org/10.1177/1938965519851466




