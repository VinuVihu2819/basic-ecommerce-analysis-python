# Basic E-commerce Data Analysis with Python

This project demonstrates fundamental data analysis techniques using Python's built-in data structures (lists and dictionaries) to process a simulated e-commerce dataset. It showcases basic data manipulation, aggregation, and filtering, which are core skills for Data Scientists and AI Engineers.

## Project Goal

To analyze a simple dataset of customer and order information to extract basic business insights.

## Data Used

The project uses three simulated datasets represented as Python lists of dictionaries:
- `customers`: Contains customer IDs, names, ages, and genders.
- `products`: Contains product IDs, names, and prices.
- `orders`: Contains order details, linking customers to products, quantities, and dates.

## Analysis Performed

The Python script performs the following analysis tasks:

1.  **Total Revenue Calculation:** Computes the total money generated from all sales orders.
2.  **Customer Spending Summary:** Calculates the total amount spent by each individual customer.
3.  **Most Popular Product:** Identifies the product(s) with the highest total quantity sold across all orders.
4.  **Filtered Customers:** Finds customers who are above a specified age (e.g., 25) AND have placed at least one order.

## How to Run the Code

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourGitHubUsername/basic-ecommerce-analysis-python.git](https://github.com/YourGitHubUsername/basic-ecommerce-analysis-python.git)
    cd basic-ecommerce-analysis-python
    ```
    (Replace `YourGitHubUsername` with your actual GitHub username)
2.  **Open in Google Colab:**
    * Go to [colab.research.google.com](https://colab.research.google.com/).
    * Click `File` > `Upload notebook` and select the `Basic_E-commerce_Data_Analysis_Project.ipynb` file you downloaded from this repository.
    * Alternatively, you can open it directly from GitHub: `File` > `Open notebook` > `GitHub` tab, then search for your repository.
3.  **Run Cells:** Execute each code cell in the Colab notebook sequentially. The output of each analysis task will be printed.

## Technologies Used

* Python 3
* Basic Python Data Structures (Lists, Dictionaries, Sets)
* Control Flow (Loops, Conditionals)

## Future Enhancements (Optional Ideas)

* Integrate with Pandas for more robust data manipulation.
* Perform time-based analysis (e.g., monthly revenue).
* Identify top-spending customers or most loyal customers.
* Visualize results using Matplotlib or Seaborn.
* Connect to a real (small) database using SQL.

---
*This project was created as part of a learning journey in Data Science fundamentals.*
