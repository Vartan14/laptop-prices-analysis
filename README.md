# Laptop Price Prediction

This project focuses on analyzing and modeling laptop prices based on various features. The primary goal is to explore the relationships between laptop characteristics and their prices, and to develop machine learning models for price prediction.

## Table of Contents

- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Data Visualization](#data-visualization)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Results](#results)
- [Conclusion](#conclusion)
- [Usage](#usage)
- [Requirements](#requirements)

## Dataset

The dataset contains various features of laptops including price, manufacturer, screen size, RAM, weight, CPU, GPU, storage, and operating system.

## Data Preprocessing

- Load the dataset and inspect its structure.
- Remove unnecessary columns (e.g., "Operating System Version").
- Split and convert text data to numeric formats (e.g., weight, RAM, screen size).
- Clean and rename columns for better readability.

## Data Visualization

- Analyze the distribution of laptop prices.
- Plot relationships between prices and various features such as manufacturer, screen type, CPU, RAM, etc.

## Feature Engineering

- Create new columns based on existing data (e.g., touchscreen, IPS screen).
- Calculate pixel density (PPI) from screen resolution and size.
- Convert text data about processors and storage into more informative categories.

## Modeling

1. **Data Splitting**: Split the data into training and testing sets.
2. **Models**:
   - **Linear Regression**
   - **Decision Tree**
   - **Random Forest**
3. **Evaluation**: Assess the models using metrics like Mean Absolute Error (MAE) and R-squared (R²).

## Results

- **Linear Regression**:
  - MAE: 32.74
  - R²: 0.62
- **Decision Tree**:
  - MAE: 28.35
  - R²: 0.65
- **Random Forest**:
  - MAE: 22.57
  - R²: 0.78

## Conclusion

The Random Forest model outperformed other models, showing the lowest MAE and highest R², indicating it most accurately predicts laptop prices based on their features. This project can be beneficial for manufacturers, retailers, and consumers to better understand the impact of various characteristics on laptop prices.

## Usage

To run this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/laptop-price-prediction.git
   cd laptop-price-prediction
   ```

2. Run the notebook or script:
     ```bash
     jupyter notebook
     ```
   - Open `laptop_price_prediction.ipynb` and run all cells.


## Requirements

- Jupyter
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

