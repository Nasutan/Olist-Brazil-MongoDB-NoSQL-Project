Olist-Brazil-MongoDB-NoSQL-Project

This project is the continous project of Olist Brazil MySQL Project; https://github.com/Nasutan/Olist-Brazil-MySQL-SQL-Project which involves the use of both SQL (Structured Query Language) and NoSQL (MongoDB) databases to manage and analyze data. The project demonstrates the advantages and disadvantages of both types of databases. While NoSQL databases like MongoDB are flexible and scalable, they may lack the query flexibility and performance of SQL databases. In this case, SQL databases are chosen because they excel at handling structured data and complex queries while maintaining data integrity. This project highlights the importance of selecting the appropriate database type based on the specific requirements and characteristics of the data and analysis needed. It also emphasizes the significance of maintaining data integrity and query flexibility in data analysis projects.
<br>
<br>
Some .json queries are unsuccessful to upload since the files are too big. below is the table relation:
<br>
<img width="474" alt="Screenshot 2023-10-29 at 11 54 51 PM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/34267ffe-51aa-4ea2-b33c-5df6f498890a">
<br>
**Queries  pipeline**:
1. **Q1. Total number of orders made by customers each year.**
<br>
<img width="424" alt="Screenshot 2023-10-30 at 12 17 10 AM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/5f3c3b86-44fd-427d-8dc0-226676a0b089">
<br>
**Result:**
<br>
<img width="419" alt="Screenshot 2023-10-30 at 12 17 19 AM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/f62124f4-c21a-416f-9e0a-7bd2040b6f9d">

2. **Q2. How fastare customers receiving theirorder?**
<br>
<img width="553" alt="Screenshot 2023-10-30 at 12 17 26 AM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/00f89be3-49d3-4ffe-b047-915e00a5208d">
<br>
**Result:**
<br>
<img width="552" alt="Screenshot 2023-10-30 at 12 17 36 AM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/958fc572-55a4-457f-bab1-394b9ae1a3aa">

3. **Q3. Determining the average delivery time based on State.**
<br>
<img width="424" alt="Screenshot 2023-10-30 at 12 17 44 AM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/db5b514a-fbdc-49da-a79b-f63bb36e9221">
<br>
**Result:**
<br>
<img width="553" alt="Screenshot 2023-10-30 at 12 17 52 AM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/4408cd64-22be-445e-b1a8-ad9f8d59919e">

4. **Q4. Evaluating the performance of sellers andidentifying the best-performing ones.**
<br>
<img width="556" alt="Screenshot 2023-10-30 at 12 17 59 AM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/469f0c56-48df-4d6c-a1e2-4668f115b6b3">
<br>
**Result:**
<br>
<img width="556" alt="Screenshot 2023-10-30 at 12 18 21 AM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/befe3375-ef5b-4037-9a44-cfa4735c10e9">

5. **Q5. Analyzing the product categoryperformance and identifying the most popular and profitable product categories.**
<br>
<img width="554" alt="Screenshot 2023-10-30 at 12 18 31 AM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/41914639-69d0-470c-86e4-72db9e025745">
<br>
**Result:**
<br>
<img width="551" alt="Screenshot 2023-10-30 at 12 18 39 AM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/1d926ef4-3dc0-4f8a-a162-6989c41dc5eb">

6. **Q6. Knowing the most expensive and the cheapest products in each category.**
<br>
<img width="554" alt="Screenshot 2023-10-30 at 12 18 45 AM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/5395f3df-93a0-4956-8af8-7d5dae491b5a">
<br>
**Result:**
<br>
<img width="552" alt="Screenshot 2023-10-30 at 12 18 54 AM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/d4575f30-45c5-4cc9-8d82-22e12f6b84cd">

7. **Q7. Identifying if there are any relationships between the order status and the rating for the orders (the Customerexperiencewitheachstatus).**
<br>
<img width="555" alt="Screenshot 2023-10-30 at 12 18 59 AM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/5be3cc0f-533e-4900-b64b-7a8fe44f37d2">
<br>
**Result:**
<br>
<img width="554" alt="Screenshot 2023-10-30 at 12 19 06 AM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/16731ebf-56bb-4116-b141-9004f923e8c8">

8. **Q8. Identifying if there is a relationshipbetween freight value and the total sales basedon states.**
<br>
<img width="554" alt="Screenshot 2023-10-30 at 12 19 12 AM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/481d9362-3317-4872-b304-de9f5d79a93b">
<br>
**Result:**
<br>
<img width="556" alt="Screenshot 2023-10-30 at 12 19 19 AM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/0f213b29-b467-4972-8b62-58a81df0b6a2">

9. **Q9. List products with review score of 5 and total number of purchase.**
<br>
<img width="551" alt="Screenshot 2023-10-30 at 12 19 27 AM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/53263465-729c-44b7-8362-8cca03e6bdd3">
<br>
**Result:**
<br>
<img width="553" alt="Screenshot 2023-10-30 at 12 19 35 AM" src="https://github.com/Nasutan/Olist-Brazil-MongoDB-NoSQL-Project/assets/118417997/3da477c9-cabe-4be5-b983-c63011dc6385">

