---
default: undefined
acceptValues: 'discrete' | 'continuous' | 'logarithmic'
type: String
---
---
##### shortDescription
Specifies the required type of the argument axis.

---
The 'discrete' type is set when string arguments are specified in the data source of the chart's series. The discrete axis is divided by the values (called _categories_) that are specified as arguments in the data source. The categories order can be specified by the [categories](/api-reference/20%20Data%20Visualization%20Widgets/dxPolarChart/1%20Configuration/argumentAxis/categories.md '/Documentation/ApiReference/Data_Visualization_Widgets/dxPolarChart/Configuration/argumentAxis/#categories') property, if the order used in the data source is not appropriate.

The 'continuous' type is set when numeric or date-time arguments are specified in the series data source. The continuous axis is divided automatically.

The 'logarithmic' type can be set when numeric values are specified in the series data source. The logarithmic axis is useful when you visualize a dataset of rapidly-growing values. Each axis tick represents a particular value that is raised to the next power in turn. This particular value is specified by the [logarithmBase](/api-reference/20%20Data%20Visualization%20Widgets/dxPolarChart/1%20Configuration/argumentAxis/logarithmBase.md '/Documentation/ApiReference/Data_Visualization_Widgets/dxPolarChart/Configuration/argumentAxis/#logarithmBase') option. For example, if you set this option to 5, the following ticks will be generated: 5<sup>0</sup>, 5<sup>1</sup>, 5<sup>2</sup>, 5<sup>3</sup> etc.

On continuous and logarithmic axes, ticks and grid lines are positioned so that their labels do not overlap each other. In addition, you can set a custom tick interval (the [tickInterval](/api-reference/20%20Data%20Visualization%20Widgets/dxPolarChart/1%20Configuration/argumentAxis/tickInterval '/Documentation/ApiReference/Data_Visualization_Widgets/dxPolarChart/Configuration/argumentAxis/tickInterval/') or [axisDivisionFactor](/api-reference/20%20Data%20Visualization%20Widgets/dxPolarChart/1%20Configuration/argumentAxis/axisDivisionFactor.md '/Documentation/ApiReference/Data_Visualization_Widgets/dxPolarChart/Configuration/argumentAxis/#axisDivisionFactor') options).

[note] If you require a discrete axis when numeric or date-time arguments are specified in the data source, set the **type** option to 'discrete' explicitly.

When configuring the widget using [ASP.NET MVC Wrappers](/concepts/35%20ASP.NET%20MVC%20Wrappers/20%20Fundamentals '/Documentation/Guide/ASP.NET_MVC_Wrappers/Fundamentals/'), specify this option using the `AxisScaleType` enum. This enum accepts the following values: `Discrete`, `Continuous` and `Logarithmic`.