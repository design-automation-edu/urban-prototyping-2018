# Discussion

Streets are one of the key structuring elements of the urban fabric. 
<br><br>
A ‘planned city’ is one which reveals a strong urban order created by streets which weaved through it. Often, urban blocks created by the streets become neighbourhoods distinct from one another. Streets become a hard edge that visibly separates one block from another.
<br><br>
The questioning of planned vs. unplanned, ordered vs. disordered city, was what motivated this project. Hence, different ways of street carving, and plot creation and assignment became an initial challenge. Subsequent challenges dealt with connecting newly cut street network to existing roads and connecting subdivided streets to specific points (designer defined city-centres). Finally, reliable ways of creating building types was required to conduct quick tests on the generated city.
<br><br>

## Plot Division

Superblocks were created by layering divisions and by isolating each layer from one another. Irregular grids were created using Voronoi. By running the initial polygon through Voronoi again using the points from the first Voronoi result, one gets a division lines which are close to the ones originally set. These techniques proved to be transferable and were useful in many occasions.

## Plot Assignment

In iteration 2, the seemingly random merging of polygons was highly controllable. Because subdivided plots are always smallest along the edges of a divided polygon, in each division, by finding all polygons which fall below the average area, I was able to isolate polygons of various sizes quickly. By merging the smallest pieces along the corners of a block, it created an interesting street scape where every corner was marked with a larger grained landmark.
<br><br>
In iteration 3, every division was important and was required to be tracked as lines. Also, Centre points of every polygon was also kept for reference. Every polygon in further subdivisions later can then compute distance values against these lines or points to track its distance from a road or centre. This reflects a method where a designer can always keep track of newly computed forms against pre-existing ones and make decisions based on numerical rules.

## Building types
Not many building type tools were created in this project. The Barcelona Courtyard type was best visualised when used with the regular grid divisions created previously. A grid overlay or a subdivided a polygon allows the designer to better create type variations. Grid overlay is used when knowing the grid dimensions is essential, otherwise the predictability of subdivision across all primitive polygons is a lot easier for the designer to create footprint patterns. To prevent creating unrealistic thin buildings from said patterns, checks were conducted after footprint creation to ensure a minimum footprint dimension. The successful typology created in iteration 1 was created by patterning on a subdivided plot.

## Future Explorations
In this project, various methods used for plot division and assignment, and building type creation were used independently of one another. Each tool needs to be further explored and explorations which utilises all techniques concurrently may be interesting.
<br><br>
Arterial roads created by initial plot divisions were treated equally. Using shortest path algorithm, an attractor/repelling curve could be created for plots to compute against. For example, more commercial, and less residential and industrial activity could be assigned to plots along such path. 
<br><br>
Voronoi divided streets were presumed to be more “organic” as streets bend slightly at intersections and creates a more interesting visual appeal than an ever-ending linear road. However, the overall urban structure was still a product of the rigid streets that carved out the blocks. I’m currently still wrapping my head around the possible use of L-systems and Differential Curve growth methods to generate a more organic street network.



