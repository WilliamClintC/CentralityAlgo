# Centrality
Centrality as a basis for stock selection

This project consist of inputing 10 stocks and a date range. The code constructs a return covariance matrix between these 10 stocks on the specified date range.
The code then converts this covariance matrix into a network. The network centrality algorithm is then applied to find the center most node. After the center
most node is found, the code uses this information to trade the node/stock the following day, weighted accordingly by the centrality of the previous data range. 
The output is the nominal return of the strategy. 
