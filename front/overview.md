# Urban Prototyping 2018

**Patrick Janssen**

## Overview

This book was developed as part of a Mastres level elevtive module called Urban Prototyping, at the Department of Architecture, National University of Singapore. The module was taught from 30th July to 12 Speptember 2018.

The site for the elective eas be a 75 Ha area between Dover Road and AYE, and between NUS UTown and North Buona Vista Road. The target population for this site was be 75,000 people. The brief was to develop a high-density mixed-use urban fabric consisting of a varied range of street networks and urban block typologies, combining residential with commercial, industrial, educational, and other work spaces. 

The elective aimed to explore parametric urban prototyping methods for generating and evaluating alternative proposals using the Houdini software. These method captured spatial urban rules as parameter fields that varied over the extent of the site in response to context and environment. Urban block typologies were then created and linked to these parameter fields, so that their form and configuration varied automatically depending on their location. Throughout the design process, the urban blocks were continuously evaluated against specific performance criteria relating to liveability and vibrancy. 

## Assignment

During the first two weeks of the elective, students were required to learn the Houdini software, including the various tools for evaluating performance. After that, they were given three weeks to complete their final assignment. 

For the assignment, students were asked to apply the urban prototyping methods to explore a set of urban massing options for the site, with the following requirements:

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

## Projects

The following chapters describe the narratives and the urban massing options developed by the students.
