# Survey Data Analysis Dashboard 📊

This project is an interactive web dashboard built with Streamlit to analyze the provided survey data. It includes data visualizations with dynamic filters and several machine learning models.

## Features

-   **Data Visualization**: An interactive dashboard with filters for Age, Gender, and Income. Includes charts for purchase likelihood, willingness to pay, and a scatter plot for health consciousness.
-   **Classification**: A Random Forest model predicts whether a customer is likely to purchase a new product.
-   **Regression**: A Random Forest model predicts a customer's willingness to pay (in dollars).
-   **Clustering**: K-Means clustering segments customers based on their attitudes and behaviors.
-   **Association Rules**: Apriori algorithm finds patterns in beverage consumption (e.g., "people who drink X also tend to drink Y").

## Project Files 📁

-   `app.py`: The main Python script containing all the Streamlit app code.
-   `survey_data.csv.csv`: The raw dataset used for the analysis.
-   `requirements.txt`: A list of the necessary Python libraries for the project.
-   `README.md`: This file.

## How to Run Locally

1.  **Clone the repository** (or download the files to a single folder).

2.  **Create a virtual environment** (recommended):
    ```bash
    python -m venv venv
    ```

3.  **Activate the environment**:
    -   **Windows**: `venv\Scripts\activate`
    -   **Mac/Linux**: `source venv/bin/activate`

4.  **Install the required libraries**:
    ```bash
    pip install -r requirements.txt
    ```

5.  **Run the Streamlit app**:
    ```bash
    streamlit run app.py
    ```

6.  Your browser will automatically open to the dashboard.