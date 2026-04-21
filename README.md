# Experiment-19

## Aim: -To explore, understand, and implement advanced, real-world data visualization techniques using Python libraries such as Plotly, Matplotlib, and SciPy to extract meaningful insights from complex datasets.
## Theory: -
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data. This experiment focuses on five advanced visualization techniques
Treemap: A visualization that displays hierarchical data as a set of nested rectangles. Each group is represented by a rectangle, which area is proportional to its value. In this experiment, it is used to visualize departmental budgets (HR, IT, Sales, Marketing), making it easy to compare resource allocation at a glance.
Dendrogram: A tree-like diagram that records the sequences of merges or splits in hierarchical clustering. It illustrates how data points are grouped based on similarity or distance. We utilized scipy.cluster.hierarchy to calculate the Euclidean distances and group sample data points using Ward's method.
Venn Diagram: A diagram representing mathematical or logical sets pictorially as circles or closed curves within an enclosing rectangle. Elements common to two or more sets are represented by intersections of the circles. Using matplotlib_venn, we visualized the overlapping relationships between two defined data sets.
Sankey Diagram: A type of flow diagram where the width of the arrows is proportional to the flow rate. They are highly effective at showing the transfer of resources, energy, or entities. Here, a Sankey diagram models the "Student Flow" through different stages: Admission → First Year → Second Year → Placed.
3D Scatter Plot: An extension of the standard 2D scatter plot that plots data points on three axes (x, y, and z) to show the relationship between three distinct numerical variables. Using plotly.express, we visualized student performance by comparing Study Hours, Marks, and Attendance simultaneously in an interactive 3D space.

Technologies & Libraries Used
Python 3

Pandas: For data manipulation and DataFrame creation.

Plotly (plotly.express, plotly.graph_objects): For creating interactive plots like Treemaps, Sankey Diagrams, and 3D Scatter Plots.

Matplotlib (matplotlib.pyplot): For rendering static visualizations.

SciPy (scipy.cluster.hierarchy): For mathematical computations and generating linkage matrices for the Dendrogram.

Matplotlib-Venn: For rendering the Venn Diagram.

## Conclusion
In this experiment, we successfully implemented and analyzed multiple advanced data visualizations. Static plots like Dendrograms and Venn diagrams proved effective for illustrating relationships and set overlaps, while interactive tools like Plotly provided dynamic, easily navigable visual insights for hierarchical structures (Treemaps), process flows (Sankey diagrams), and multi-dimensional correlations (3D Scatter Plots).
