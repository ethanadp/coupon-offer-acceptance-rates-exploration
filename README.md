# Coupon Offer Acceptance Rates Exploration

## Overview

This project explores which factors influence whether drivers accept digital coupon offers for restaurants, coffee houses, and bars. The dataset consists of responses from a large, diverse group of drivers, covering demographic, behavioral, and situational information for each coupon offer. The goal is to highlight the key differences between those who accept and those who decline various types of coupons.

## Key Findings

### 1. Time of Day Matters
- **Morning and early afternoon** offers have the highest acceptance rates across both coffee house and restaurant coupons.
- **Evening and late-night** offers are less successful, especially for coffee and higher-end restaurant coupons.

### 2. Age and Gender Differences
- **Younger drivers** (especially under 21) are significantly more likely to accept coffee house coupons.
- **Young men under 21** are especially receptive to coffee offers, with much higher acceptance rates than young women.
- For high-value restaurant coupons, **younger and middle-aged adults** (especially those under 30) are more responsive than older drivers.

### 3. Occupation and Income Influence Acceptance
- **Manual, healthcare, and support workers** tend to accept restaurant coupons at much higher rates than other professions.
- **Middle- and high-income individuals** are most likely to accept higher-value restaurant coupons. Acceptance is notably lower in the lowest and some upper-middle income brackets.

### 4. Passenger Context
- **Drivers with adult passengers or friends** are more likely to accept both coffee house and restaurant coupons than those driving with kids or alone.
- The social aspect of a trip appears to make a coupon offer more attractive.

### 5. High-Value Restaurant Coupons: Age & Wealth
- **Wealthy young adults (26 and under)** have the highest acceptance rates for $20–$50 restaurant coupons.
- **Wealthy older adults (50+)** are less likely to accept these offers, possibly due to different dining habits or preferences.

## Visual Summaries

The analysis includes bar plots and heatmaps showing:
- Acceptance rates by time of day, passenger group, age, gender, occupation, and income bracket
- Direct comparisons between coupon types (coffee house vs restaurant)
- Grouped comparisons to highlight key differences in customer response

## Usage

All analysis was performed in Python using pandas, seaborn, and matplotlib. The Jupyter notebook and code can be adapted for similar exploratory data analysis projects on marketing or customer segmentation.

## About the Data

The data comes from a public survey and includes anonymized information on driver demographics, trip context, and coupon offer responses.

## License

This project is open-source and available under the MIT License.

