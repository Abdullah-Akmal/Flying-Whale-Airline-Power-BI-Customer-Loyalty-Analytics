# Flying Whale Airline: Power BI Customer Loyalty Analytics

This Power BI project delivers a comprehensive business intelligence solution for Flying Whale Airline, focusing on customer loyalty, segmentation, and cancellation behavior. The analysis empowers data-driven strategies to improve customer retention, loyalty program performance, and overall customer experience.

## Project Objectives

- Analyze flight activity trends, booking behaviors, and companion travel impact.
- Segment customers by loyalty card tier, demographics, and customer lifetime value (CLV).
- Investigate enrollment and cancellation patterns across various segments.
- Provide actionable recommendations for improving retention and loyalty engagement.

## Data Sources

1. Customer Flight Activity  
   - Fields: Flights Booked, Companion Count, Flight Distance, Loyalty Points.

2. Customer Loyalty History  
   - Fields: Loyalty Card Tier, Enrollment/Cancellation Dates, CLV, Demographics.

## Key Analyses & Visuals

### Flight Activity Analysis

- Monthly & Yearly Booking Trends: Date-sorted line charts.
- Distance vs. Points Correlation: Scatter plot with trend line.
- Companion Impact: Optimal point redemption seen with 5 companions.

### Loyalty Segmentation

- Demographics: Marital status, gender, and education level distribution.
- Loyalty Tier Breakdown: Flights, CLV, and median distance by tier.
- Customer Lifetime Value (CLV): Visual trends by segment.

### Enrollment & Cancellation Trends

- Custom DAX measures to calculate enrollment duration.
- Cancellation patterns by province, tier, and demographics.
- Peak cancellation months identified (December, August, July).

## Insights & Findings

- Star Card Dominance: 58% of customers with highest CLV and flight count.
- Seasonality: July is peak for travel; December–August have high cancellations.
- Demographic Influence: Married males with bachelor's degrees cancel more.
- Companion Travel: Group of 5 drives highest point redemption.
- Geographic Variation: Yukon leads in longest customer loyalty duration.

## Strategic Recommendations

- Personalized Experiences for Star Card holders.
- Demographic-Specific Retention campaigns (e.g., for married men, degree holders).
- Family/Group Packages to boost engagement through companion travel.
- Geographically Targeted benefits and marketing.
- Data-Driven Enhancements using A/B testing and predictive analytics.

## Tools & Technologies

- Power BI Desktop: Data modeling, DAX measures, and report design.
- DAX: Used to compute custom metrics for enrollment duration.
- Excel/CSV: Assumed data format for import and model creation.

## How to Use

1. Open the `.pbix` file in Power BI Desktop.
2. Review the dashboards across the following sections:
   - Flight Activity
   - Loyalty Segmentation
   - Enrollment & Cancellation Trends
3. Use filters and slicers to explore dynamic customer behaviors.

