
# Iteration 1a

An octogonal grid is first constructed. Then courtyards are punched into the individual building blocks, and plot areas less than 1000m2 are converted into parks. 

>Grid> Polyexpand> 'Make-Octogon'> Boolean Intersect (with courtyards)> Boolean Intersect (with site)
><img src="https://raw.githubusercontent.com/design-automation/urban-prototyping-2018/master/lisa/imgs/1aworkflow.jpg"
>alt="1aworkflow" width="1240" height="354.5" border="10" />

**Final results**

<img src="https://raw.githubusercontent.com/design-automation/urban-prototyping-2018/master/lisa/imgs/1aviewfactor.JPG" 
alt="octogon" width="1089" height="613" border="10" />

View Factor Evaluation

<img src="https://raw.githubusercontent.com/design-automation/urban-prototyping-2018/master/lisa/imgs/1apassiveratio.JPG" 
alt="octogon" width="1075" height="596" border="10" />

Passive Ratio Evaluation

<img src="https://raw.githubusercontent.com/design-automation/urban-prototyping-2018/master/lisa/imgs/iteration1agbbldg.JPG" 
alt="octogon" width="1087" height="701" border="10" />

Good Building Evaluation


The results were astonishing as almost all the buildings were bad buildings. 

After going through the evaluation nodes I realised the reasons why.
1. The buliding blocks were too close together, resulting in bad views and subsequently bad windows. 
2. The individual buildings were too wide, resulting in a bad passive factor and subsequently bad buildings.


>Make Octogon node:
>
><img src="https://raw.githubusercontent.com/design-automation/urban-prototyping-2018/master/lisa/imgs/octogon.JPG" 
>alt="octogon" width="241" height="325" border="10" />
>
>The 4 corners of the square are individually selected, then boolean-intersected with smaller squares rotated at a 45 degree angle, to create the octogon.

This node is present in all my iterations, used to create the octogonal shape of the building blocks
