## User_Behaviour_and_Revenue_Analytics
Real-world business analytics workflow using Python in Google Colab

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
  Understand how users interact with the platform.
  
  <img width="752" height="659" alt="image" src="https://github.com/user-attachments/assets/43b5884d-a0c4-41f5-9f7e-00b8df229bb3" />


  
- # Traffic Source Analysis:
  Identify high-performing acquisition channels.
<img width="521" height="511" alt="image" src="https://github.com/user-attachments/assets/0f9642e4-bb96-4e7a-ad0a-81ae3cc93095" />

  
- # Revenue Over Time:
  Tracks revenue growth and trends
<img width="773" height="559" alt="image" src="https://github.com/user-attachments/assets/e3f9b10b-19d8-4064-8b9b-0c073b4d93cf" />

- # Top Products by Revenue:
  Highlights best performing products
<img width="766" height="671" alt="image" src="https://github.com/user-attachments/assets/f8dbd6bb-8719-4953-b203-478cd11aabcb" />

- # User Behaviour Analysis:
  Analyse engagement levels and activity distribution
  <img width="802" height="610" alt="image" src="https://github.com/user-attachments/assets/0034e500-4dd4-4da0-a38c-ebe4b6c3ff7c" />

- # Conversion Funnel:
  Tracks user journey from interaction to purchase
<img width="743" height="670" alt="image" src="https://github.com/user-attachments/assets/0c4ac3c2-33a7-4325-9c29-418403668e66" />

  ## Key Insights:
  - Most users interacts via top-of-funnel events (Views)
  - Conversion drops significantly at purchase stage
  - Certain traffic sources drive higher revenue quality users
  - Revenue is concentrated amoung top-performing products
 
  ## How to Run the Project:
  1. Clone the repository:

         git clone https://github.com/Revathi-Gangadaran/User_Behaviour_and_Revenue_Analytics.git
     
  2. Open in Google Colab
  3. Upload dataset when prompted
  4. Run all cells

  ## Project Structure:
User_Behaviour_and_Revenue_Analytics/
> data/
>> user_events.xlsx
>> 
> notebooks/
>> User_Behaviour_and_Revenue_Analytics.ipynb
>> 
> Outputs/
>> *.png
>> 
> README.md

## Future Improvements
- Cohort Analysis (Retention tracking)
- Funnel Conversion Rate (%)
- Interactive Dashboard (Power BI)
- Machine Learning for user segmentation

## Contributing
Contributions are welcome. Feel free to fork and improve the project

## Contact
If you'd like to connect or discuss about this project:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/revathi-gangadaran)





