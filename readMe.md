# Background

The Meditation App offers a range of meditation services for a paid subscription and in-app purchases.

## Challenge

The challenge for this project is to understand our customer base and explore how we can maintain a high paid conversion rate.

## Data

The dataset for this project includes two CSV files: `user_demographics_v1` and `purchase_data_v1`.

#### user_demographics_v1
This file includes demographic information for each user, such as `uid`, `reg_date`, `device`, `gender`, `country`, and `age`.

#### purchase_data_v1
This file includes purchase data for each user, such as `date`, `uid`, `sku`, and `price`.

The dataset is provided in CSV format and contains 10,000 rows in `user_demographics_v1` and 9,006 rows in `purchase_data_v1`.

## Project Structure

The project structure is organized as follows:

├── data/
│ ├── user_demographics_v1.csv
│ └── purchase_data_v1.csv
│
├── README.md
├── analysis.ipynb


## Running the Project

To run the project, follow these steps:

1. Clone the repository.
2. Install the required dependencies.
3. Open `analysis/analysis.ipynb` in Jupyter Notebook.
4. Run the code cells to reproduce the analysis.
5. Check the `visualizations` folder for the output visualizations.

## Dependencies

This project requires the following dependencies:

- pandas
- numpy
- matplotlib
- seaborn

You can install these dependencies using pip:
`pip install pandas numpy matplotlib seaborn`

