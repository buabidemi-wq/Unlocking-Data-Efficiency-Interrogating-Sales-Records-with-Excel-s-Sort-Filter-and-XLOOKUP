# Unlocking-Data-Efficiency-Interrogating-Sales-Records-with-Excel-s-Sort-Filter-and-XLOOKUP
This project demonstrates technical mastery in the structural interrogation of data using Excel. By leveraging Sort, Filter, XLOOKUP, and INDEX &amp; MATCH, I was able to move beyond basic aggregation and provide precise, definitive answers to complex business questions.
**Introduction**
Following an initial exploratory analysis focused on calculated metrics, this second project phase dives into data interrogation—the ability to quickly and accurately retrieve specific, non-aggregated information from a sales dataset.

For this analysis, I leveraged Microsoft Excel’s core data management tools: sorting, filtering, and lookup functions (XLOOKUP and INDEX & MATCH), applied to the same 100-row sales dataset. This exercise simulates real-world demands for rapid data retrieval and precise information lookup, demonstrating technical proficiency in navigating structured data.

**Objectives**
The core objectives for this stage of the project were to demonstrate mastery in:

Benchmarking Performance: Identifying top and bottom performers based on sales value and quantity using Sort and Filter.
Targeted Querying: Isolating specific subsets of data (e.g., Tech in Lagos) to answer highly specific business questions.
Precision Retrieval: Utilising advanced lookup functions (XLOOKUP and INDEX \ MATCH) to retrieve data based on multiple criteria, sequential order, or row position.
Report
1. Performance Benchmarking and Extremes (Sorting & Filtering)
This initial exploration used the sort function to quickly establish the performance boundaries of the dataset:

Highest Sales: By sorting the dataset by sales in descending order, I immediately identified the regions driving the highest single-transaction value. The top five transactions were recorded in Ibadan, Abuja, Kano, Abuja, and Ibadan, with the highest individual sale hitting ₦348,306.
Press enter or click to view image in full size

Top Five Highest Selling Table Screenshot
Lowest Quantity: A reverse sort, by Quantity from lowest to highest, showed operational extremes. Both Abuja and Lagos recorded the lowest quantity order with 1 item per transaction.
Press enter or click to view image in full size

High-Value and High-Volume Orders: Using filtering, I isolated significant order types. The analysis confirmed 77 orders exceeded the ₦100,000 sales threshold. Furthermore, both Kano and Lagos recorded the highest high-volume orders over 20, with transactions reaching 30 quantities.
Structural Analysis: A sort by Region (A to Z) confirmed that the first 10 rows were all from Abuja, indicating its placement in the alphabetical sort.
Press enter or click to view image in full size

2. Targeted Data Interrogation (Filtering Specifics)
Filtering allowed for the creation of focused subsets to answer crucial operational questions:

Geographic and Category Focus: Filtering for Tech products sold exclusively in Lagos revealed 13 specific records — a critical finding for assessing that region’s market segment strength.

Personnel and Time Focus: By filtering orders handled by Sales Rep Yusuf in February, I identified 7 records, which is key for monthly productivity assessment.
Category Specialization: Filtering for Grocery sales only showed that Samuel appears the most in the list of sales representatives, confirming his high involvement in this category.
Initial Sales Analysis: Sorting the dataset by Date (Oldest to Newest) confirmed that Mouse (a Tech product) was the very first product sold in the year.
Team Diversity: A final sort by Product (A to Z) revealed that the product “Phone” was sold by four different Reps: Aisha, Samuel, Yusuf, and Musa, demonstrating robust product knowledge across the team.
3. Precision Data Retrieval (Lookup Functions)
This section demonstrates the use of XLOOKUP and INDEX & MATCH to retrieve single data points with high accuracy, often based on complex or conditional criteria. This is essential for providing rapid, definitive answers to ad-hoc business queries.

Basic Retrieval: I retrieved definitive data points such as the Sales Amount for OrderID 10125 (₦336,548) and the Quantity for OrderID 10172 (12) using direct XLOOKUP formulas.
Conditional Retrieval: XLOOKUP was used to find the Region for Sales Rep Aisha (Abuja) and the Category for the product “Keyboard” (Tech). I also successfully identified Bread as the product associated with the highest sales value by performing a lookup on the sorted data.
Composite and Sequential Lookups:
To find the Rep responsible for the earliest sale of a Laptop, I used XLOOKUPto find the earliest date a laptop was sold and then nested another XLOOKUP to retrieve the Rep (Grace) corresponding to that date and product.
The date of the first Grocery transaction handled by Grace (2/24/2024) was found using an XLOOKUP combining multiple lookup criteria (Grace AND Grocery) into a single logical search.
Positional Retrieval: I demonstrated the classical INDEX function to retrieve the sales amount for the 10th row in the dataset (₦181,739).

**Recommendation**
Based on the precise insights gained through targeted querying, I recommend the following strategic actions:

Investigate High-Value Transactions: Focus marketing and follow-up efforts on Ibadan, Abuja, and Kano, which drive the highest single-transaction revenue. Analyzing the customers behind the top 5 transactions should be a priority.
Optimize Product Stock: Since Bread was identified as the product associated with the single highest sales value (after sorting), its placement and inventory levels should be reviewed, as it drives maximum return.
Targeted Marketing in Lagos: Given the discovery of 13 specific records for Tech sales in Lagos, this segment appears robust and warrants increased targeted advertising and resource allocation.
Sales Specialization: Use the finding that Samuel appears most frequently in Grocery sales to either formalize his specialization or use him as a trainer to disseminate best practices across the team.
**Conclusion**
This project demonstrates technical mastery in the structural interrogation of data using Excel. By leveraging Sort, Filter, XLOOKUP, and INDEX & MATCH, I was able to move beyond basic aggregation and provide precise, definitive answers to complex business questions.

This ability to quickly and accurately retrieve pinpoint information — whether based on specific criteria, sequence, or position — is a foundational skill for any data analyst aiming to provide agile and accurate business intelligence.
