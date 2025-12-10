# NDM Hockey Travel Impact Analysis

This repository contains a comprehensive analysis of how travel affects hockey team performance using Jupyter notebooks.

## Overview

This analysis examines the impact of travel distance, travel time, timezone shifts, and travel stress on hockey team performance metrics including:
- Win/loss rates
- Goal differential
- Shots on goal
- Team offensive and defensive performance

## Files

- `hockey_travel_analysis.ipynb` - Main analysis notebook with data exploration, visualizations, and statistical testing

## Key Findings

### Travel Intensity Impact
- **Low Travel (1.5 hrs):** 25% win rate
- **Medium Travel (2-2.5 hrs):** 35.7% win rate (optimal)
- **High Travel (3+ hrs):** 16.7% win rate

### Stress Level Effects
- **Moderate Stress:** 41.2% win rate (optimal zone)
- **Low/High Stress:** 0% win rate (small samples)

### Timezone Impact (Most Notable)
- **No/Minimal Shift:** 23.1% win rate
- **Moderate 1-hr Shift:** 44.4% win rate (best)
- **Significant 2+ hr Shift:** 0% win rate

### Travel Type Comparison
- **Flights:** 36.8% win rate
- **Bus Trips:** 0% win rate

### Performance Within Trips
Teams show improvement as trips progress:
- Game 1: 25% win rate, -1.42 goal differential
- Game 2: 27.3% win rate
- Game 3: 100% win rate, +3.0 goal differential

## Analysis Sections

1. **Data Loading & Exploration** - Overview of dataset structure and summary statistics
2. **Data Cleaning & Preparation** - Data validation and feature engineering
3. **Travel Metrics Analysis** - Comparison of performance across travel conditions
4. **Visualizations** - Multiple charts showing travel impact on performance
5. **Statistical Testing** - Correlation analysis and t-tests for significance
6. **Summary Report** - Comprehensive findings and insights

## Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scipy

## Usage

Open the notebook in Jupyter:
```bash
jupyter notebook hockey_travel_analysis.ipynb
```

## Author

Perry Gregg

## License

MIT
