### Airbnb Data Analysis Dashboard | Power BI

#### Project Overview

This project uses Power BI to analyze Airbnb listing data, focusing on pricing trends, room types, neighbourhood distribution, availability and host performance. The report uses visualizations like KPI cards, bar charts, donut charts, line charts etc to help users quickly understand the structure of the property market and further explore the relationships.



#### Project Objectives

Analyze the distribution of Airbnb listings across different neighbourhood groups.

Compare pricing patterns across different room types and locations.

Explore the relationship between listing prices and review activity.

Evaluate listing availability and booking-related indicators.

Analyze host performance, verification status, and review performance.



#### Data Modeling

FactListings: Main listing data, including price, service fee, availability, and review information.

DimHost: Host information and verification status.

DimLocation: Neighbourhood and geographical information.

DimRoom: Room type classification.

DimPolicy: Cancellation policy information.



#### Dashboard Pages \& Analysis

Page 1 -- Airbnb Overview -- Overall listing distribution and key performance indicators

Key visualizations:

KPI Cards: Key listing performance indicators.

Clustered Column Chart: Distribution of listings by neighbourhood group and room type.

Donut Chart: Proportion of different room types.

Line Chart: Changes in average listing review scores over time.

The listings are primarily concentrated in Manhattan and Brooklyn, consisting mainly of entire homes and private rooms. Despite the high prices, user satisfaction has long remained low—though there have been recent signs of improvement, suggesting an increase in the quality of service provided.



Page 2 -- Prices \& Room Type -- Pricing trends and room type comparisons

Key visualizations:

Clustered Bar Chart: Average nightly price by room type.

Column Chart: Total listings by neighbourhood group and price category.

Scatter Chart: Relationship between listing price and review rate.

Waterfall Chart: Average total price analysis.

Interactive slicers for room type and neighbourhood groups.

Price on this platform is driven more by location than by room type, and neither price nor room type strongly predicts popularity. Hosts in Manhattan and Brooklyn face intense competition.



Page 3 -- Listing \& Neighbourhood -- Geographical distribution and listing availability

Key visualizations:

Map: Geographical distribution of listings by room type.

Treemap: Proportion of total listings by neighbourhood.

Matrix: Available days of different neighbourhood groups and room type.

Funnel Chart: Total listings of neighbourhood groups.

The market is geographically concentrated in a few core areas, with listings consisting primarily of entire homes or individual rooms. In these central areas, hosts face competition, whereas in the surrounding regions, the supply of listings is relatively limited.



Page 4 -- Host Performance -- Host characteristics and review performance

Key visualizations:

Decomposition Tree: Listing distribution by host, room type, and neighbourhood group.

Matrix: Review performance of different hosts.

Gauge Chart: Proportion of annual available days for listings.

Interactive slicers for host identity verification status and cancellation policies.

Verification status does not have a significant impact on listing quality, though listings managed by professional teams tend to perform slightly better. For the platform, identity verification is not a sufficient indicator of listing quality; metrics such as ratings, response speed, and host type may serve as more meaningful points of reference.



#### Key Skills Demonstrated

Data Cleaning \& Transformation

Power Query (ETL)

DAX Measures \& Calculations

Data Modeling

Exploratory Data Analysis (EDA)

Data Visualization

KPI Development \& Performance Analysis



#### Final Conclusion

The Airbnb market in New York is substantial, characterized by a high concentration of listings and a fragmented base of hosts. Manhattan and Brooklyn account for approximately 80% of all listings, the vast majority of which are "entire homes/apartments" or "private rooms." This distribution leads to intense competition in central areas, while peripheral neighborhoods face a shortage of supply. The average price across all listing types is around $600. Notably, neither price nor a host’s verification status serves as a reliable predictor of guest ratings; this suggests that location has a more significant impact on ratings than the specific attributes of the listings themselves. Following a decline prior to 2016, ratings have gradually recovered, with listings managed by professional teams often performing slightly better. Strengthening quality assurance and expanding into surrounding neighborhoods represent the primary opportunities for growth in this market.

