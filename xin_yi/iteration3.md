# Iteration 3 - Zoning through Parametric Attractors

Various attributes are mapped in as parameter within the modelling network. 

Residential buildings (the tower blocks) are planned wtih increasing relative density (RD) in closer proximity to MRT stations to encourage the use of public transportation. They are also situated further from the AYE for the comfort of the residents (issues of traffic noise etc). Institution buildings (the podium blocks) are zoned close to Utown, facilitating ease of knonwledge exchange betweeen instituitions and offices and R&D from the convenience of proximity. They are also planned in increasing relative density along the AYE (since those buildings are more likely to be air-conditioned and closed off, where noise will be less of a concern), allowing a buffer distance between residential blocks and AYE. Commercial buildings (the precinct blocks) are present in every urban block, providing a sense of enclosure for the public space that resides within it. 

![Left: Factors affecting RD of Institutional buildings. Right:  Factors affecting RD of Residential buildings.](imgs/03instiresiall.jpg)

### Changes from iteration #02

* changes to required relative density for institutional buildings
* changes to required relative density for residential buildings

### Generative Process

This is generated through the following process:

Dividing site into urban blocks > Forming plots > __Specifying relative density for each required program__ > Make building > Evaluate building

![Generative process](imgs/03generativeprocess.PNG)

![Computational process - Institutional Buildings](imgs/03computationallogicInsti.png)

![Computational process - Residential Buildings](imgs/03computationallogicResi.png)

### Parameters

* Residential storey height: 3m
* Commercial storey height: 5m
* Institutional storey height: 4m
* Roads: xx m
* Attribute composite blending weights (Institutional Blocks)
  * air path: 0.50
  * AYE: 0.75
  * Utown: 0.60
* Attribute composite blending weights (Residential Blocks)
  * air path: 0.50
  * AYE: 0.35
  * MRT stations: 0.65
  
![Various attributes and their individual effects on RD](imgs/03attribweight.jpg)
 
![Composited attribute for Instituitional buildings](imgs/03Insti_composite.png)
  
![Composited attribute for Residential buildings](imgs/03Resi_composite.png)

### Evaluation of Results

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
