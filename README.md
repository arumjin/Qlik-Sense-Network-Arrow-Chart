# Qlik-Sense-Network-Arrow-Chart
Qlik Sense Network Arrow Chart


Dimensions
1. Node identifier: This dimension controls which nodes are presented in the chart.
2. Node label: This dimension sets the label of each node.
3. Node parent: This dimension sets the parent of a node, and controls the relationships between nodes. It needs to contain the value of the node identifier of the parent to connect to.
4. Node group (Color): You can use this dimension to group nodes. All nodes in the same group will have the same color.


You can use up to three measures to enhance the diagram. All measures are optional, but you need to add them in the following order:
1. Tooltip: You can set a measure value that is displayed in a tooltip when hovering over a node.
2. Node size: You can set the size of the node according to a measure.
3. Edge size: You can set the width of the lines between nodes according to a measure.
