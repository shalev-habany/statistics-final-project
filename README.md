# Life Expectancy Analysis - Statistics Final Project

This project analyzes life expectancy data using statistical methods and machine learning techniques to understand factors that influence life expectancy across different countries.

## 📊 Project Overview

The project explores the relationship between life expectancy and various socio-economic factors such as:
- GDP per capita
- Income composition
- Alcohol consumption
- Healthcare indicators
- Education levels
- And more...

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- pip (Python package installer)

### Installation

1. **Clone or download this repository**
   ```bash
   git clone <repository-url>
   cd statistics-final-project
   ```

2. **Install required dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Open the analysis notebook**
   - Navigate to `life_expectancy.ipynb`
   - Click on the file to open it in Jupyter

## 📁 Project Structure

```
statistics-final-project/
├── data/
│   └── Life Expectancy Data.csv    # Main dataset
├── figures/                         # Generated visualizations
│   ├── alcohol-by-status.png
│   ├── alcohol-scatter-plot.png
│   ├── hist-alcohol.png
│   ├── quarter-gdp-alcohol.png
│   └── quarter-income-alcohol.png
├── life_expectancy.ipynb           # Main analysis notebook
├── requirements.txt                 # Python dependencies
└── README.md                       # This file
```

## 🔧 Dependencies

The project uses the following Python packages:
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - Basic plotting
- **seaborn** - Statistical data visualization
- **scikit-learn** - Machine learning algorithms
- **scipy** - Scientific computing
- **sweetviz** - Automated exploratory data analysis

## 📈 Running the Analysis

1. **Ensure all dependencies are installed**
   ```bash
   pip install -r requirements.txt
   ```

2. **Start Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

3. **Open `life_expectancy.ipynb`**
   - The notebook contains the complete analysis pipeline
   - Run cells sequentially from top to bottom
   - All visualizations will be saved to the `figures/` directory

4. **Data Loading**
   - The notebook automatically loads data from `data/Life Expectancy Data.csv`
   - Ensure the data file is in the correct location

## 🎯 Key Features

- **Exploratory Data Analysis (EDA)** using Sweetviz
- **Statistical modeling** and hypothesis testing
- **Machine learning** approaches for prediction
- **Data visualization** with matplotlib and seaborn
- **Comprehensive reporting** of findings
