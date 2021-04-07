# Qlik-Sense-Network-Arrow-Chart
Qlik Sense Network Arrow Chart
![network](https://user-images.githubusercontent.com/7877793/113825861-72c39c00-97bc-11eb-8a39-3f9b36b55dc6.png)

Based on library vis.js (http://visjs.org)
https://github.com/miclae76/network-vis-chart

##Dimensions
1. Node identifier: This dimension controls which nodes are presented in the chart.
2. Node label: This dimension sets the label of each node.
3. Node parent: This dimension sets the parent of a node, and controls the relationships between nodes. It needs to contain the value of the node identifier of the parent to connect to.
4. Node group (Color): You can use this dimension to group nodes. All nodes in the same group will have the same color.

##Measures
1. Tooltip: You can set a measure value that is displayed in a tooltip when hovering over a node.
2. Node size: You can set the size of the node according to a measure.
3. Edge size: You can set the width of the lines between nodes according to a measure.

##
