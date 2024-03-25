# Personal Finance Assistant

The Personal Finance Assistant is a data mining project designed to help users manage their finances effectively by analyzing their spending habits, categorizing transactions, and creating personalized savings goals and budget plans.

## Features:

- **Autoencoders and Fuzzy C-Means Clustering:** The project utilizes autoencoders and fuzzy c-means clustering to analyze average spending habits and incomes from a dataset. This allows for the identification of patterns and clusters within the data, enabling more accurate insights into individual financial behaviors.

- **Transaction Categorization:** Users can upload their banking transactions, which are then processed using a separate model for categorization. This model assigns categories to each transaction, such as groceries, utilities, entertainment, etc., making it easier for users to understand their spending patterns.

- **Monthly Averages Calculation:** The project calculates monthly averages for each spending category based on the user's transaction history. This provides users with a clear overview of their monthly spending habits and allows them to identify areas where they can potentially save money.

- **Personalized Savings Goal/Budget Plan:** Based on the user's financial data and goals, the project generates a personalized savings goal and budget plan. Users can set an intended savings goal and specify a timeframe for achieving it. The system then creates a budget plan that outlines recommended spending limits for each category to help users reach their savings goal.

## Technologies Used:

- **Python:** The project is primarily developed using Python programming language, leveraging its libraries for data analysis, machine learning, and web development.
- **Autoencoders and Fuzzy C-Means:** Autoencoders and fuzzy c-means clustering algorithms are implemented using libraries such as TensorFlow or PyTorch for deep learning and clustering tasks.

## Usage:

To use the Personal Finance Assistant:

1. Clone this repository to your local machine.
2. Open the jupyter notebook in Google Colab.
3. Upload the files `personal_transactions.csv` and `fbc_data_2022.csv` in Colab's local files.
4. Follow prompts to run the code, generate insights, and set savings goals.

Feel free to explore the code, contribute to further improvements, or use the project for personal financial management. Feedback and contributions are welcome!
