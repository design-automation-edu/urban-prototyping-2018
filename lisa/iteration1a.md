
# Iteration 1a

An octogonal grid is first constructed. Then courtyards are punched into the individual building blocks, and plot areas less than 1000m2 are converted into parks. 

>Grid> Polyexpand> 'Make-Octogon'> Boolean Intersect (with courtyards)> Boolean Intersect (with site)
><img src="https://raw.githubusercontent.com/design-automation/urban-prototyping-2018/master/lisa/imgs/1bworkflow.jpg"
>alt="1aworkflow" width="1240" height="354.5" border="10" />

Overall workflow

<img src="https://raw.githubusercontent.com/design-automation/urban-prototyping-2018/master/lisa/imgs/1aflow.JPG" 
alt="1aflow" width="642" height="754" border="10" />


**Final results**

Total number of buildings evaluated: 53

<img src="https://raw.githubusercontent.com/design-automation/urban-prototyping-2018/master/lisa/imgs/1agbw.JPG" 
alt="octogon" width="1089" height="613" border="10" />

"Good" Building Ratio: 1.89%

"Good" Window Ratio: 35.85%

<img src="https://raw.githubusercontent.com/design-automation/urban-prototyping-2018/master/lisa/imgs/1apavf.JPG" 
alt="octogon" width="1075" height="596" border="10" />

Passive Area Ratio: 1.89%

Unobstructed View Factor Ratio: 81.72%

<img src="https://raw.githubusercontent.com/design-automation/urban-prototyping-2018/master/lisa/imgs/1adfsf.JPG" 
alt="octogon" width="1087" height="701" border="10" />

Daylight Factor Ratio: 84.04%

Solar Factor Ratio: 70.46%

```
Conclusion

The results were astonishing as almost all the buildings were bad buildings. 
After going through the evaluation nodes I realised it was because the passive area ratio was very low. 
My buildings were too thick - so I explored ways of 'thinning' my building block down.
```



