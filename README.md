# Pizza Place Sales Dashboard

## Introduction

The dashboard offers a comprehensive overview of the pizza shop’s revenue performance, transaction frequency, and individual sales. It features an interactive design that allows users to navigate and explore business insights seamlessly. Key functionalities include:

- **Revenue Performance Overview**: Presents a snapshot of overall financial performance and trends.
- **Frequency Analysis**: Displays the frequency of various transactions and events to uncover patterns.
- **Detailed Transaction Data**: Provides in-depth information on each transaction for granular analysis.
- **Interactive Navigation**: Facilitates dynamic exploration of data for more detailed insights.
- **Filters**: Allows users to drill down into specific details by category, date, type, and product.

This intuitive dashboard is designed to help users easily analyze and interpret the shop’s performance metrics for more informed decision-making.

## Data Background

A year's worth of sales from a fictitious pizza place, including the date and time of each order and the pizzas served, with additional details on the type, size, quantity, price, and ingredients.

The data are seperated to 4 tables:

| Table  | Field    | Description |
| ---    | ---      | ---         |
| orders | order_id | Unique identifier for each order placed by a table                             |
| orders | date     | Date the order was placed (entered into the system prior to cooking & serving) |
| orders | time     | Time the order was placed (entered into the system prior to cooking & serving) |
| order_details | order_details_id | Unique identifier for each pizza placed within each order                   |
| order_details | order_id         | Foreign key that ties the details in each order to the order itself         |
| order_details | pizza_id         | Foreign key that ties the pizza ordered to its details, like size and price |
| order_details | quantity         | Quantity ordered for each pizza of the same type and size                   |
| pizzas | pizza_id      | Unique identifier for each pizza                           |
| pizzas | pizza_type_id | Foreign key that ties each pizza to its broader pizza type |
| pizzas | size          | Size of the pizza                                          |
| pizzas | price         | Price of the pizza in USD                                  |
| pizza_types | pizza_type_id | Unique identifier for each pizza type                              |
| pizza_types | name          | Name of the pizza as shown in the menu                             |
| pizza_types | category      | Category that the pizza fall under in the menu                     |
| pizza_types | ingredients   | Comma-delimited ingredients used in the pizza as shown in the menu |

Data Source: **Maven Analytics**

## Dashboard

### About
![About - 1](https://github.com/user-attachments/assets/e3bde96b-e474-45ac-9e68-1b50dc5f205b)
The "About" page offers an overview of the dashboard, including its purpose and the background of the data used. It provides essential information about the dashboard's design and objectives. The design of this page is kept minimal to focus on clarity and ease of understanding.. 


### Overview
![Overview - 2](https://github.com/user-attachments/assets/6cae3317-28ba-4b68-8426-c924026e59bc)
The "Sales Overview" page addresses common questions about business performance, such as monthly revenue, top-selling categories or pizza types, and sales by hour. This page features interactive visuals that enhance the efficiency of in-depth analysis. Additionally, the dashboard includes a "Month" filter, allowing for a more detailed examination of the data.


### Analysis
![Analysis - 3](https://github.com/user-attachments/assets/30011ecd-876f-491a-900b-24356d04ad1a)
The "Analysis" page provides a deeper dive into key metrics, addressing detailed questions such as the frequency of customer visits by hour, the number of items sold by category or pizza type, and seasonal trends. Like the "Sales Overview" page, the "Analysis" page is interactive and includes a "Month" filter to facilitate a more detailed examination of the data.


### Table
![Tables - 4](https://github.com/user-attachments/assets/b4dd8fc2-c343-4d9b-a60c-35c5779c3729)
The "Table" page presents detailed individual transactions for every customer served by the pizza shop. It includes all relevant information necessary for in-depth analysis of each transaction. This page features multiple filters to allow users to easily target and examine specific transactions.


