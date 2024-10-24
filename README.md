
# Bakery Sales Report/Dashboard


## Problem Statement

This report/dashboard helps the bakery understand their customers better. It helps the bakery know if their customers by understanding the time of the day, day of the week and period of the month during which they have more patronage and also to know if they are satisfied with their services. Through different ratings, they get to know their  area of improvement and specialization, and thus they can improve their services by identifying these area. 

Since most sales occured on weekends during the time period, they should focus more on producing less quantity of products during weekdays and more during weekends to maximize profit. 

Also, since there are more patronage during the last quarter of the year in 2016 and more patronage during the first quarter in 2017, the bakery should focus more on producing more products during those period of the year.


### Steps followed 

- Step 1 : Launch the Power BI Desktop and open a new page.
- Step 2 : Import the dataset as a csv file into power query editor
- Step 3 : Profiled the dataset and discovered there was an error in the "DayType" column therefore it was removed.
- Step 4 : Duplicated the original table to create dimension tables and modifying them by ceating conditional columns and linking them with the fact table hence, modelling.
- Step 5 : Closed and loaded the data back to the power bi desktop and creating measures. 
- Step 6 : Creating visuals by building reports to answer some of the business problems and creating the dashboard which included a slicer of the time of the day to gain more insight about how it affects the business operation.
          


### Reports and Findings 
After detailed Analysis was carried out, the findings were summarized in the reports generated below 


![TOTAL AUANTITY SOLD PER DAY OF THE WEEK](https://github.com/omaksounds/omaksounds/assets/172240838/8f647051-c4da-4bdd-90c0-3d1eab387f56)


        
At 3,554, Saturday had the highest Quantity of Goods sold and was 55.33% higher than Wednessday, which had the lowest Quantity of Goods sold at 2,288.

Saturday accounted for 17.33% of Quantity of Goods.

Across all the days of the week, Quantity of Goods sold ranged from 2,288 to 3,554.




![QUANTITY SOLD PER YEAR](https://github.com/omaksounds/omaksounds/assets/172240838/b964d167-c2c9-4cf9-a2cc-133dbf7def74)


        
 Quantity of Goods for 2017 (12,363) was higher than 2016 (8,144).
 
 2017 accounted for 60.29% of Quantity of Goods.
 
         
 
 ![QANTITY SOLD PER TIME OF DAY](https://github.com/omaksounds/omaksounds/assets/172240838/86e658bd-8240-494c-a950-131e597d0586)



 
 At 10,226, Afternoon had the highest Quantity of Goods sold and was 28,305.56% higher than Night, which had the lowest Quantity of Goods sold at 36.
 
 Afternoon had the highest Quantity of Goods sold at 10,226, followed by Morning, Evening, and Night.
 
Afternoon accounted for 49.87% of Quantity of Goods.
    
 Across all 4 Time of Day, Quantity of Goods ranged from 36 to 10,226.
 
 
 
![TOP 10 SELLING PRODUCTS](https://github.com/omaksounds/omaksounds/assets/172240838/b9399667-9ffa-491a-a7f5-6f73533e76ff)

 
 - *Highest Selling Product:* Coffee, with a significant margin, is the highest selling product, amounting to 5,471 units.

- *Second Highest:* Bread follows as the second most popular product, with 3,325 units sold.

- *Least Selling in Top 10:* Brownie is the least sold among the top 10, with 379 units.





The data clearly shows that beverages such as coffee and tea dominate the sales, indicating a high demand for drinks. Bakery items like bread, cake, and pastries also show substantial sales figures, suggesting they are popular choices among consumers. The relatively lower quantities of items like hot chocolate, cookies, and brownies highlight a lesser preference compared to other items listed.



This report can be useful for inventory planning, marketing strategies, and understanding consumer preferences.
 
 
![TOTAL QUANTITY SOLD PER MONTH AND YEAR](https://github.com/omaksounds/omaksounds/assets/172240838/e9788b9a-ca1c-4244-8811-c27e9b349018)

This report analyzes the quantity of goods sold on a monthly basis for the years 2016 and 2017. The data visualization provided highlights the fluctuations in sales quantities across these two years.



FINDINGS AND RECOMMENDATIONS


1. #### Significant Increase in 2017 (Early Months):

   The quantity of goods sold saw a substantial increase in 2017 compared to 2016 from January to March, with each of these months exceeding 2,000 units sold.



2. #### Highest Sales in 2016:

   In 2016, the highest sales were recorded from October to December:

     - October: 688 units

     - November: 2,593 units

     - December: 2,316 units



3. #### Seasonal Trends:

   -Both years exhibit clear seasonal trends with peaks and troughs.

   -In 2016, there is a significant peak in sales during the last quarter, particularly in November and December.

   -In 2017, the peak months are January, February, and March.



4. Lowest Sales Period:

   - The lowest sales period in both years appears to be the summer months, specifically July and August, where quantities dropped significantly.





#### Summary

The data demonstrates a notable growth in sales in 2017 compared to 2016 in the early months, while 2016 saw its highest sales in the last quarter. The significant peak in November and December 2016 indicates high seasonal demand during these months.



These insights can help the bakery in strategizing inventory management, marketing efforts, and resource allocation to maximize sales during peak months and identify opportunities to boost sales during traditionally lower-performing months. By understanding these trends, the bakery can better prepare for high-demand periods, ensuring sufficient stock and staff to handle increased sales, while also developing promotions or new product offerings to stimulate demand during slower months. This strategic approach can lead to improved customer satisfaction and overall business growth.



![TOTAL NUMBER OF PRODUCT](https://github.com/omaksounds/omaksounds/assets/172240838/4dd2d6c1-ce0e-47d4-9598-eb135129f986)

From the analysis i was able to uncover that there are 94 different products produced by the bakery and these can further be categorized into Beverages such as Coffee,Tea, e.t.c., Bakery and Pastry such as Bread, Cookies, e.t.c., Savory Items such as Bacon, Caramel Bites, e.t.c., Sweet Treats such as Cake, Honey, e.t.c., and other Miscellaneous likeBasket, Tshirt e.t.c.

 

 
![TOTAL QUANTITY SOLD](https://github.com/omaksounds/omaksounds/assets/172240838/32146bfd-1fec-42ec-bbf5-0f436d07a15e)
From the analysis it was discovered that within the time period from January 2016 to December 2017, a total number of 20,507 items were sold.


![TOTAL TRANSACTION](https://github.com/omaksounds/omaksounds/assets/172240838/398c1c7d-4e8b-4eac-8ae5-08118793600b)

The Analysis shows that there were a total transaction of 9,465 within the time period.


#### Dashboard
![DASHBOARD](https://github.com/omaksounds/omaksounds/assets/172240838/fc9bd880-bd14-4c2c-befe-58f20ce2cf22)

The dashboard above is a summary of the reports generated during the analysis.

