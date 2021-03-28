# GoT analysis using Graph_Theory

For this analysis, the network data was taken from the source https://github.com/mathbeveridge/asoiaf. These networks were created by connecting two characters whenever their names (or nicknames) appeared within 15 words of one another in one of the books in "A Song of Ice and Fire." The edge weight corresponds to the number of interactions.

In this notebook we have analysed:

1. Which characters are the most important in Books 1 through 5 using Degree Centrality and BetweenNess Centrality
2. Maximal Clique analysis is done on one character to understand which "community" of other characters he/she has most interaction with.
3. PyVis has been used to visualise the Network
