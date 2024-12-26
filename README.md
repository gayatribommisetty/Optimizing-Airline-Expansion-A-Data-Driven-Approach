# Optimizing-Airline-Expansion-A-Data-Driven-Approach
## Project Overview
This project aims to assist an airline company in strategically expanding into the US Domestic airline market by identifying 5 profitable round-trip routes using comprehensive data analysis and insights. The company's motto, "On time, for you," emphasizes punctuality as a cornerstone of their brand identity.
## Datasets Used
1. **Flights Dataset**: Contains information about flight operations.
2. **Airport Codes Dataset**: Provides details about various airports.
3. **Tickets Dataset**: Includes ticket sales and passenger data.
   
## Key Steps in the Project
1. **Data Cleaning and Preprocessing**: Removing null values and filtering relevant data.
2. **Feature Engineering**: Creating new metrics such as fare per passenger.
3. **Outlier Removal**: Using IQR method to clean the dataset.
4. **Data Aggregation and Analysis**: Grouping data by origin and destination to find averages.
5. **Airport Classification**: Filtering for medium and large airports.
6. **Financial Calculations**: Analyzing profitability and break-even points.
7. **Route Optimization**: Selecting the most profitable routes for investment.

## Key Metrics and Variables
**Ticket Data
1. ITIN_FARE_PER_PASSENGER: Itinerary fare per passenger
2. Normalized_ROUTE: Combined origin and destination for round trips
**Flight Data
1.TOTAL_REVENUE: Includes ticket fare and baggage fare
2.TOTAL_COST: Covers distance-related costs, airport charges, and delay charges
3.AIRPORT_CHARGES: For origin and destination, based on airport type
4.DELAY_CHARGES: For departure and arrival delays
5.TOTAL_PROFIT: Revenue minus cost per round trip
6.BREAK_EVEN: Number of flights needed for a route to break even

## Key Constraints and Assumptions
1. Incidental expense per airplane: $90 million
2. Focus on punctuality as per company motto
3. Analysis limited to medium and large US airports
   
## Visualizations
- Pie chart showing the distribution of medium vs large airports.
-[image](https://github.com/user-attachments/assets/bc220771-f7d4-4087-907f-0f4ebc2f4dd9)

## Top 10 Busiest Routes
Los Angeles (LAX) to San Francisco (SFO) is the busiest route with 13,068 flights. The second busiest route is Las Vegas (LAS) to Los Angeles (LAX) with 11,290 flights. Following that, LaGuardia (LGA) to Chicago O'Hare (ORD) sees 11,092 flights.
The Honolulu (HNL) to Kahului (OGG) route in Hawaii operates 9,268 flights. Los Angeles (LAX) to Seattle (SEA) handles 8,898 flights, while Atlanta (ATL) to Orlando (MCO) serves 8,620 flights.
Portland (PDX) to Seattle (SEA) maintains 8,540 flights. Atlanta (ATL) to Fort Lauderdale (FLL) operates 8,268 flights. The Atlanta (ATL) to LaGuardia (LGA) route runs 7,894 flights, and Boston (BOS) to LaGuardia (LGA) rounds out the top routes.

## 10 Most Profitable Round Trip Routes
The Washington DC (DCA) to Chicago O'Hare (ORD) route leads in profitability with approximately $218.4 million in profits. While not having the highest revenue, its efficient cost management makes it highly profitable.
Atlanta (ATL) to Los Angeles (LAX) ranks second, generating about $198.1 million in profit. This route also has the highest revenue among all routes at nearly $397 million, demonstrating strong demand for this cross-country connection.
The Atlanta (ATL) to Charlotte (CLT) route comes in third with $197.2 million in profit. Despite lower total revenue, its relatively low operating costs help maintain strong profitability.
Charlotte (CLT) to Wilmington (ILM) is fourth with $182.2 million in profit. Atlanta (ATL) to LaGuardia (LGA) follows closely with $180.7 million in profits, benefiting from high revenue of about $396.1 million.
The Washington DC (DCA) to LaGuardia (LGA) route generates $165.1 million in profit, while Charleston (CHS) to Charlotte (CLT) earns $163.3 million. LaGuardia (LGA) to Chicago O'Hare (ORD) produces $153.3 million in profit, despite having the highest revenue in the dataset at $453.9 million.
Rounding out the top 10 are Dallas-Fort Worth (DFW) to Houston (IAH) with $150.5 million and Newark (EWR) to Chicago O'Hare (ORD) with $146.7 million in profits.
Interestingly, all these routes maintain a consistent 65-66% occupancy rate, suggesting well-optimized capacity management across these profitable routes.

## Recommended Round Trip Routes for Investment
 By considering factors like total_profit,Break even,occupancy rate and delays the five recommended routes would be ATL-LGA,DCA-ORD, LGA-ORD, MSP-ORD,BOS-LGA.These routes not only considers the financial perspective but also considers brand Image by considering delays, Operational Effiency by considering Break even etc

## Break-Even Analysis
The break-even analysis of the top 5 routes shows how many round trips each route needs to become profitable. The LGA-ORD route needs the most trips (about 65,000) to break even, making it the most demanding route financially. BOS-LGA comes second, needing around 30,000 trips, while ATL-LGA requires 20,000 trips. The DCA-ORD and CHS-CLT routes are more efficient, needing only about 5,000 and 2,000 trips respectively to start making money. This means these last two routes can become profitable much more quickly than the others.

## Additional Insights
(Insert key findings and insights derived from the analysis)

## Technical Skills Demonstrated
- Python programming
- Data manipulation with Pandas and NumPy
- Data visualization using Seaborn, Matplotlib, and Plotly Express
- Statistical analysis and outlier detection
- Financial modeling and break-even analysis

## Soft Skills Applied
- Problem-solving
- Data interpretation
- Strategic thinking
- Decision-making based on data insights
- Clear communication of complex findings

