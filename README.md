# Centrality
Centrality as a basis for stock selection

This project consist of inputing 10 stocks and a date range. The code constructs a return covariance matrix between these 10 stocks on the specified date range.
The code then converts this covariance matrix into a network. The network centrality algorithm is then applied to find the center most node. After the center
most node is found, the code uses this information to trade the node/stock the following day, weighted accordingly by the centrality of the previous data range. 
The output is the nominal return of the strategy. 

Below is a sample covariance matrix output
![output](https://github.com/WilliamClintC/CentralityAlgo/assets/118032486/b5c7009c-8172-464f-946d-161954c5b4b2)

Below is a sample Network
![1](https://github.com/WilliamClintC/CentralityAlgo/assets/118032486/5446ab2f-6138-4da4-8c5d-2144822eabf1)

Below is a sample Numerical Centrality output
<img width="134" alt="Screenshot 2023-05-21 152504" src="https://github.com/WilliamClintC/CentralityAlgo/assets/118032486/3011d505-301d-4511-8708-3e28f6bcf0a7">

Bwlow is sample Return Output
<img width="172" alt="Screenshot 2023-05-21 152547" src="https://github.com/WilliamClintC/CentralityAlgo/assets/118032486/4e6b49b9-8818-4fcf-94d6-c84b60de6880">
