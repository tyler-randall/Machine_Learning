# Population Analysis with Machine Learning Regression

## Overview
This project analyzes population data using two regression methods: Linear Regression and K-Nearest Neighbors (KNN). The goal is to understand population trends over time using machine learning techniques.

## Dataset
- **File**: `population_vs_day.csv`
- **Columns**:
  - `date`: Specific date
  - `day`: Day index (starting from 20190101 as Day 1)
  - `population`: Population of a species (in millions)

## Prerequisites
- Python 3.x
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - scikit-learn

## Installation
1. Clone the repository
```bash
git clone https://github.com/yourusername/population-analysis.git
cd population-analysis
```

2. Install required libraries
```bash
pip install pandas numpy matplotlib scikit-learn
```

## Key Findings
- Maximum population: 151,667.5013
- Minimum population: 0.0
- Population follows a bell curve distribution
- K-Nearest Neighbors (KNN) model provides a better fit compared to Linear Regression

## Analysis Methods
1. **Linear Regression**: 
   - Creates a straight-line model of population growth
   - Less adaptable to complex population trends

2. **K-Nearest Neighbors (KNN)**:
   - More flexible model
   - Captures non-linear population dynamics
   - Better reflects the actual population changes

## Visualization
The project includes scatter plots showing:
- Original population data
- Linear Regression predictions
- KNN model predictions

## Potential Improvements
- Experiment with different regression models
- Use more advanced time series analysis techniques
- Incorporate additional features for more accurate predictions

## License
[Choose an appropriate license, e.g., MIT License]

## Author
[Your Name]

## Acknowledgments
- Course: ANLY 6110 - Data Analytics II
- Dataset provided as part of Machine Learning Landscape assignment
