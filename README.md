# Restaurant Sales Performance Dashboard
### Analysis of restaurant sales performance to help the business understand what's working and the areas that need attention
## Tools: Power BI ( DAX, Data Modelling)

## Table of Contents
- [Project Overview](#project-overview)
- [Executive Summary](#executive-summary)
- [Insights](#insights)
- [Recommendations](#recommendations)
- [Limitations](#limitations)


## Project Overview
#### This is a fictional restaurant sales dataset. The dashboard was built to demonstrate real scenarios in a restaurant business operation. In the real world, this analysis will help a restaurant business understand how much money it is making, which dishes customers order most, and where it is losing money due to cancellations. Instead of digging through raw sales records every time a question comes up, the owner or manager can open the dashboard, filter by year or by menu item, and see the full picture in seconds.

#### The dashboard pulls together data from restaurant sales transactions (orders, revenue, profit, order channel, cancellations, and timing), spanning three years of data (2023, 2024, and 2025), with a list of local dishes such as Amala, Jollof Rice, Fried Rice, Beef Suya, Ayamase Sauce, Boiled Rice, and more.

#### The goal was to give the business owner a tool that answers the questions: how are we doing, what's working, and what needs attention.

## Executive Summary

<img width="1108" height="624" alt="Dashboard" src="https://github.com/user-attachments/assets/c30a7566-e03e-45c3-ba96-7d17033283aa" />

#### Over the period covered, the restaurant generated a total revenue of about ₦12.2 thousand from 1,408 orders, with a total profit of about ₦6.1 thousand. That works out to a profit margin of 50.27%, which is healthy for a food business.

#### The average value of each order was about ₦8.68, and the cancellation rate across all orders was very low at 0.71%, meaning the business is not losing many sales to cancelled orders.

#### Looking at month-over-month movement, the business experienced slow growth: revenue growth is 1.5%, orders 1.1%, and profit 1.5% compared to the previous month. There is room to push harder on marketing, upselling, or expanding popular items to accelerate that growth.

## Insights
#### 1. A handful of dishes drive most of the profit. The top 5 highest-profit items are Assorted Meat Pepper Soup, Boiled Rice with Designer Stew, Fried Rice, Ayamase Sauce, and Jollof with Chicken. Assorted Meat Pepper Soup stands out clearly above the rest with a profit of ₦886.65, generating close to double the profit of some of the other top items. This means a small group of star dishes is carrying a large share of the business's profitability.

#### 2. Weekends are the busiest days. Saturday brings in by far the most orders of the week (343), followed by Friday (248). This makes sense for a restaurant, since weekends are days when people eat out or order more food. However, Saturday and Monday also have the highest cancellation rates (close to 2%), while Tuesday has the lowest. While Saturday drives the most sales, it also carries more risk of lost orders.

#### 3. Evening hours around 4 PM to 8 PM are prime time. Order volume is highest at 4 PM (388 orders) and gradually decreases through the evening toward 8 PM (161 orders). This is a useful window for staffing decisions, making sure there are enough hands in the kitchen and enough delivery riders to reduce delays and improve customer experience.
#### 4. Revenue growth has been inconsistent month to month. Looking at the year across January to December, revenue grew steadily in the early months but dipped noticeably around July to September before picking back up toward the end of the year. This kind of dip could be linked to seasonal factors (such as school holidays, weather, or reduced spending during certain periods) and is worth investigating further.

#### 5. Delivery is the dominant order channel. Delivery brings in significantly more orders (1,064 orders) and profit (₦4,526) than in-person collection. This tells us that most customers prefer to order from home or work rather than pick up their food, which has implications for how the business should prioritize its delivery service, riders, and packaging quality.

#### 6. Cancellations are low overall, but not evenly spread. While the total cancellation rate of 0.71% is small, the fact that it is concentrated around Monday and Saturday suggests there may be specific operational issues on those days, for example, order backlogs after a busy Saturday, or slower restocking at the start of the week (Monday).

## Recommendations
- Double down on the top-performing dishes. Since Assorted Meat Pepper Soup, Boiled Rice with Designer Stew, Fried Rice, Ayamase Sauce, and Jollof with Chicken already drive the most profit, consider featuring them more prominently in marketing, ensuring they are never out of stock.
- Strengthen weekend operations. Since Saturday and Friday bring in the most orders, make sure staffing, ingredients, and delivery capacity are all scaled up ahead of the weekend to avoid delays or stockouts that could lead to cancellations.
- Investigate the Monday and Saturday cancellations. A closer look into why cancellations spike on these two days specifically could reveal a fixable operational issue, such as kitchen overload, delivery delays, or payment problems.
- Invest further in delivery. Since delivery drives more orders and profit than walk-in collection, improving delivery speed, packaging, and rider availability could have a bigger impact on revenue than efforts focused on in-store experience alone.
- Plan around the July–September slowdown. Understanding what caused the dip in growth during this period (whether it's seasonal, competition-related, or something internal) can help the business prepare promotions or offers in advance to protect revenue during that stretch.
- Use the 4 PM–8 PM window strategically. Since this is peak ordering time, running time-limited promotions or ensuring the fastest service during these hours could help convert more browsing customers into paying ones.

## Limitations
- Cancellation reasons are not captured. The dashboard shows how many orders were cancelled and when, but not why. Without a reason code attached to each cancellation, we can only guess at the root cause.
- External factors aren't accounted for. Things like weather, holidays, local events, or competitor promotions can affect sales but are not reflected in this data, which can make certain spikes or dips (like the July–September dip) harder to fully explain.
- Data covers a limited set of years (2023–2025). As more years of data are added, trends will become more reliable and seasonal patterns easier to confirm.






