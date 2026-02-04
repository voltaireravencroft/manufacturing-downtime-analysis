# manufacturing-downtime-analysis
Analysis of production line efficiency, downtime factors, and operator performance for a soda bottling facility.
# Manufacturing Line Downtime Analysis

## Overview
Analysis of production line efficiency and operator performance for a soda bottling facility, identifying key downtime factors and operator-specific error patterns.

## Business Questions
1. What's the current line efficiency?
2. Are any operators underperforming?
3. What are the leading factors for downtime?
4. Do any operators struggle with particular types of errors?

## Analysis Results

### 1. What's the current line efficiency?
**67.1% overall efficiency**, with the line running at theoretical capacity when actively producing. All efficiency loss (33%) is attributable to downtime events, representing significant recovery potential.

### 2. Are any operators underperforming?
Yes. **Mac is the lowest performer at 63.3% efficiency** with 41.5 minutes average downtime per batch, compared to top performer **Charlie at 71.0% efficiency** with 34.9 minutes average downtime. This represents a 7.7 percentage point performance gap.

### 3. What are the leading factors for downtime?
- **Product Spill (338 minutes)** - Operator error, #1 cause
- **Machine Failure (261 minutes)** - Equipment issue
- **Inventory Shortage (229 minutes)** - Supply chain issue

### 4. Do any operators struggle with particular types of errors?
Yes, clear patterns emerged:
- **Mac:** Struggles with Batch Changes (130 min) and Batch Code Errors (47 min)
- **Charlie & Dennis:** Both struggle with Machine Adjustments (118 and 120 min respectively)
- **Dee:** Shows distributed errors across multiple categories with no single dominant issue

## Tools Used
- Microsoft Excel
- Data analysis: VLOOKUP, SUMIF, AVERAGEIF
- Visualization: Column charts, stacked bar charts

## Files
- `Manufacturing_Line_Productivity.xlsx` - Full analysis with Dashboard tab

## Recommendations
Immediate Actions (0-30 days):

Implement spill prevention training for all operators, focusing on handling procedures during product changeovers and transfers. This addresses the #1 downtime cause (338 minutes).
Provide targeted coaching to Mac on batch change procedures and coding protocols. Consider pairing Mac with Charlie for shadowing/mentorship on these specific tasks.
Schedule machine operation refresher training for Charlie and Dennis, focusing on proper adjustment techniques to reduce the 238 combined minutes lost to this error type.

Short-term Actions (30-90 days):

Conduct root cause analysis on machine failures (261 minutes) - determine if failures are preventable through better preventive maintenance or operator handling.
Review inventory management processes with supply chain team to address the 229 minutes lost to shortages. Implement buffer stock or improved forecasting.
Establish operator performance metrics dashboard to track efficiency and downtime patterns on an ongoing basis, enabling early intervention when performance degrades.

Long-term Strategic Actions (90+ days):

Develop standardized work procedures for all high-error tasks, particularly batch changes and machine adjustments, incorporating best practices from top performers.
Implement a continuous improvement program with monthly operator reviews focused on error reduction and efficiency gains.
