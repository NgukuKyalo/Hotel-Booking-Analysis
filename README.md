# Hotel Booking Analysis
This project was analyzing guests arrival, bookings, cancelation and duration of stay for travellers, groups and corporate guests for hotels across Portugal for a period of one year.
The following were the project objective
1. To determine the overall cancellation rate
2. To investigate whether hotel type affects cancellation
3. Booking volume and cancellation by month
5. What is the lead time and its association with cancellation
6. Which are the top 10 countries
7. Which type of customer are reliable, and cancel the most

## The overall cancellation Rate

<img width="558" height="374" alt="image" src="https://github.com/user-attachments/assets/a3db2eb2-5cd7-47cd-868d-c5b2b1618fff" />

The overall cancellation rate was 27.6%. This translates to roughly 1 out of 3 bookings being cancelled which is a massive loss to the hotel

## Hotel type and cancellation

<img width="713" height="547" alt="image" src="https://github.com/user-attachments/assets/a3983cb0-f05d-49ab-a404-f0349db1f097" />

City Hotels 
Not Cancelled     69.90%
cancelled         30.09%
Resort Hotels
Not Cancelled     76.29%
Cancelled         23.71%

City Hotels saw a significantly higher booking volumes but also suffered from much higher cancellation compared to Resort Hotels. This can be linked to short trips and accessibility within City Hotels.
Also Resort Hotel being used for vacation stays while City Hotels hosting business meetings.


## Booking volume and cancellation by month

<img width="1014" height="597" alt="image" src="https://github.com/user-attachments/assets/c8dbc8d4-fc1e-4973-af61-3682a3773875" />

Number of booking increased during the summer months with most bookings being done in August. The weather is a contributing factor. While less bookings are observed in winter months.

Recommendation: The hotel should impliment stricter, non-refundable booking rates during summer because they can easily find replacement guests

## Lead Time and its Association with Cancellation

Lead time is the number of days between when a guest books a room and when they actually arrive

<img width="695" height="451" alt="image" src="https://github.com/user-attachments/assets/8eff92a8-bca0-40f4-adf3-fd5e6437b662" />

The box plot shows that the lead time for canceled bookings is much higher.
Basically: the earlier someone books, the more time they have to change their mind , find a better deal or experience a schedule change.

Recommendation: Introduce a progressive deposit system where bookings made more than 90 days in advance, require 20% non-refundable deposits

## Top 10 Countries

<img width="868" height="547" alt="image" src="https://github.com/user-attachments/assets/b58379b4-4b90-452c-8835-2767f0a17390" />

Portugal generate the highest volume of bookings, but it also has the highest rate of cancellation of 50%. Because the hotels in this dataset are based in Portugal, these are local residents.
Locals often book multiple hotels as 'backups' for weekend getaways because the don't have to commit to flights. International guest such as GBR, FRA, DEU, they rarely cancel, due to travel plans are locked in by airline tickets

## Customer Type Analysis

<img width="868" height="547" alt="image" src="https://github.com/user-attachments/assets/094c3c5e-8b0a-4ac8-82b3-9dc2aa76805a" />

Transient travellers (Independent/solo traveller not part of a group) account for the vast majority of the bookings and cancellation. Conversely, 'Groups' and 'Conract' bookings are much more stable.

Recommendation: The sales team should prioritize securing more B2B contracts and group events to build a stable guaranted revenue base that protects against the volatility of individual transients

# Tools Used
Pandas, Matplotlib, Numpy, Seaborn, Visual Studio Code
