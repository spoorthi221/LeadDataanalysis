# LeadDataanalysis

# 📊 Lead Quality Analysis Tool

A comprehensive data analysis tool for evaluating lead quality, tracking performance metrics, and identifying improvement opportunities in marketing campaigns.

## 🎯 Key Features

- **Exploratory Data Analysis (EDA)**
  - Basic data statistics and distributions
  - Missing value analysis
  - Call status breakdowns
  - Visual representation of key metrics

- **Lead Trend Analysis**
  - Monthly quality trends
  - Conversion rate tracking
  - Statistical correlation analysis
  - Time-series visualizations

- **Performance Drivers**
  - Widget performance analysis
  - Debt level impact assessment
  - Quality rate calculations
  - Cost per lead optimization

## 📈 Analysis Components

### 1. Initial Data Exploration
```python
perform_eda(df)
```
- Generates comprehensive data overview
- Creates visual distributions
- Identifies data patterns and anomalies

### 2. Lead Quality Trends
```python
analyze_lead_trends(df)
```
- Tracks quality metrics over time
- Calculates conversion rates
- Performs statistical tests
- Visualizes trend patterns

### 3. Quality Drivers Analysis
```python
analyze_widget_performance(df)
analyze_debt_levels(df)
```
- Evaluates widget effectiveness
- Assesses debt level impact
- Calculates performance metrics
- Creates comparative visualizations

### 4. Improvement Analysis
```python
calculate_base_metrics(df)
analyze_improvement_opportunities(df)
```
- Current vs target metrics
- Cost optimization strategies
- Performance improvement paths
- ROI calculations

## 🛠️ Requirements

```python
pip install pandas numpy matplotlib seaborn scipy
```

## 📊 Sample Output

The analysis provides:
- Quality rate trends
- Performance breakdowns
- Cost analysis
- Improvement recommendations

## 🚀 Getting Started

1. Prepare your data:
```python
df = pd.read_excel('lead_data.xls')
```

2. Run initial analysis:
```python
perform_eda(df)
trends = analyze_lead_trends(df)
```

3. View improvement opportunities:
```python
main()  # Runs complete analysis pipeline
```

## 📝 Notes

- Minimum 30 leads required for widget analysis
- Default CPL set to $30
- Target quality rate improvement: 20%
- Customizable thresholds and metrics

## 🤝 Contributing

Found ways to improve the analysis? PRs welcome! Please include:
- Clear description of changes
- Updated documentation
- Test results if applicable

---

Built with Python and data science best practices. For questions or suggestions, please open an issue.
