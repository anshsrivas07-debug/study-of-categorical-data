# Study-of-Categorical-Data
This experiment demonstrates how categorical data can be analyzed using the Python (programming language) library pandas (Python library). Categorical data represents variables that contain labels or categories such as product types, payment methods, gender, grades, etc. The experiment uses two datasets to perform different operations including frequency counting, identifying unique values, cross-tabulation, percentage distribution, filtering, grouping, and sorting.

In the first dataset, an order dataset was created containing attributes such as Order ID, Category, Payment Method, Delivery Status, and Customer Type. The data was converted into a pandas DataFrame and various categorical analysis techniques were applied.

First, frequency counts were calculated using value_counts() to determine how many orders belonged to each category and payment method. The results showed that Electronics had the highest number of orders (4), while Clothing and Grocery had 3 orders each. Similarly, Credit Card and PayPal were the most commonly used payment methods, followed by UPI and Cash.

Next, unique values and the number of unique categories were obtained using unique() and nunique(). This helped identify all available categories and delivery statuses in the dataset. It showed that there are three product categories (Electronics, Clothing, Grocery) and three delivery statuses (Delivered, Pending, Express).

The experiment then used cross-tabulation (pd.crosstab) to analyze relationships between two categorical variables. For example:

Category vs Payment Method showed how different payment methods were used for each product category.

Delivery Status vs Customer Type revealed that Regular customers mostly had delivered orders, while New customers had mostly pending orders, and Returning customers used express delivery.

A percentage distribution of categories was also calculated, showing that Electronics accounted for 40% of the orders, while Clothing and Grocery each accounted for 30%.

The dataset was also filtered to extract only orders from the Electronics category, demonstrating how to analyze a specific subset of data. Additionally, grouping and sorting operations were performed using groupby() and sort_values() to organize the data based on categories and payment methods for better interpretation.

In the second dataset, a CSV file containing student information (Student, Gender, Department, and Grade) was analyzed. The data was loaded using read_csv() and similar categorical analysis techniques were applied.

First, grade frequency was calculated, showing that Grade B was the most common (24 students), followed by Grade A (22 students) and Grade C (14 students). The percentage distribution indicated that 40% of students received Grade B, 36.67% received Grade A, and 23.33% received Grade C.

Next, the department distribution was analyzed. The results showed that CSE had the highest number of students (20), followed by IT (18), while ECE and Mechanical each had 11 students.

The gender distribution analysis revealed that the dataset had an equal number of male and female students (30 each), indicating balanced representation.

A cross-tabulation of Gender vs Grade was also performed. It showed that female students had more A grades (14) compared to males (8), while male students had slightly more B and C grades.

Finally, grouping by department and grade was performed to examine the distribution of grades within each department. The analysis showed that CSE students had the highest number of A grades, while B grades were common across most departments.

Overall, this experiment demonstrates how categorical data can be effectively explored and analyzed using pandas functions such as value_counts(), unique(), nunique(), crosstab(), groupby(), and sort_values(). These techniques help summarize categorical datasets, identify patterns, and understand relationships between variables.

#conclusion
In this experiment, categorical data analysis was successfully performed using Python (programming language) and the pandas (Python library) library. Various techniques such as frequency counting, percentage distribution, cross-tabulation, filtering, grouping, and sorting were used to analyze two different datasets.

The analysis of the order dataset revealed patterns in product categories, payment methods, delivery statuses, and customer types, while the student dataset provided insights into grade distribution, department-wise student counts, and gender-based performance.

Through these operations, the experiment demonstrated that categorical data analysis helps in identifying trends, relationships between variables, and meaningful patterns within datasets. Using pandas makes the process efficient and simple, enabling better data understanding and supporting data-driven decision making.
