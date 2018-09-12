# XYLEM

![Perspective](./imgs/r6.jpg)

The last algorithm stems from an exploration into the Shortest Path SOP in Houdini. We discovered that rather than manually drawing road connections like the previous two examples, efficient road systems could also be generated parametrically using this function. However, as we have already explored road and parcel models in the previous examples, merely changing to another street network is not very tantalising to do.

Instead, we inverted the street and block relationship and treated the street as the base of a megastructure where all the programmes are packed into a single building. The building has returned positive analysis results, therefore, we evlovled it with more changes to push the boundaries.

The algorithm is constructed in the following steps:

![Point Vertices](./imgs/c1.png)

We first triangulate the site into segments of 150m. This offers a good balance between number of turns in the path and the distance between two braches. A starting point is chosen in the center of the site. All vertices are treated as end points. 

![Path Offset](./imgs/c2.png)

The algorithm then carves out the shortest path that connects all boundary points to the start point. Every connection on the fringe of the site represents a potential entry to the site.

Rather than using the path as roads, we offset it to have a width of 30m and extruded the surface so that all program requirement of 75,000 would fit into a continuous, 9 stories tall megastructure.


![Iteration 1](./imgs/c3.png)


Building analysis has returned positive. Upon further testing, we could push the passive threshold to 0.65 and good window threshold to 0.2. This is a substantial increase from the default parameter. 

Passive ratio in the structure is high because of the slender width compared to  building footprint and the windows return positive results due to the longest branches sprawlling from West to East and therefore creating windows facing North and South.


![Zoning with Attractors](./imgs/c4.png)


Like the previous two examples, we allocate zones according to attractor factors. Each zone now has an individual starting point that connects to the rest of the site.

![text label](./imgs/c5.png)

The three functional zones join together to create a non-stop experience of living, shopping, and working.

![Iteration 3 with POLYGON typology](./imgs/c6.png)

The current structure is reminiscent of the podium typology introduced in POLYGON. By planting the typology function as a module into this algorithm, we obtain a podium-tower typology just like in POLYGON. Although performance analysis returned good results, the leaf-like spatial arrangement of the programs in this iteration is not very conducive for community interaction as each residential tower has only two ajacent towers and the roof space segements are too elongated for an enjoyable after dinner stroll. Therefore, the towers need to move to a more suitable location.


![Shortest Path Inversion](./imgs/c7.png)


The spaces enclosed by the branches of the megastructure offers an ideal location for communities to thrive. These courtyards offer intimacy to the residents and the branches offers them work, shopping and quick transportation. Therefore, we subtracted the building footprint from the site, applied the generative function used in TETRIS on the resulting surface.

![2 out of 5 Plots](./imgs/c8.png)


![Iteration 4 with TETRIS function](./imgs/c9.png)

Several density studies are done to find the optimal setting in this context. Taking 2 blocks out of 5 blocks produces a low rise residential community. However, this model performs badly due to buildings blocking each other's view.

![1 out of 5 Plots](./imgs/c10.png)


![Iteration 5](./imgs/c11.png)


After a series of trials, we set the density to 1 out of 5. This creates a mostly point block neighbourhoods which returns a good building ratio of 96.38%. Residential blocks are surrounded by green spaces and are hugged by retail and work spaces. This semi-lattice spatial relationship resovles the disadvanges of the megastructure discussed above.
 
![Perspective with Programme Colour](./imgs/r5.jpg)
