# FLO RFM Analysis
FLO, an online shoe store, wants to divide its customers into segments and create marketing strategies for each segment. To do this, customer behaviors will be defined, and groups will be formed based on these behaviors.

## Features
- master_id: Unique customer identifier
- order_channel: The channel used for shopping (Android, iOS, Desktop, Mobile)
- last_order_channel: The channel used for the most recent order
- first_order_date: The date of the customer's first purchase
- last_order_date: The date of the customer's most recent purchase
- last_order_date_online: The date of the customer's most recent online purchase
- last_order_date_offline: The date of the customer's most recent offline purchase
- order_num_total_ever_online: The total number of orders the customer has placed online
- order_num_total_ever_offline: The total number of orders the customer has placed offline
- customer_value_total_ever_offline: The total amount spent by the customer in offline purchases
- customer_value_total_ever_online: The total amount spent by the customer in online purchases
- interested_in_categories_12: The list of categories the customer has purchased from in the last 12 months

# Action

a. FLO is introducing a new women's shoe brand, and the product prices of this brand are higher than the general customer preferences. Therefore, they want to specifically communicate with customers who match the profile to promote the brand and sell the products. Customers who are loyal (champions, loyal_customers) and those who have previously shopped in the women's category will be the target customers for communication. Save the IDs of these customers in a CSV file.

b. A 40% discount is planned for Men's and Children's products. Customers who have previously been good customers but have not shopped for a while, those who are dormant, and new customers who are interested in these categories will be specially targeted. Save the IDs of the customers who match the appropriate profile in a CSV file.

# Resource
This work is based on the dataset and training provided in the Miuul - CRM Analytics course.
