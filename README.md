# Exploratory Data Analysis App

This is the **EDA App** created using Streamlit and the `pandas-profiling` library. The app allows users to upload a CSV file and generate a comprehensive exploratory data analysis report.

## Features

- Upload CSV files to analyze your data.
- Generate a detailed Pandas Profiling report.
- Use an example dataset to see the app in action.

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/eda-app.git
    cd eda-app
    ```

2. Create and activate a virtual environment:

    ```sh
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. Install the required packages:

    ```sh
    pip install -r requirements.txt
    ```

4. Ensure that the `visions` package is installed with a compatible version for `ydata-profiling`:

    ```sh
    pip install visions>=0.7.5,<0.7.7
    ```

## Usage

1. Run the Streamlit app:

    ```sh
    streamlit run app.py
    ```

2. Open your web browser and navigate to `http://localhost:8501`.


