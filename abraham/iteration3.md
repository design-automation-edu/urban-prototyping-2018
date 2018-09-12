# XYLEM

![text label](./imgs/r6.jpg)

The last algorithm uses a different thinking compared to the rest. Rather than manually drawing road connections like the previous two examples, a more efficient road system could be generated using Shortest Path SOP in Houdini. Shortest paths to certain key nodes in the site can be carved out and used both as roads and commercial spaces. This approach creates a high performing megastructure that could not be designed with conventional methods. 

This algorithm also included functions completed in the previous two examples. This shows that functions can be transfered as modules and immediately applied in different con

The algorithm is constructed in the following steps:

![Point Vertices](./imgs/c1.png)

1.	We first triangulate the site into segments of 150m. This offers a good balance between number of turns in the path and the distance between two braches. A starting point is chosen in the center of the site. All vertices are treated as end points. 

![Path Offset](./imgs/c2.png)

2.	The algorithm then carves out the shortest path that connects all boundary points to the start point. Every connection on the fringe of the site represents a potential entry to the site.
3.	Rather than using the path as roads, we offset it to have a width of 30m and extruded the surface so that all program requirement of 75,000 would fit into a continuous, 9 stories tall megastructure.

![Iteration 1](./imgs/c3.png)

4.	Building analysis has returned positive. Upon further testing, we could push the passive threshold to 0.65 and good window threshold to 0.2. This is a substantial increase from the default parameter. Passive ratio in the structure is high because of the slender width compared to  building footprint and the windows return positive results due to the longest branches sprawl from west to east and therefore create windows facing north and south.


![text label](./imgs/c4.png)


5.	Like the previous two examples, we allocate zones according to attractor factors. Each zone now has an individual starting point that connects to the rest of the site.

![text label](./imgs/c5.png)

6.  The three functional zones join together to create a non-stop experience of living, shopping, working, and production.

![text label](./imgs/c6.png)

7. The current structure is reminiscent of the podium typology introduced in POLYGON. By planting the typology function as a module into this algorithm, we obtain a podium-tower typology with residential in the towers and others in the megastructure. Although performance analysis returned good results, the leaf-like spatial arrangement of the programs in this iteration is not very conducive of community interaction as each residential tower has only two ajacent towers and the roof space is too elongated for walking. Further changes to the urban fabric is required.

![text label](./imgs/c7.png)


8. The spaces enclosed by the branches of the megastructure offers an ideal location for communities to thrive. These courtyards offerr intimacy to the residents and the branches offers them work, shopping and the quickest way to commute to the fringe. Therefore, we subtracted the building footprint from the site, applied the generative function used in TETRIS on the resulting surface.

![text label](./imgs/c8.png)
![text label](./imgs/c9.png)

9. Several density studies are done to find our the optimal setting in this context. Taking 2 blocks out of 5 blocks produces a low rise residential community. However, this model performs badly due to buildings blocking each other's view.

![text label](./imgs/c10.png)
![text label](./imgs/c11.png)

10. After a series of trials, we set the density to 1 out of 5. This creates a mostly point block neighbourhood which returns a good building ratio of 96.38%. The spatial arrangment of the three program spaces is also effective where the private residential blocks are surrounded by semi pivate green spaces and hugged around by public retail and work spaces.This semi-lattice spatial relationship resovles the disadvanges of the megastructure discussed above.

![Perspective with Programme Colour](./imgs/r5.jpg)
