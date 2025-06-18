# Restaurant Recommendation & Star Rating Analysis

## Project Overview
This project explores and analyses a restaurant dataset using Python and Tableau. It aims to identify key metrics and trends that can help a restaurant consolidator revamp its B2C portal using intelligent automation techniques. The insights generated focus on identifying star restaurants and building a strong foundation for future recommendation systems.

## Problem Statement

A restaurant consolidator is planning to upgrade its B2C platform. To do this, the company wants to:
- Understand current restaurant behaviours.
- Identify top-performing "star" restaurants.
- Determine the feasibility of generating intelligent recommendations.

The solution requires deep analysis of two datasets:
- `data.csv`: Contains detailed restaurant data with 19 attributes.
- `Country-Code.csv`: Maps country codes to country names.

##  Technologies Used
- **Python** (with libraries: pandas, seaborn, math)
- **Jupyter Notebook** for exploratory data analysis (EDA)
- **Tableau** for interactive dashboards and visualization
- Git & GitHub for version control

## Data Understanding & Cleaning
Performed the following preprocessing steps:
- Inspected dataset structure and types
- Handled **missing values** and **duplicates**
- Merged country code data to enrich context
-  Cleaned string e.g. ‘Cuisines’

## Exploratory Data Analysis (EDA)
Key questions explored using Python:
1. **Restaurant Geography**:
   - Identified cities with **maximum** and **minimum** restaurant count.

2. **Franchise Analysis**:
   - Found franchises with the **widest national presence**.

3. **Service Features**:
   - Ratio of restaurants with **table booking** vs. those without.
   - Percentage of restaurants offering **online delivery**.

4. **Votes & Delivery Impact**:
   - Compared number of **votes** between delivering and non-delivering restaurants.	

5. **Cuisine Insights**:
   - Top 10 cuisines served across cities.
   - Max/min number of cuisines per restaurant.
   - Most popular cuisine per city.

6. **Cost & Ratings**:
   - Distribution of **average cost** for two.
   - Relationship between ratings and:
     - Price Range
     - Delivery
     - Booking
     - Cuisine variety
     - Voting

##  Tableau Dashboard
The Tableau dashboard provides a detailed visual overview of restaurant data through various charts and maps to support quick insights and business decisions:
The visual dashboard includes:
- **Tabular Summary**: A detailed table listing key restaurant attributes for a quick glance and filtering.
- **Geographical Overview**: A map showing the location-based distribution of restaurants.
- **Votes vs Rating**: A scatter plot to visualize the relationship between user votes and ratings.
- **Rating vs Price Range**: Bar chart comparing average ratings across different price categories.
- **Rating vs Online Delivery**: Bar chart analysing the impact of online delivery availability on ratings.
- **Rating vs Table Booking**: Bar chart comparing ratings between restaurants that offer or don't offer table booking.
- **Rating vs Number of Cuisines**: Bar chart to explore how the variety of cuisines served affects restaurant ratings.
- **Top 10 Restaurants**: Bar chart highlighting the highest-rated restaurants based on key metrics.
> Link to Tableau Public Dashboard: https://public.tableau.com/app/profile/viijeta.r/viz/Project-RestaurantInsights/Dashboard1?publish=yes

## Key Insights

- Majority of restaurants are concentrated in a few cities.
- Very few franchises have strong international presence.
- Delivery and Table booking has a slight correlation with number of votes.
- Indian cuisine is the most commonly served across cities.
- Higher cost or a greater number of cuisines does not necessarily lead to higher ratings.

## Project Structure

├── data/
│ ├── data.csv
│ ├── Country-Code.csv
├── notebooks/
│ ├── EDA-Restaurant.ipynb ← Python analysis done in Jupyter
├── dashboard/
│ ├── tableau-dashboard.twbx
├── README.md
