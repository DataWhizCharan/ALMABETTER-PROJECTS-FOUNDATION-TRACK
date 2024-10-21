## Airbnb NYC  Exploratory Data Analysis (EDA)

### Project Overview

This project conducts an Exploratory Data Analysis (EDA) on the Airbnb NYC 2019 dataset, which contains information on various Airbnb listings in New York City. The goal is to extract insights into the factors influencing pricing, booking trends, and guest satisfaction, which can help hosts optimize their listings and improve profitability.

### Dataset

The dataset used in this project is **Airbnb NYC 2019**, which contains 48,895 listings from New York City. It includes various attributes such as location, room type, price, availability, and guest reviews. Some key columns in the dataset are:
- **Listing Information**: `id`, `name`, `host_id`, `host_name`
- **Location Details**: `neighbourhood_group`, `neighbourhood`, `latitude`, `longitude`
- **Property Information**: `room_type`, `price`, `minimum_nights`
- **Guest Interaction**: `number_of_reviews`, `last_review`, `reviews_per_month`
- **Host Activity**: `calculated_host_listings_count`, `availability_365`

#### Accessing the Dataset
- The the dataset is already included in this repository.

### Objectives

- Analyze the distribution of Airbnb listings across neighborhoods and boroughs.
- Identify factors affecting pricing, such as location, room type, and minimum stay requirements.
- Explore guest satisfaction trends through review data, including the frequency and quality of reviews.
- Investigate availability and booking trends, focusing on seasonal demand and host activity.

### Key Steps

1. **Data Cleaning**:
   - Handling missing values (e.g., in `last_review`, `reviews_per_month`) and potential outliers in price and availability.
   
2. **Data Exploration**:
   - Exploring listing distributions by neighborhood and borough using visualizations.
   - Analyzing price variations by room type, neighborhood, and listing characteristics.

3. **Review and Sentiment Analysis**:
   - Understanding trends in guest feedback through the number of reviews and the most recent review activity.

4. **Availability Analysis**:
   - Investigating the relationship between availability and pricing, and analyzing how hosts manage multiple listings.

### Results

- **Neighborhood Trends**: Certain boroughs, such as Manhattan and Brooklyn, have a higher concentration of listings, with premium pricing in tourist-heavy areas.
- **Room Type Analysis**: Entire homes/apartments tend to be more expensive than private rooms, with location and availability influencing price.
- **Review Insights**: Properties with frequent, recent reviews typically enjoy higher occupancy, indicating a positive feedback loop between guest satisfaction and bookings.
- **Seasonal Trends**: Listings with higher availability year-round or during peak seasons exhibit distinct pricing strategies.

### Conclusion

This analysis provides actionable insights for Airbnb hosts to optimize pricing strategies, improve guest experiences, and manage availability based on demand trends. The data-driven approach can help hosts make informed decisions to enhance their property listings on Airbnb.
