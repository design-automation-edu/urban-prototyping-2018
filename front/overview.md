# Urban Prototyping 2018

**Patrick Janssen**

## Overview

To be completed... 

## Assignment

For the final assignment, students were asked to use the urban prototyping methods to explore a set of urban massing options for the 75 Ha site between the AYE and Dover Road, with the following requirements:

* Basic Generative Requirements: The total floor area must be for 35 m2 per person, for 75,000 people. That comes to a total of 2.6 million m2 of floor area. This must be constant for all the models that are generated. The way that these 35m2 are divided between different program is up to you, and may vary from project to project. For example, some may assign 22m2 per person to residential, while the remaining 13m2 are divided more or less equally between offices, shops, and clean-tech industrial. In other cases, you may decide to vary this distribution in different parts of the site. So for example, if in one area of your site, you are proposing a lot of student housing, then maybe 22m2 is too high. 

* Basic Evaluative Requirements: All buildings must achieve basic requirements that ensure a reasonable quality for the space, in terms of daylight, views, etc. These are evaluated using the "Generate Buildings" and "Evaluate Buildings" Houdini nodes. These nodes will use a simple scoring system to calculate whether the building is "good" or not. For your urban massings, you must try to make most buildings are evaluated as "good" blue buildings. (You may find that there are a few red buildings left that are not achieving the "good" threshold. This is not so a big issue, as long as there are not too many of them.)

* "Eval  Buildings" Node (version >= 7) Settings: The settings for the "Evaluate Buildings" node must be as follows:​
  * For good windows,
    * view_threshold>0.4
    * daylight_threshold>0.1
    * solar_threshold<0.2
  * For good building thresholds,
    * passive_threshold>0.5
    * good_window_threshold>0.1

* Design Goals: On top of these basic generative and evaluative requirements, you should set your own design goals that will drive your exploration process. These goals can be very diverse, but will typically be related to some kind of quality-of-life targets. For example, that residents live close to the MRT, or that they do not overlook the AYE, or that everyone is 5 mins from a park, etc. You can also include non-quantifiable goals that are evaluated based on visual inspection of the models. 
