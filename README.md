📊 PROJECT OVERVIEW

Comprehensive retail sales analysis using Pivot Tables, XLOOKUP, Power Query, 
and advanced Excel formulas to uncover customer segments, spending patterns, 
and sales trends.

Dataset: 10,000+ retail transactions
Categories: 5 product categories
Timeframe: 12 months

🎯 KEY QUESTIONS ANSWERED

1. Which customer demographics drive the most revenue?
   Finding: Female customers (62% of transactions) have 18% higher average 
   order value ($156 vs $132 for males).

2. When do customers shop most?
   Finding: Friday-Saturday peak: 42% of weekly revenue. Tuesday lowest traffic: 
   12% of weekly revenue.

3. Which age groups are most valuable?
   Finding: Age 25-35 segment generates 45% of revenue from only 28% of 
   customers. Age 50+ lower frequency but higher transaction value.

4. Which product categories have highest ROI?
   Finding: Electronics (22% margin), Fashion (18% margin), Home (12% margin).

🛠️ DATA CLEANING PROCESS

Raw Data Problems:
  • 40% missing values in customer age field
  • Duplicate order records (same order ID, different rows)
  • Date format inconsistency (DD/MM/YYYY vs MM/DD/YYYY)
  • Product category typos ("Electonics" vs "Electronics")
  • Negative values in sales amounts (likely returns, not marked)

Data Cleaning Steps (Power Query):
  • Removed 245 duplicate records using "Remove Duplicates"
  • Used Find & Replace to standardize category names
  • Separated date column into separate Month/Year columns
  • Created conditional formula to handle missing ages (used median by category)
  • Flagged negative sales as "Returns" for separate analysis
  • Validated cleaned dataset: 100% non-null key fields

  🛠️ ANALYSIS TOOLS & FORMULAS USED

Pivot Tables:
  • Revenue by Customer Demographics (Age, Gender, Location)
  • Sales by Product Category (Volume, Revenue, Margin)
  • Trend analysis by Month and Day of Week

Excel Formulas Used:
  • XLOOKUP: Match customer IDs to demographic data
  • SUMIF: Revenue by category, gender-wise breakdowns
  • AVERAGEIFS: Avg order value by multiple criteria
  • COUNTIFS: Customer count by segment
  • Conditional Formatting: Color-coded performance tiers

Dashboard Components:
  • Summary KPI cards: Total Revenue, Avg Order Value, Customer Count
  • Pie chart: Revenue breakdown by gender
  • Stacked bar: Weekly sales pattern
  • Line chart: Month-over-month revenue trend
  • Heatmap: Day-hour traffic patterns

  💡 BUSINESS INSIGHTS & RECOMMENDATIONS

Insight 1: Gender-Based Spending Behavior
  • Female customers: Higher transaction frequency (1.4x) AND higher order 
    value (18% higher)
  • Average Female Order: $156
  • Average Male Order: $132
  • Recommendation: Create female-targeted marketing campaigns; stock more 
    products women buy (Fashion, Beauty)

Insight 2: Day of Week Pattern
  • Friday-Saturday: 42% of weekly revenue
  • Tuesday: 12% of weekly revenue
  • Recommendation: Increase staffing 25% on weekends; run promotions on 
    Tuesday to drive traffic

Insight 3: Age Segment Value
  • Age 25-35: 45% revenue, 28% of customers (highest value density)
  • Age 18-24: High frequency, low order value
  • Age 50+: Low frequency, highest order value per transaction
  • Recommendation: Target 25-35 with premium products; engage 50+ with 
    loyalty rewards

Insight 4: Product Category Performance
  • Electronics: 22% margin, seasonal spikes in Dec/Jan
  • Fashion: 18% margin, steady demand
  • Home: 12% margin, correlated with age 45+ segment
  • Recommendation: Stock Electronics heavily before holiday; promote Fashion 
    to 25-35 demographic

    📈 IMPACT

✓ Marketing team used segment insights to create targeted campaigns
✓ Female customer retention increased by 12% through targeted marketing
✓ Weekend staffing recommendations increased sales per employee by 8%
✓ Identified $80K+ in untapped revenue opportunities from underserved segments
