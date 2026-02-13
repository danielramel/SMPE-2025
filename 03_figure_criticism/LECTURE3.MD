Visualization and Exploratory Data Analysis


Common problems:
- too much information (chartjunk)
- causation vs correlation
- inappropriate chart types
- misleading axes and scales (truncated Y-axis, dual Y-axis)
- lack of context and annotations
- missing confidence intervals


Key lesson: Use checklist:
    Data - Chart type, interpolation, confidence intervals
    Graphical Objects - Readability, colors, axes, scales
    Annotations - Labels, units, legends
    Information - Scale consistency, data density, relevance
    Context - Title, self-containment, source citation



Good Graphics Critique:
[Criticism of 4 figures](./homework.md)


## Challenger Analysis: What went wrong with the Challenger data visualization ##

- Selection bias: excluded positive results >> misleading conclusion about O-ring performance
- Not using trial counts: only showing failure rates without context of total launches >> overemphasizing risk
- Small sample size >> unreliable p-values and confidence intervals
- independence assumption violated: multiple O-rings per launch >> the data points are not independent, leading to underestimated variability and overconfident conclusions
- extrapolation beyond data range >> making predictions about O-ring performance at temperatures not observed in the data



