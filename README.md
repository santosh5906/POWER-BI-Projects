# Supply Chain and Freight Analytics BI Projects

## Project Overview

This project aims to develop a comprehensive and user-friendly dashboard for a local transportation company to provide a clear and insightful overview of its financial performance. The dashboard visualizes key financial metrics and trends to help management make data-driven decisions and monitor the company's financial health. The core objective is to present crucial Key Performance Indicators (KPIs) and data points in a simple yet effective way to facilitate better understanding and management of company operations.

## Data Overview

The dataset consists of 28 columns and records for over a year, capturing key financial transactions and operational data related to the transportation company's expenses, income, and other metrics. The data covers multiple financial categories, including expenses associated with goods supply and freight costs.

### Key Columns:
- **Insurance Cost**: The amount spent on insurance policies.
- **Fuel**: Fuel expenditures for vehicle operations.
- **Diesel Exhaust Fluid**: Costs related to the purchase of DEF for vehicles.
- **Freight Expenses**: Various transportation-related costs including fuel, repairs, and warehousing.
- **Warehouse**: Storage and warehousing expenses.
- **Tolls**: Tolls paid during the transportation of goods.
- **Income**: Revenue generated by the transportation services.
- **Driver Payroll**: Salaries paid to the drivers each month.
- **Odometer**: Total distance covered by all vehicles.
- **Extra Stops**: Additional costs incurred for extra stops during deliveries.

## KPIs and Metrics

The dashboard primarily focuses on the following Key Performance Indicators (KPIs):

1. **Income**: 
   - Total income over a specific period (sum of income for the months).
   - This metric reflects the overall revenue the company generates from transportation services.

2. **% Income**: 
   - Formula: `Income / (Income + Expenses)`
   - This metric provides the proportion of income relative to the total of both income and expenses, helping to assess the company's profitability.

3. **Expense**: 
   - Total expenses over a specific period (sum of all expenses such as fuel, insurance, repairs, etc.).
   - This metric reflects the total operational cost incurred by the company during the period.

4. **% Expenses**: 
   - Formula: `Expenses / (Income + Expenses)`
   - This metric represents the proportion of expenses relative to the total of both income and expenses, helping to evaluate cost efficiency.

5. **Monthly Balance**: 
   - Formula: `Monthly Income - Monthly Expense`
   - This metric shows the net balance for each month, helping to track whether the company is in profit or loss during any given month.

6. **Income vs Expenses Comparison**: 
   - A line chart or bar graph comparing monthly income with monthly expenses.
   - This provides an easy-to-understand visual of the financial performance over time.

7. **Graphical Representation of Shipments to Different Provinces**: 
   - A map or bar chart visualizing the volume or value of shipments delivered to different provinces.
   - Helps in understanding the distribution of company services and performance across regions.

8. **Driver Payroll**: 
   - Total salary paid to drivers for a particular month.
   - Helps to monitor payroll expenditure and track how it varies month by month.

9. **Odometer**: 
   - The total distance covered by all vehicles for a particular month.
   - Helps track vehicle usage and can correlate with fuel costs and maintenance.

10. **Extra Stops**: 
   - Total money spent on making extra stops during a given month.
   - It highlights any additional costs incurred outside the standard delivery route.

## Features of the Dashboard

The dashboard includes several key features designed to provide insights and aid in decision-making:

- **Dynamic Graphs and Charts**: Interactive line charts, bar graphs, and pie charts that allow the user to explore and drill down into the data.
- **Monthly Analysis**: A clear and intuitive overview of monthly financial performance with easy-to-read comparisons of income, expenses, and profits.
- **Geographical Visualizations**: Mapping and graphical representation of shipment data to different provinces, offering insights into geographical trends.
- **Expense Breakdown**: Detailed categorization of expenses, including fuel, insurance, repairs, tolls, and others, presented in both absolute and percentage terms.
- **Profitability Tracking**: Real-time tracking of profitability with monthly balances and clear income vs expense comparison.
- **Driver and Odometer Insights**: Detailed breakdown of payroll and vehicle usage to help optimize costs and resource allocation.

## Link to the dashboard
https://app.powerbi.com/groups/me/reports/5b0c2312-ef6a-450e-a7b7-84a420e94ddb/ReportSection?experience=power-bi

## Technologies Used

- **Data Processing , Analysis & Visualisation**: POWER BI

## Installation Instructions

To get started with the dashboard, follow the steps below to set up your local environment:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/transportation-financial-dashboard.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd transportation-financial-dashboard
   ```

## Results and Insights

The dashboard provides actionable insights into the financial health of the transportation company. Below are some of the key findings:

- **Profitability Trends**: The Income vs Expenses chart highlights months with unusually high or low profitability, enabling the company to investigate seasonal trends, unforeseen expenses, or periods of increased demand.
- **Geographic Insights**: The graphical representation of shipments to various provinces allows the company to see which regions are more profitable or have higher operational costs, aiding in targeted marketing and resource allocation.
- **Cost Optimization**: By visualizing expenses (fuel, insurance, repairs, tolls, etc.), the dashboard helps identify cost-saving opportunities, such as optimizing routes or negotiating better terms with suppliers.
- **Payroll Monitoring**: Monitoring driver payroll on a monthly basis ensures that labor costs are well-managed and aligned with the company's operational needs.
- **Operational Efficiency**: The odometer data, when combined with fuel and repair expenses, allows the company to track the efficiency of its fleet and identify areas for improvement.

## Future Enhancements

- **Predictive Analytics**: Implement machine learning models to predict future income, expenses, or the likelihood of additional stops based on historical data.
- **Real-Time Data Integration**: Integrate real-time data sources (e.g., GPS or fuel sensor data) for live updates on fleet operations and expenses.
- **Mobile-Friendly Version**: Develop a mobile-optimized version of the dashboard for easy access and monitoring on-the-go.
- **Advanced Filtering**: Allow users to filter data by region, vehicle type, or specific cost categories for more granular analysis.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Submit a pull request.
