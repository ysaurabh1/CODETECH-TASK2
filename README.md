# CODETECH-TASK2

#Name: Saurabh Yadav 
#Company:CODETECH IT SOLUTIONS 
#ID: CT0806GK 
#Domain: SQL 
#Duration: 12/12/24 to 12/1/25


#Overview of Task 2: Data Analysis with Complex Queries

<img width="1154" alt="Screenshot 2025-01-03 at 4 16 56 PM" src="https://github.com/user-attachments/assets/3081a8cc-e21f-4b4c-bc83-45092c9d2939" />
<img width="1154" alt="Screenshot 2025-01-03 at 4 18 05 PM" src="https://github.com/user-attachments/assets/24f70a74-fa82-4de5-8721-4ca52c1fb28c" />
<img width="1154" alt="Screenshot 2025-01-03 at 4 19 36 PM" src="https://github.com/user-attachments/assets/22a8ae62-d208-4a2a-92d9-7c11b9aaab88" />
<img width="1154" alt="Screenshot 2025-01-03 at 4 20 34 PM" src="https://github.com/user-attachments/assets/d884d2b8-152b-4a85-85f0-f4420894607a" />
<img width="1154" alt="Screenshot 2025-01-03 at 4 21 58 PM" src="https://github.com/user-attachments/assets/6a4487b1-244e-4326-922f-dbb2b6ced910" />



Objective:
The aim of Task 2 was to perform advanced data analysis on an airline database by leveraging complex SQL features, including window functions, subqueries, and Common Table Expressions (CTEs). The goal was to identify trends, patterns, and insights within the dataset and showcase the results in a structured format.

#Database Structure Recap:
The database consisted of the following key tables:

Passengers: Contains personal information about passengers.
Tickets: Includes booking details such as ticket ID, passenger ID, flight ID, booking date, and seat number.
Flights: Contains flight-related details, including flight ID, flight number, departure and arrival times, origin, and destination.
Destinations: Stores the destination city and country information.

1. Window Functions for Trends Analysis:
Window functions were used to calculate aggregate values over a specified set of rows while retaining detailed row-level information. These functions included ROW_NUMBER(), RANK(), and SUM().
2. Subqueries for Derived Information:
Subqueries were used to calculate specific metrics, such as the busiest destination or flights with the highest number of passengers.

3. Common Table Expressions (CTEs):
CTEs simplified complex queries by creating reusable, temporary result sets. They were used for multi-step analyses, such as finding trends over time.

Challenges and Key Findings:
Handling NULL Values:
NULL values in certain fields, such as DestinationID or PassengerID, required careful handling to avoid skewed results in the analysis.

Data Interpretation:
Patterns revealed by queries needed contextual understanding, such as why certain flights or destinations had higher demand.

Scalability:
Complex queries like those involving window functions and nested subqueries demonstrated the importance of database optimization to handle larger datasets efficiently.

Conclusion:
Task 2 showcased the power of advanced SQL features in extracting actionable insights from a database. By combining window functions, subqueries, and CTEs, the analysis revealed trends that could drive decision-making for optimizing operations, improving customer experiences, and enhancing resource planning. These techniques are invaluable for large-scale, data-driven decision-making in real-world scenarios.







