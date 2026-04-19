## User_Behaviour_and_Revenue_Analytics
Aim of this projects is to simulate a real-world business analytics workflow using Python in Google Colab

## Overview
This project analyzes user events data to uncover actionable insights into:
- User behaviour patterns
- Conversion funnel performance
- Revenue trends
- Product performance

## Dataset Description
The dataset contains two sheets in excel format:
1. user_events Data
  - event_id - Unique event identifier
  - user_id - Unique user identifier
  - event_type - view, cart, info, purchase
  - event_Data - Timestamp of event
  - product_id - Unique product identifier that is associated to products
  - amount - Transaction value
  - traffic_source - Source of user
    
2. products Data
   - product_id - Unique product identifier
   - product_name - Product name
   - series - Series of product
   - sales_price - sales price of each product

## Tech Stack
- Python
- Pandas & Numpy - Data Manipulation
- Matplotlib & Seaborn - Visualization
- Google Colab - Development environment

## Analysis Performed
- # Event Type Distribution :
      Understand how users interact with the platform
  
<img width="752" height="659" alt="image" src="https://github.com/user-attachments/assets/43b5884d-a0c4-41f5-9f7e-00b8df229bb3" />


  
- # Traffic Source Analysis:
      Identify high-performing acquisition channels.
- # Revenue Over Time:
      Tracks revenue growth and trends
- # Top Products by Revenue:
      Highlights best performing products
- # User Behaviour Analysis:
      Analyse engagement levels and activity distribution
- # Conversion Funnel:
      Tracks user journey from interaction to purchase


  ## Key Insights:
  - Most users interacts via top-of-funnel events (Views)
  - Conversion drops significantly at purchase stage
  - Certain traffic sources drive higher revenue quality users
  - Revenue is concentrated amoung top-performing products
  
 






