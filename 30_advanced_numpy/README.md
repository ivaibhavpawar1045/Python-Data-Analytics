# Day 30 — Advanced NumPy

## Topics Covered
          - `reshape()`
          - `flatten()`
          - Boolean operations
          - `np.where()`
          - `np.select()`
          - Broadcasting
          - NumPy with Pandas
          - `np.maximum()`
          - Regional KPI calculations

## 1. Array Reshaping
          - Reshaped 12 sales observations into arrays with different dimensions and calculated regional totals.

## 2. Boolean Operations
          - Filtered sales using combined conditions and classified observations into business categories.

## 3. Broadcasting
          Applied different sales adjustment rates:
          - Region A: 10%
          - Region B: 5%
          - Region C: 15%

## 4. Regional Performance

          | Region | Total Sales | Contribution |
          |---|---:|---:|
          | Region A | 5,600 | 28.79% |
          | Region B | 5,050 | 25.96% |
          | Region C | 8,800 | 45.24% |

## 5. Target Analysis
          Target per region: 6,000

          - Region A: Below Target; gap 400
          - Region B: Below Target; gap 950
          - Region C: Target Achieved; gap 0

## 6. Sales Projection
          Assumption: sales increase by 10% in every region.

          - Current total sales: 19,450
          - Projected total sales: 21,395
          - Projected increase: 1,945

## Business Insight
          Region C currently leads in sales and has achieved the target. Region B has the largest target gap and should be prioritized for improvement.

          The 10% increase is a scenario assumption, not a guaranteed forecast.

## Skills Practiced
          NumPy, array manipulation, Boolean filtering, broadcasting, conditional classification, Pandas integration and business KPI analysis.
