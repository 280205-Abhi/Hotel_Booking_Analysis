# Hotel Booking Analysis

This project is an exploratory data analysis (EDA) of hotel booking data to uncover patterns, customer behavior, trends, and insights about hotel reservations. The analysis is performed using Python, focusing on data cleaning, feature engineering, and creating various visualizations.

## Project Structure

### 1. Data Preparation
- **Loading Dataset**: Reading the hotel booking dataset from a `.csv` file.
- **Data Cleaning**: Handling duplicates, missing values, and invalid data entries. Correcting data types for specific columns.
- **Feature Engineering**: Adding new columns such as total nights, revenue per booking, season mapping based on months, etc.

### 2. Key Insights & Metrics
- **Customer Behavior**: Patterns such as cancellation rates, repeated guest ratios, and booking trends.
- **Hotel Types**: Insights into city hotels vs. resort hotels, including revenue and booking distribution.
- **Cancellation Analysis**: Exploring factors influencing cancellations, such as lead time and market segments.
- **Revenue Analysis**: Visualizations and comparisons of revenue by room type, total stays, and guest numbers.

### 3. Visualizations
- Exploratory visualizations using `matplotlib` and `seaborn` for easy interpretation of booking patterns, cancellations, customer types, and seasonality.

## Getting Started

### Prerequisites
To run this project, you will need Python 3.13 and the following Python libraries installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`
- `jupyter`


### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd hotel-booking-analysis
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Hotel_Booking_Analysis.ipynb
   ```

## Dataset

The dataset used for this analysis is sourced as `data/hotel_bookings.csv`. Ensure the file is placed inside the `data` directory as required by the notebook.

### Overview of the Dataset
The dataset includes the following features:
- Hotel types (city or resort)
- Customer demographics
- Booking lead times
- Stay duration, cancellation status
- Revenue and room types

## Key Findings

- **Booking Trends**:
  - Resort hotels had higher average lead times but lower booking rates compared to city hotels.
  - Certain months had peak booking and cancellation rates (visualized as seasonal trends).

- **Customer Patterns**:
  - Cancellation behavior is influenced by lead time and market segments (e.g., high cancellations for groups with long lead times).
  - Repeated guest percentage is significantly low, indicating scope for improvement in customer retention strategies.

- **Revenue Insights**:
  - Significant revenue variations exist based on room types, customer types, and seasonality.
  - Resort hotels contributed higher revenue when longer stays were involved.

## Visualizations

The analysis includes the following visualizations for insights:
- Hotel booking distributions (Resort vs. City)
- Cancellation patterns by months and hotels
- Revenue comparisons by room types and hotels
- Country-wise top bookings and top cancellations
- Market segment analysis for guests and cancellations

## Running the Analysis

To replicate the analysis or customize it for your dataset:
1. Load the dataset.
2. Perform data cleaning and transformation steps as outlined in the notebook.
3. Use the feature-engineered data to generate insights and create visualizations.
4. Export results and important insights for reporting.

## Project Directory
Hotel-Booking-Analysis/
│
├── data/
│   └── hotel_bookings.csv
│
├── Hotel_Booking_Analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore

Install the dependencies using the `requirements.txt` file.


## Dependencies

See `requirements.txt` for all required packages.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
