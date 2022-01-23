# Warehouse_Locator
- This is a Meta-Heuristics algorithm to solve TSP and FLP by using SA, K-Opt and savings algorithm (clarke & wright)

## Introduction 
###  Traveling Salesman Problem (TSP)
The TSP is a classic problem in discrete or combinatorial optimization that belongs to the NP-complete classes, which means that solving it with an exhaustive search method may be infeasible, so less expensive heuristics in terms of processing time are commonly used to obtain satisfactory solutions in a short running time. The TSP is mainly categorized into two kinds: symmetric travelling salesman problems (sTSP) and asymmetric travelling salesman problems (aTSP).

###  Facility Location Problem (FLP)
The FLP is one of the most important models in combinatorial optimization, which is to determine the number and locations of the facilities and allocate customers to these facilities in such a way that the total cost is minimized. The FLP may be the most critical and most difficult decision in the designing of an efficient supply chain for the facilities to reduce cost of opration.

### Simulated Annealing (SA)
It's a probabilistic technique for estimating a function's global optimum. Simulated annealing approach is based on physics annealing laws. The basic idea behind simulated annealing is to heat a solid to its maximum temperature and then slowly cool it. As the temperature rises inside the solid particles, the form becomes disordered, and internal energy increases. As the temperature slowly cools, the temperature reaches equilibrium in each state, and eventually reaches the ground state at room temperature, which can be reduced to the minimum. 

### Savings Algorithm (clarke & wright)
The fundamental savings idea explains the cost savings realised by combining two routes into one, as seen below, with point 0 representing the depot.
<div align="center"><img width="290" alt="Screen Shot 2022-01-23 at 5 27 49 PM" src="https://user-images.githubusercontent.com/74301587/150700478-f7048352-ccab-4da9-b3d7-b8a7d82ce19b.png"></div>

Customers I and j are first visited on distinct routes in figure (a). Another option is to visit both customers on the same route, such as in the sequence i-j as shown in Figure (b). The savings that arise from driving the route in figure (b) instead of the two routes in figure (a) may be estimated because the transportation expenses are known. The total transportation cost Da in figure (a) is calculated by denoting the cost of transportation between two specified places I and j by cij:
<div align="center"><img width="160" alt="Screen Shot 2022-01-23 at 5 32 21 PM" src="https://user-images.githubusercontent.com/74301587/150700633-fed4a285-c8cc-4413-818e-c1d9edaa8dc3.png"></div>

Db in figure (b) is equivalent to: 
<div align="center"><img width="121" alt="Screen Shot 2022-01-23 at 5 37 06 PM" src="https://user-images.githubusercontent.com/74301587/150700774-8b482eb9-1dd9-4433-a7e5-0700531b3ce6.png"></div>

Savings are obtained by merging the two routes Sij:
<div align="center"><img width="186" alt="Screen Shot 2022-01-23 at 5 38 22 PM" src="https://user-images.githubusercontent.com/74301587/150700805-71a9f099-5b1d-4b5b-ae32-d60bb2e9b0fd.png"></div>









