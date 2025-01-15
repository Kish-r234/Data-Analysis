# Freshco_Hypermarket_Capstone
Freshco Hypermarket, situated in HSR, Bangalore, has established itself as a prominent supermarket in the region, catering to a wide range of customers. In response to evolving customer needs and to enhance convenience, Freshco introduced a home delivery service in the year 2021. To ensure seamless operations and optimize customer satisfaction, the store diligently maintained a comprehensive transaction data sheet, containing detailed information at the order level.
Business Metrics:
Completion rate: This refers to the rate at which orders are completed (Order successfully delivered / Total order placed).
Customer Lifetime value: It refers to the total revenue generated per customer. Usually this number is defined across various time
period such as 3 month LTV, 6 month LTV or 12 months LTV. However, you don't need to consider specific time period for this business
case. For example, if a person placed 15 olders and paid cumulative 4500 rupees to Freshco, the LTV for the customer is 4500 (excluding discount).
Acquisition month: First month of transaction by the customer. For example, If you have purchased your first order at Amazon on 15th Jan, 2017, then you as a customer, got acquired by Amazon in Jan 2017. For a user, the acquisition month is always going to be same, it doesn't change with subsequent transactions. It's like your birth date, which is always going to be same.
Delivery Area: It refers to the designated drop-off location where a product or package is intended to be delivered. Refer order geo drop column for this.
Slot definition: A time slot is a specific interval when a customer chooses to place an order from a specific store or location. Example of time slots: morning, afternoon, evening, night, and late-night.
Morning: Orders placed between 5am to 12pm
Afternoon: Orders placed between 12pm to 5 pm
Evening: Orders placed between 5pm to 8pm
Night: Orders placed between 8pm to 11pm
Late Night: Orders placed between 11pm to 5am
Customer acquisition source: It is the source from which a customer got acquired to the platform.

Overall delivery time It refer as the time difference between the order placed time and the completion time of the delivery process. It measures the total elapsed time required for the entire delivery process (Order time - completed delivery time)
The overall delivery time can be broken down into following-
Order to Arrival: Order time to Partner Store reach.
Arrival to pickup: Partner Store Reach Time to Partner Start for Delivery Time.
Pickup to Delivery: Partner Start for Delivery Time to Completed/Cancelled Timestamp.

Task to do -

Order level Analysis:
1. Identify order distribution at slot and delivery area level.
2. Identify the areas having highest increase in monthly orders (from Jan to Sep) in absolute orders
3. Calculate delivery charges as a percentage of product amount at slot and month level.
4. Calculate discount as a percentage of product amount at slot and month level.
5. Calculate discount as a percentage of product amount at drop area and slot level.
   
Completion Rate Analysis:
7. Identify Completion rate at slot vs day of the week (Sunday to Saturday) level. Can you spot some pattern in the data?
8. Calculate completion rate at drop area leva.
9. Completion rate at number of products ordered level. For this first you need to create a column having number of product against every order.
10. Give you analysis on the any pattern you observe in the completion rate.

Customer Level Analysis:
11. Identify Completion rate at source level.
12. Calculate LTV for every customer.
13. Calculate aggregated LTV at customer acquisition source level. Refer to aggregated LTV example.
14. Calculate aggregated LTV at acquisition month level. Refer to aggregated LTV example.
15. What is the average Revenue(Product amount after discount) per order at different customer acquisition source level?
16. What is the average Revenue(Product amount after discount) per order at acquisition month level?
17. Is there any pattern in order rating across slots, number of items placed, delivery charges, discount. For example, there might be an insight from the data that orders placed during late night are generally rated high. While orders placed in early morning are not rated high. OR orders having more than 5 items are generally rated high.

Delivery Analysis:
18. Calculate average overall delivery time at month and delivery area level.
19. Calculate average overall delivery time at month and weekday/weekend level. You might need to create a column which will tag every date to either weekday or weekend.
20. Calculate average overall delivery time at slot level. Refer to the definition of slot.
21. Do you see any pattern in delivery charges with slot or delivery area.
22. Do you see any pattern in delivery time and delivery area. If yes then find out logical reason.





