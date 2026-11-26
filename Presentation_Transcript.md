# Presentation Transcript

Timestamped presentation transcript for [`IT_Expenditure_Analysis_Presentation.mp4`](./IT_Expenditure_Analysis_Presentation.mp4). Source dataset: Microsoft IT Spend Analysis Sample (*obviEnce ©*).

## 00:00:00.000 — IT expenditure: where the budget gap sits

This Power BI sample shows IT spending 5.85 percent above plan. Infrastructure is the clearest area for investigation. This presentation follows the figures from the overall budget gap to regional costs, forecast accuracy, and the accounting checks needed before acting.

## 00:00:19.042 — Monitor costs and make budget owners accountable

The business challenge is to monitor IT costs and explain deviations early. Actual expenditure shows what was recorded. The plan is the original budget, while each latest estimate is a separate forecast snapshot. Comparing all three supports budgeting and accountability without adding the scenarios together.

## 00:00:38.500 — The scope is a public Power BI sample

The analysis uses Microsoft's public IT Spend Analysis sample, with data credited to obviEnce. It covers 2014 and contains 166,216 fact records. The video combines original Power BI report images with charts recalculated from the model.

## 00:00:58.417 — Check the source before explaining the result

The Excel source and the PBIX fact totals match. Preparation checks found no null fact fields, no exact duplicate rows, and no unmatched dimension keys. Numeric keys and dates were standardized for analysis. Negative and zero values were retained because deleting them would change the reported costs.

## 00:01:18.750 — Keep scenarios and reporting dimensions separate

The model connects one fact table to seven reporting dimensions. These active relationships are many to one and use single direction filtering. Scenario separates actuals from the plan and forecasts. IT Area and Business Area are different dimensions, even when both contain a label called Infrastructure.

## 00:01:38.917 — Match the report’s calculation and units

The source Amount measure calculates year to date cost and applies a factor of 0.3. This analysis preserves that factor so the results match the Power BI report. Comparing unscaled Excel sums with the report cards would create an avoidable mismatch.

## 00:01:55.750 — Define the sign of variance clearly

Plan variance is actual cost minus planned cost. A positive result therefore means cost above plan. Dividing by the plan gives the percentage variance when the baseline is meaningful. Missing plan records and negative planning adjustments need separate flags before their percentages are used for ranking.

## 00:02:15.167 — The full-year result exceeds the annual budget

Full year actual cost is $257.53 million. The original plan is $243.29 million. The difference is $14.24 million, or 5.85 percent above plan, across the full model scope.

## 00:02:32.083 — Review the timing of the budget gap

The trend view compares cumulative actual spend with the plan and the third latest estimate. Each point includes earlier months, so these lines should not be read as individual monthly spending. By December, the gap to the original plan reaches $14.24 million.

## 00:02:49.708 — Spend concentration helps set the review order

Functional is the largest IT area by actual cost, at $79.72 million. BU Support and Infrastructure follow at about $75 million each. This distribution sets the scale, while the variance comparison shows which large areas are exceeding their budgets.

## 00:03:08.625 — Infrastructure is the main IT-area exception

Infrastructure IT area reports $74.98 million of actual cost against a plan of $50.66 million. That is $24.32 million above plan, or about 48 percent. The underlying adjustments and subareas deserve review before selecting a response.

## 00:03:28.417 — The net gap hides larger offsetting differences

Infrastructure's variance is larger than the organization's net budget gap. The other IT areas are collectively about $10.08 million below plan. These offsets reduce the total variance to $14.24 million. A single headline percentage would hide that difference.

## 00:03:46.750 — Prioritize the largest financial exposure

The United States accounts for about 84.4 percent of actual expenditure. It is $12.89 million above plan, while Europe is about $2.13 million above. Europe has a slightly higher percentage variance, but the United States has the larger financial impact.

## 00:04:06.667 — Below plan needs an operating explanation

Canada and Latin America are each about 13 percent below plan. Australia and New Zealand are about 7 percent below. These results could reflect savings or work that moved to another period. Service output and project delivery records are needed before calling the difference underutilization.

## 00:04:25.583 — Labor is the largest cost element group

Labor is the largest actual cost group at $136.64 million. It represents about 53.1 percent of net actual cost. Depreciation and amortization follow, then hardware and software. Cost concentration identifies where contract and staffing reviews could have the greatest reach.

## 00:04:47.625 — Labor and Shared Services are both below plan

Shared Services records about $437 thousand against a plan of $1.048 million. That is 58.3 percent below plan. Labor is also below plan, by about 2.3 percent. Confirm service volumes and allocation rules before treating either result as a repeatable saving.

## 00:05:09.125 — Forecast alignment differs from budget alignment

The third latest estimate is $260.09 million. Actual cost finishes about $2.57 million lower, a difference of roughly 1 percent. The second estimate is closer to the final actual, so later forecasts should still be checked for error.

## 00:05:27.083 — Networking is a specific subarea to investigate

Networking reports $15.19 million of actual cost against a plan of $8.63 million. The gap is about $6.55 million, or 75.9 percent. Review approved scope changes and vendor contracts to explain the difference, rather than assuming a cause from the chart.

## 00:05:47.417 — Treat accounting exceptions explicitly

The Administrative cost group has negative planning adjustments and no actual scenario records. Core Infrastructure also has a negative plan total. Africa and Asia have actual records without an original plan. These cases need reconciliation, and ordinary positive budget percentages would give a misleading ranking.

## 00:06:08.417 — The Power BI pages support the drilldown

The original Power BI report provides trend, cost element, and plan variance pages. In a live review, begin with the same year and cost scope, select a region, then an IT area and subarea. The filters support exploration, while these presentation images show fixed selections.

## 00:06:28.208 — Similar labels can describe different dimensions

The plan variance page shows about 44.4 percent for the Infrastructure Business Area selection. The Infrastructure IT Area comparison was about 48 percent. Those figures use different dimensions. Naming the dimension and checking selections prevents the two results from being confused.

## 00:06:48.000 — Make each Power BI interaction answer a question

A repeatable review moves from the overview to a region, then an IT area, subarea, and cost group. Use the month filter to test timing. Keep the measures reusable, sort months by their period number, and reconcile the headline cards after changes to the reporting scope.

## 00:07:06.458 — Turn findings into accountable follow-up

The budget owner should reconcile Infrastructure adjustments and investigate Networking. Regional owners should start with the United States, then Europe. Service owners should validate below plan spending against delivered work. Finance should track forecast error and budget variance over time, with named owners for each explanation.

## 00:07:27.917 — Close the loop from transparency to decisions

The organization is 5.85 percent above its annual plan, while actual cost is close to the third latest estimate. The strongest review combines financial impact with detailed scope checks. Follow the major drivers, validate exceptions, and use the same measures to judge the next reporting cycle.
