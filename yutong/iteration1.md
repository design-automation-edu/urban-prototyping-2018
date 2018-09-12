
# Iteration 1

## Basic Parameter 

Residential storey height: 3m

Commercial storey height: 5m

Office storey height: 4m

Industry storey height: 10m

Shops storey height: 5m

Street: 9m

Lanes: 6m

Maximum floor count: 33

Average floor count: 4

Total number of buildings: 571

## Road Network

The first iteration started from the overlapping of two sets of road networks on the one-north site. The road network was divided into two areas in proportion of about 2:1 by a 20m-wide urban main road, and then plots was divided in each area. Zone 1 is a long and narrow belt, which is located in the north of the site. Zone 2 is half surrounded by Zone1 from north-east to sourth-west. Zone 1 has a dense road network, which is divided into two road levels: 9m street in the north-south direction and 6m lane in the east-west direction. The streets of Zone 2 extends the streets of Zone 1, and adds an east-west street, which divided the Zone2 into five clusters.

## Program Mix

In Zone2, the buildings on each site are a cluster, surrounded by residential and commercial buildings to form a central green space. Dividing the plot with egg_slice node, and the path to the activity field is left between buildings on the east and west sides of clusters. Then, the program mix is applied to the two areas respectively. Zone 1 contains high-rise residential buildings with commercial podiums. According to the requirements, 22 m2 / person residential and 13 m2 / person other must be satisfied. The building height is mainly affected by MRT and AYE. The closer to MRT, the more residents there are, the closer to aye, the more commercial is distributed, so the height changes.


## Simulation

Good Window =47.9% 

Daylight factor = 67%

Solar Factor = 86.9% 

View Factor = 66.2%

Good Building = 43.6%

Passive ratio = 67.1%

Good window ratio = 62.9%

## Evaluation

Zone1:

Since the plots are quite large and the number of floors is less, the expected change trend is not achieved. Due to the problem that the average building height is too low, solar and daylight factor are further affected, while the floor is too average, which affects view. Overall assessment is poor. By adjusting the offset in polyexpand node and increasing the number of plot, the number of building floors was increased, which significantly increased the blue buildings. 

Zone2:

Due to the dense tower block, the east and west facades are not illuminated and the view is poor, resulting in a high ratio of bad Windows. Relatively speaking, the situation of the largest building group which is located in eastern area is worse, also the land utilization is low. In this group, the building is deep in north to sorth, which makes the area of bad (east and west) facade too large. What’s more, due to the influence of the gap between north and south, the view factor of the ground floor is poor.
In conclusion, both form of the buildings in two zones need to be reformed, and there’s also has room to adjust the road grid, in order to gain a better result.
