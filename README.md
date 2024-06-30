# Airbnb NYC Dataset Analysis

This project analyzes the Airbnb listings dataset for New York City. The dataset includes various attributes of listings such as price, location, host information, and booking policies. The goal is to gain insights into the rental market trends and factors influencing pricing and popularity of listings.

## Dataset Description

The dataset used in this project (`airbnb_nyc.csv`) contains the following columns:

- `id`: Listing ID
- `name`: Name of the listing
- `host_id`: ID of the host
- `host_name`: Name of the host
- `host_identity_verified`: Whether the host identity is verified or not
- `neighbourhood_group`: Borough in NYC
- `neighbourhood`: Neighborhood in NYC
- `lat`: Latitude of the listing
- `long`: Longitude of the listing
- `instant_bookable`: Whether instant booking is available
- `cancellation_policy`: Policy for cancellation
- `room_type`: Type of room available
- `construction_year`: Year of construction of the building
- `price`: Nightly price in dollars
- `service_fee`: Additional service fee
- `minimum_nights`: Minimum nights required for booking
- `number_of_reviews`: Number of reviews received
- `last_review`: Date of the last review
- `reviews_per_month`: Average reviews per month
- `review_rate_number`: Rating given by guests
- `calculated_host_listings_count`: Number of listings by the host
- `availability_365`: Number of days the listing is available in a year
- `min_amount`: Derived minimum amount calculation

## Usage

Ensure you have Python with its necessary libraries installed (pandas, numpy, geopy), and Anaconda environment set (for better use). You can clone this repository to run the code using Jupyter Notebook from Anaconda Prompt.

```bash
https://github.com/mammadmammadov/New-York-Airbnb-Data-Analysis.git
cd New-York-Airbnb-Data-Analysis
jupyter notebook
