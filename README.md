# Elite Hotels International: Booking Demand and Revenue Diagnostics

Data-Driven Insights Across 119,000+ Reservations to Mitigate Cancellations, Optimize ADR, and Enhance Guest Satisfaction.

---

## Executive Diagnostics and Overview
An empirical analysis of hotel booking patterns, lead time sensitivity, market segment yield, and overbooking strategies across 119,390 reservations between 2015 and 2017.

### Key Performance Benchmarks
- Total Analyzed Reservations: 119,390 records
- Total Cancelled Bookings: 44,224 reservations
- Overall Cancellation Rate: 37.0%
- Potential RevPAR Loss: Late cancellations and empty room capacity reduce potential RevPAR by up to 18% during peak season.

---

## Dataset and Analytics Scope
- Property Scope: City Hotel (79,330 bookings / 66.4% share) and Resort Hotel (40,060 bookings / 33.6% share).
- Lead Time Window: Booking horizons ranging from 0 to 737 days ahead of arrival.
- Financial Metrics: Average Daily Rate (ADR), non-refundable deposits, market distribution channels, and parking demand.

---

## Operational Findings and Cancellation Drivers

### 1. Property Type Dynamics
- City Hotel: Experiences a 41.7% cancellation rate, driven by transient business travelers, short stay lengths (avg 3.0 nights), and OTA rate comparison.
- Resort Hotel: Maintains a lower 27.8% cancellation rate, characterized by longer family vacation stays (avg 4.3 nights) and higher commitment.

### 2. Lead Time Sensitivity
- Very Long Lead (> 180 Days): Suffers a 55.8% cancellation rate, almost 3x higher than short-lead bookings (< 30 days @ 20.1%).
- Unrestricted reservation policies allow guests to hold speculative rooms with zero deposit penalties.

### 3. Distribution Channels and Guest Commitment Signals
- Direct Bookings: Yield a 15.4% cancellation rate, compared to 41.1% on Online Travel Agencies (OTAs) and 61.1% on Group bookings.
- Guests requesting dedicated parking spaces exhibit an almost 0% cancellation rate (1.2%).
- Guests submitting 2 or more special requests have 65% lower cancellation probability.

---

## Market Segment Performance Matrix

| Market Segment | Avg Lead Time | Avg ADR | Cancellation Rate | Strategic Value |
| :--- | :--- | :--- | :--- | :--- |
| Direct Bookings | 47 Days | 106.50 EUR | 15.4% | Highest Profit Margin |
| Corporate Channel | 26 Days | 86.40 EUR | 18.7% | High Reliability |
| Online TA (OTAs) | 84 Days | 116.30 EUR | 41.1% | High Volume / Volatile |
| Offline TA / Tour Ops | 137 Days | 87.20 EUR | 34.3% | Base Capacity Block |
| Groups | 185 Days | 79.80 EUR | 61.1% | High Revenue Risk |

---

## Strategic Optimization Roadmap

- Q1 - Dynamic Overbooking: Deploy machine-learning models predicting daily cancellation probabilities by segment to resell capacity safely.
- Q2 - Direct Booking Push: Launch best-rate guarantees, complimentary breakfast, and free parking to migrate guests from OTAs.
- Q3 - Tiered Deposit Policy: Enforce 20% non-refundable deposits for bookings made more than 90 days in advance.
- Q4 - Pre-Arrival Engagement: Automate pre-arrival guest itineraries 7 days prior to check-in to confirm arrival intent and drive ancillary spend.

---

## Repository Structure
```text
├── data/
│   └── hotel_bookings_dataset.csv
├── working_files/
│   └── Elite_Hotels_Booking_Working_File.xlsx
├── screenshots/
│   └── elite_hotels_booking_dashboard_clean.png
├── presentation/
│   └── Elite Hotels International Booking Analytics.pptx
└── README.md
