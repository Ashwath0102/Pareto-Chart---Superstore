# Pareto Chart Analysis: Revenue Concentration Risk in Retail Business

![Tableau](https://img.shields.io/badge/Tableau-Visualization-orange)
![Business Analytics](https://img.shields.io/badge/Business-Analytics-blue)
![Pareto Analysis](https://img.shields.io/badge/Analysis-Pareto%2080/20-green)

A comprehensive implementation of Pareto chart analysis in Tableau to evaluate revenue concentration risk and business diversification using the Superstore dataset.

## Project Overview

This project demonstrates the construction and application of Pareto charts in Tableau to analyze revenue concentration and assess adherence to the 80/20 principle. The analysis provides insights into business risk exposure and strategic planning for resource allocation.

## Objectives

- Quantify and visualize revenue dependency using Pareto analysis
- Assess adherence to the 80/20 principle in retail sales data
- Identify revenue concentration risks and diversification opportunities
- Create an interactive dashboard for business decision-making

## Dataset

**Source:** [Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

**Key Features:**
- Order ID, Product Name, Category, Sub-Category
- Customer demographics and geographic segments
- Sales, Profit, Quantity, Discount measures
- Multi-year transactional records

## Methodology

### Step-by-Step Implementation

<img width="550" height="813" alt="image" src="https://github.com/user-attachments/assets/9d041da7-7c82-44c0-84be-f18e1a5254e6" />

1. **Data Preparation**
   - Load Superstore dataset into Tableau
   - Identify Product Name as dimension and Sales as measure

2. **Base Chart Construction**
   - Drag Product Name to Columns shelf
   - Convert to Count Distinct measure
   - Add Sum of Sales to Rows shelf

3. **Table Calculations**
   - Apply Running Total calculation
   - Add Percent of Total calculation
   - Configure calculations using Product Name dimension

4. **Data Sorting**
   - Sort products by Sum of Sales in descending order
   - Ensure proper Pareto curve formation

5. **Reference Lines**
   - Add 20% product threshold on X-axis
   - Add 80% sales threshold on Y-axis
   - Create intersection point for Pareto principle evaluation

## 📊 Results & Findings

<img width="699" height="375" alt="image" src="https://github.com/user-attachments/assets/9e0e2037-59b2-4b6d-b669-18ce9eb48980" />


### Key Insight
- **22.70%** of products generate **80%** of total sales
- Positive deviation from strict 80/20 dependency
- Moderately diversified revenue portfolio

### Business Implications
- **Lower Risk Exposure**: Less vulnerable to market fluctuations
- **Healthy Diversification**: Balanced product portfolio
- **Strategic Advantage**: Reduced dependency on narrow product range

## Quick Start

### Prerequisites
- Tableau Desktop 2022+
- Superstore dataset
- Basic understanding of business analytics

### Implementation Steps
1. Download the Superstore dataset
2. Open Tableau and connect to the data source
3. Follow the methodology steps outlined above
4. Customize reference lines for specific business thresholds


## Business Applications

### Quality Management
- Identify 20% of defect types causing 80% of production errors
- Focus process improvement efforts effectively

### Marketing Optimization
- Pinpoint high-performing channels and campaigns
- Allocate budgets based on performance contribution

### Operational Efficiency
- Analyze IT service desk tickets for common issues
- Enable proactive system maintenance

### Inventory Management
- Identify top-selling products for stock optimization
- Reduce carrying costs for low-performing items

## Key Features

- **Interactive Dashboard**: Dynamic Pareto chart with hover details
- **Benchmark Analysis**: Reference lines for 80/20 principle evaluation
- **Real-time Updates**: Live data connection capabilities
- **Export Functionality**: Share insights across organization

## Technologies Used

- **Tableau Desktop**: Primary visualization tool
- **Superstore Dataset**: Sample retail data
- **Business Intelligence**: Analytical framework
- **Statistical Analysis**: Pareto principle application

## 📚 References

1. [Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
2. [Tableau Pareto Chart Documentation](https://help.tableau.com/current/pro/desktop/en-us/pareto.htm)
3. Playfair Data: 3 Ways to Make Powerful Pareto Charts in Tableau
4. Investopedia: The Pareto Principle (80/20 Rule)

**Note**: This analysis demonstrates how simple visualization techniques can reveal critical business insights for strategic decision-making and risk management.
