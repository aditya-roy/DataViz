# DataViz
CA1: https://tinyurl.com/viz-ca1
CA2: https://tinyurl.com/viz-ca2
Multidimensional tech: https://tinyurl.com/viz-types

Force-based graph : Proximity is based on strength. It’s a graph so it’s relationship based.
Input : Graph
Useful : The algorithm is able to identify some predefined regular substructures like chains, stars, cycles, and parallel structures and arrange them in an optimized manner.
Advantage : Suppose 2 text documents are completely different, then the distance will be too large. But the distance is measured in such a way that it puts a limit on the largest distance so that extremely large distances can be represented effectively.
Disadvantage : Projection technique is fast but lacks precision.
Application : network visualization, large graph visualization, knowledge representation, system management, or mesh visualization. It is used to visualize the connections between objects in a network.

Input : tree data structure
Useful for representing hierarchies. Eg Phylogenic trees
Observations provided : relationships between various points. Parent child relationship. Evolutionary details.
Application : Treemaps are often used for sales data, as they capture relative sizes of data categories, allowing for quick perception of the items that are large contributors to each category. Color can identify items that are underperforming (or overperforming) compared to their siblings from the same category.
Disadvantage : In a treemap, as we go down the hierarchical levels, the space available to plot decrease dramatically. This sets a limitation to the number of hierarchical levels that can be displayed at once. As the categories delve deeper, they become harder to read. This is good for comparing macro-level data and giving viewers a sense of how many sub-categories there are. But it isn’t really effective when you want to drill down into those sub categories.
Use a treemap to display hierarchical information presented using a tree structure. You can, for instance, use a treemap to show the folder structure of a system. You can also use it to study patterns and occurrences in a large dataset since the color, and the size dimensions are correlated.

Node-link
Input : Graph
Use : A node link diagram is an excellent construct for the many use cases where the key questions are around identifying and understanding how and whether entities are connected.
Node link diagrams are extremely useful in use cases such as intelligence analysis (e.g., one person is an associate of a suspect or known criminal), fraud detection (e.g., the same social security number was used by different people), and many others.
Advantage : significantly better performance for the two network connectivity tasks-identifying the number of clusters and finding a path between two nodes-than the other two representations.
Disadvantage : In an ideal situation, nodes are automatically placed into positions that allow the user to simply group them visually into clusters on the basis of their proximity and thereby deliver new knowledge about network structure, which would not be possible without such representation. Unfortunately, in most cases, this is not possible - many network datasets are so complex that their graph visualization looks like a "hairball", where the nodes are no longer able to be positioned according to the proximity rule. 
Application : Network analysis

