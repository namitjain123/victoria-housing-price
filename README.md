# Victoria Housing Price Analysis

A comprehensive Power BI analysis of Victorian property market trends from 2004 to 2025, tracking housing prices across different council regions and property types.

## 📊 Project Overview

This project analyzes historical housing price data across Victoria, Australia, providing insights into:
- **Price Trends**: Median and mean property prices by council area and year
- **Market Growth**: Year-over-year price growth analysis
- **Regional Comparisons**: Housing market performance across different Victorian regions
- **Long-term Index**: Price indices based on 2004 as the baseline year

## 📁 Files

| File | Description |
|------|-------------|
| `melbourne_council_property.csv` | Main dataset containing property sales and pricing metrics (2004-2025) |
| `victoria_council_property_2004_2025.xlsx` | Extended Excel file with additional worksheets |
| `sheet 1.png` - `sheet3.png` | Power BI dashboard previews/screenshots |

## 📈 Dataset Structure

### Columns in `melbourne_council_property.csv`

| Column | Description |
|--------|-------------|
| **Council** | Local council area in Victoria |
| **Region** | Regional classification (Metropolitan/Regional Victoria) |
| **Year** | Calendar year (2004-2025) |
| **PropertyType** | Type of property (e.g., House, Unit, etc.) |
| **NumSales** | Number of property sales recorded |
| **MedianPrice** | Median sale price for the period |
| **MeanPrice** | Average sale price for the period |
| **YoY_Median_Growth_Pct** | Year-over-year percentage change in median price |
| **Median_Index_2004base** | Price index with 2004 as base year (100) |
| **IsAggregate** | Boolean flag for aggregated data |
| **IsPreliminary** | Boolean flag for preliminary/incomplete data |

## 🔍 Key Insights

- Data spans **21 years** (2004-2025), capturing multiple housing market cycles
- Covers all Victorian councils across **Metropolitan** and **Regional Victoria**
- Includes both median and mean price metrics for comprehensive analysis
- Year-over-year growth rates enable trend analysis and market volatility assessment
- Index values allow easy tracking of long-term property value appreciation

## 📊 Power BI Dashboards

The project includes Power BI visualizations (see screenshots):
- **Sheet 1**: Overall market overview and regional comparisons
- **Sheet 2**: Price trends and growth analysis
- **Sheet 3**: Detailed council-level insights

## 🚀 How to Use

1. **Explore the Data**: Open the CSV or XLSX file in Excel or Power BI
2. **View Dashboards**: Check the PNG previews for visualization examples
3. **Analyze Trends**: Filter by region, council, or property type
4. **Track Growth**: Use YoY growth percentages to identify trending markets
5. **Compare Markets**: Use index values to compare long-term appreciation

## 💡 Analysis Applications

- Market trend forecasting
- Investment opportunity identification
- Regional economic indicators
- Property valuation benchmarking
- Real estate portfolio analysis

## 📝 Notes

- Some entries marked as `IsPreliminary=TRUE` may be updated with final data
- Aggregate data entries include combined metrics across multiple property types/categories
- Price data reflects actual sales transactions in each council area

---

**Data Source**: Victorian council property sales records (2004-2025)  
**Last Updated**: 2026  
**Format**: CSV, XLSX, Power BI Dashboard
