# Picking the chart

Choose the comparison first. The chart is whatever makes that comparison
easiest to read.

| What you are showing | Use | Avoid |
| --- | --- | --- |
| A value changing over time | Line (many periods) or column (few periods) | Area charts, which hide the lower series |
| What drove a change between two numbers | Waterfall / bridge | A before-and-after pair of bars, which makes the reader do the subtraction |
| Parts of a whole, one period | Stacked bar, or a sorted bar of the parts | Pie charts above three slices; donuts always |
| Parts of a whole, over time | 100% stacked column | Stacked area with more than four series |
| Two dimensions at once (share × size) | Mekko / marimekko | Bubble charts, which are hard to read by area |
| Ranking | Horizontal bar, sorted descending | Vertical bars with rotated labels |
| Distribution | Histogram or box plot | Averages presented alone |
| Correlation | Scatter, with the outliers labelled | Dual-axis line charts, which can imply any relationship you like |
| Progress against a target | Bullet chart or a bar with a target marker | Gauges and speedometers |
| A single important number | Just the number, large, with its comparison beside it | A one-bar bar chart |

## Rules that apply to all of them

- Zero baseline on anything with bars. Always.
- Direct labels on the series being discussed; legend only when you have
  four or more series and cannot label them in place.
- Sort by value unless the categories have a natural order.
- Units in the axis title, not repeated on every label.
- Grey out the series you are not talking about. One accent colour for the
  one you are.
- If the chart needs more than one sentence of explanation, it is the wrong
  chart.

## Dual axes

Avoid them. If you genuinely need two scales, index both series to 100 at
the first period and use one axis. If that loses the point, use two charts
stacked with a shared x-axis.
