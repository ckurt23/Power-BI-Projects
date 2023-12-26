This GitHub repository contains the files related to the omnichannel sales report created for FLO retailer using Power BI.
The sales report is based on a CSV file with approximately 20,000 rows of sales records and includes 12 variables/columns;

`master_id`
`order_channel`
`last_order_channel`
`first_order_date`
`last_order_date`
`last_order_date_online`
`last_order_date_offline`
`order_number_total_ever_online`
`order_number_total_ever_offline`
`customer_value_order_ever_online`
`customer_value_order_ever_offline`
`interested_in_categories_12`

## How to Use the Dashboard

1. Download the Power BI dashboard (.pbix) file.
2. Open Power BI Desktop and load the dashboard file.
3. Explore the various visuals and use the slicer to dynamically filter data.
4. Refer to the case study questions for specific insights.

## Case Study Questions

The dashboard addresses the following 10 case study questions:

First, add Header, FLO logo.
Then;
1. Create 2 new columns as total_order_num (`order_number_total_ever_online` + `order_number_total_ever_offline`) and total_customer_value (`customer_value_order_ever_online` + `customer_value_order_ever_offline`)
2. Create 6 KPI's as shown on PDF.
3. Use YEAR and MONTH functions and create 2 differenet variables from `last_order_date`
4. Create Slicers by using `order_channel` and also 2 different variables created in Step 3. (as shown on top*left of PDF)
5. Add "Clustered Column Chart" to show the total order quantity and add a header as "Sales by Month".
6. Add Pie Chart showing the total order quantity per Order Channel.
7. Create a new table by using `master_id` - `last_order_date` - `order_channel` - total_order_num (created on Step 1) - customer_total_value (created on Step 1)
8. Order the newly created table on Step 7 in Desceding Order for customer_total_value
9. Create a new Measure named Target as customer_total_value * 1.5
10. Add Clustered Bar Chart for customer_total_value per order_channel


If you have any feedback, suggestions, please feel free to reach me.

Thank you for exploring the FLO Retailer Sales Reporting Dashboard!
