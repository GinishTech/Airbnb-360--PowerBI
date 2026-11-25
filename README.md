# <img width="96" height="96" alt="image" src="https://github.com/user-attachments/assets/9aaacdb8-b445-4130-85c6-73a89b50e3cc" />
Airbnb-360--PowerBI
Power BI dashboard connecting Airbnb app reviews with ABNB stock performance.
# Stock, Guest Sentiment & Hospitality

Power BI dashboard connecting Airbnb app reviews with ABNB stock performance.

## Questions
- What do guests complain about most?
- How has app rating and sentiment changed over time?
- Does guest sentiment move with the stock price?

<img width="800" height="400" alt="all tables" src="https://github.com/user-attachments/assets/bd439525-0779-4c17-914c-db3c7c5af418" />

## Data
- fact_reviews: ~14K app reviews with rating, sentiment score and topic
- fact_daily_reviews: daily avg rating, review count, sentiment
- fact_market: ABNB price, volume, returns, SMA 50/200, 30d volatility
- dim_date: calendar table linking everything

## Dashboard pages
1. Customer Voice

   <img width="664" height="362" alt="Customer Voice" src="https://github.com/user-attachments/assets/5dc70839-7b71-4aae-861e-853d45aa3446" />

3. Market Performance
4. Sentiment vs Stock

## Key findings
- ~75% of reviews are positive, 22% negative
- Top negative themes: Pricing & Fees, Host & Cancellations
- Avg rating 4.02, avg sentiment 0.33

## Tools
Power BI, DAX, Python, Excel/CSV

Built by Ginish Kumar | GinishTech
