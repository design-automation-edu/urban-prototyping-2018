# Iteration 3 Regularized Grid with Primary and Secondary Roads (Bent and Heterogeneous)

## Iteration B
This iteration features simulation based on the same block typology tested on Type 3 Regularized grid with primary and secondary roads, as described in the introduction of the chapter. Iteration 3B features the same typology where the residential tower sits on the commercial podium block, however, the depth and width of the residential block is reduced.


![Figure 12. Block typology and Urban morphology for Iteration 3b](./imgs/iteration_3bv2.png)
Figure 12. Block typology and Urban morphology for Iteration 3b

### Set-up
#### The distribution of residential and commercial area is as follows
* Residential: 22sqm per person
* Commercial: 13sqm per person 
#### Parameters for urban morphology
* Residential storey height: 3m
* Commercial storey height: 5m
* Green connector road 15m
* Green buffer 5m (each side)
* Primary roads 8m
* Secondary roads
* Pedestrian roads 1.5m
* Parks < 500sqm
#### Urban morphology
* Maximum floor count: 22
* Average floor count: 8
* Total number of buildings: 170

### Building Simulation

![Figure 13. Iteration 3b Building simulations](./imgs/eval_3b.png)
Figure 13. Iteration 3b Building simulations

#### Good Building = 83.68%
* Daylight factor = 45.66%
* Passive ratio = 98.90%
* Solar Factor = 88.52% 

#### Good Window =25.35%
* View Factor = 48.46%
* Good window ratio = 84.26%


### Evaluation
With reduced width and depth of residential towers, view factor and good window improved significantly. Good window has increased to 25.35% from its previous 19.74%. Good building has also increased to 83.68%, up from its previous 63.23%.

The low perentage of good window here is still low at 25.35%. However, this is due to the block typology of a courtyard residential tower. All inner courtyard facing windows are considered to be unpleasant in this simulation. In reality, inner facing windows are to be considered desirable as the courtyard was meant be filled with greenery and landscape. Hence, the number of good window would be significantly higher.

