# Pizza Sales Data Analysis Project

## Table of Contents
1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Data Source](#data-source)
4. [Key Performance Indicators (KPIs)](#key-performance-indicators-kpis)
5. [Visualizations](#visualizations)
6. [Insights](#insights)
7. [Setup Instructions](#setup-instructions)
8. [Contributing](#contributing)
9. [License](#license)
10. [Contact](#contact)

## Project Overview
This project implements an end-to-end data analysis process using SQL and Power BI to analyze sales data from a pizza business. The goal is to derive key insights from the data by creating various visualizations and calculating essential KPIs. The analysis focuses on trends in orders, sales categorization, and performance metrics for different pizza offerings.

## Technologies Used
- **SQL**: For data extraction and manipulation.
- **Power BI**: For data visualization and analysis.
- **Microsoft Excel**: For initial data cleaning and exploration (if required).
- **Visual Studio Code (or any SQL IDE)**: For writing SQL queries.
- **Data Source**: A hypothetical or sample pizza sales dataset (e.g., CSV format).

## Data Source
The data used for this analysis is sourced from a fictional pizza sales dataset, which contains the following fields:
- Order ID
- Order Date
- Pizza Category
- Pizza Size
- Quantity Sold
- Sales Amount

You can find the sample dataset in the `data` folder of this repository.

## Key Performance Indicators (KPIs)
The following KPIs were calculated as part of the analysis:
1. **Total Revenue**: The sum of the total price of all pizza orders.
2. **Average Order Value**: The average amount spent per order.
3. **Total Pizzas Sold**: The sum of the quantities of all pizzas sold.
4. **Total Orders**: Count of all orders placed in the dataset.
5. **Average Pizzas Per Order**: The average number of pizzas sold per order
6. **Sales Growth**: Percentage change in sales over specified periods.
7. **Top-Selling Pizza**: The pizza with the highest sales volume.
8. **Worst-Selling Pizza**: The pizza with the lowest sales volume.



## Visualizations
Visual representations of the data were created using Power BI, including:
- **Daily Order Trends**: A bar chart illustrating the number of orders placed over a specific time period.
- **Percentage of Sales by Pizza Category**: Created a pie chart that shows the distribution of sales across different pizza categories.
- **Percentage of Sales by Pizza Size**: Generated a pie chart that represents the percentage of sales attributed to different pizza sizes.
- **Total Pizzas Sold by Pizza Category**: Created a funnel chart that presents the total number of pizzas sold for each pizza category.
- **Top 5 Best Sellers by Revenue, Total Quantity and Total Orders**: Created a bar chart highlighting the top 5 best-selling pizzas based on the Revenue, Total Quantity, and Total Orders.
- **Bottom 5 Best Sellers by Revenue, Total Quantity and Total Orders**: Created a bar chart showcasing the bottom 5 worst-selling pizzas based on the Revenue, Total Quantity, and Total Orders.


## Insights
From the data analysis, several key insights can be drawn:
- Trends in order volume and sales can help identify busy periods.
- Performance analysis by category and size informs inventory and marketing strategies.
- The top and worst-selling pizzas can guide menu adjustments and promotional efforts.

## Setup Instructions
To replicate this project, follow these steps:
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/pizza-sales-analysis.git
   cd pizza-sales-analysis
   ```

2. **SQL Setup**:
   - Open your SQL IDE.
   - Import the dataset located in the `data` folder into your SQL environment.
   - Run the provided SQL scripts located in the `sql` folder to extract and manipulate data.

3. **Power BI Setup**:
   - Open Power BI Desktop.
   - Import the processed data from your SQL environment into Power BI.
   - Use the provided Power BI report file located in the `powerbi_reports` folder to visualize the KPIs and trends.

## Contributing
Contributions are welcome! If you have suggestions for improvements or features, please fork the repository and submit a pull request. Ensure that you follow the guidelines set for contributions.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For inquiries or questions, please reach out to:
- **Your Name**: [your.email@example.com]
- **GitHub Profile**: [yourusername](https://github.com/yourusername)

---

Feel free to modify the content as per your project specifics, such as the dataset details, technologies, and contact information.
