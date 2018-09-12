
# Iteration 1a: Tests

In this iteration, regular and irregular Voronoi grid coupled with different building types were tested extensively to understand the environmental implications of each strategy should they be chosen.
The following are a quick run through of the various types tested

## Superblock + Barcelona Courtyard Type
![Superblock + Barcelona Courtyard Type](./imgs/iteration1TEST1.png)
*	Percentage Good Windows: 10.9918
*	Percentage Good VF: 51.6432
*	Percentage Good SF: 85.655
*	Percentage Good PR: 100
*	Percentage Good DF: 47.0903
*	Percentage Good Building: 5.28736

## Grid + Barcelona Courtyard Type
![Grid + Barcelona Courtyard Type](./imgs/iteration1TEST2.png)
*	Percentage Good Windows: 8.85619
*	Percentage Good VF: 42.6957
*	Percentage Good SF: 87.5468
*	Percentage Good PR: 100
*	Percentage Good DF: 42.0251
*	Percentage Good Building: 4.77002

## Voronoi + Barcelona Courtyard Type
![Voronoi + Barcelona Courtyard Type](./imgs/iteration1TEST3.png)
*	Percentage Good Windows: 8.85619
*	Percentage Good VF: 42.6957
*	Percentage Good SF: 87.5468
*	Percentage Good PR: 100
*	Percentage Good DF: 42.0251
*	Percentage Good Building: 4.77002

## Evaluation
Although voronoi grid introduces more turns and consequently a slightly more interesting street scape, it returns less value to this simulation when buildings are built to the edge of the plot. Daylight, view, and solar factor are all too low.

# Iteration 1b: Instant Gratification
![Linear N-S facing types](./imgs/iteration1bldgRender.png)
Linear N-S facing types
![Distribution of types: yellow - Commercial; grey - Industrial](./imgs/iteration1distribution.png)
* Distribution of types: yellow - Commercial; grey - Industrial
<br/><br/>
Conceptually, Commercial and Industrial Buildings were mixed to possibly work as clean tech industrial towers with a possible mix of retail. Residential buildings are all made to be within walking distance of a clean tech tower. This is to simulate a city for clean tech workers.

![Environment Evaluation 3d](./imgs/iteration1goodBadRender.png)
![Iteration 1 Environment Evaluation Plan](./imgs/iteration1goodBadRenderpLAN.png)
* Percentage Good Windows: 81.8129
* Percentage Good VF: 96.5413
* Percentage Good SF: 89.2467
*	Percentage Good PR: 100
*	Percentage Good DF: 92.7323
*	Percentage Good Building: 95.9677

These 32-storey (max), N-S facing towers prove to be effective in achieving good environment results. They allow the ground to be completely free up for activities and green space.
<br/><br/>
However, they look awfully boring. 
<br/><br/>
In the subsequent iterations, I try to deviate from a uniform urban grain and rigid distribution of similar types.
