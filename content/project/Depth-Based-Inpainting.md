+++
# Date this page was created.
date = "2017-11-02"

# Project title.
title = "Depth-Based-Inpainting"

# Project summary to display on homepage.
summary = "Depth-based Inpainting method for filling disoclusions appear in the 3D rendered views "

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "pub/inpv.gif"

# Tags: can be used for filtering projects.
tags = ["computer-vision", "Depth-Based-Inpainting"]

# Does the project detail page use math formatting?
math = false

+++

Disocclusions are one of the major problems in virtual views when rendered from DIBR. Disocclusion are holes occur at depth discontinuities near the object borders. Disocclusions needs to be handled using background data since they are part of it. However, distinguishing foreground-background requires the knowledge of depth. Thus we adopt inapinting methods and incorporated depth and developed methods to handle disocclusion in a plausible manner.

{{< figure src= "/img/pub/inp2.gif" title="Comparision of Depth-based inpainting methods" >}}

For more details of the project [follow](http://miun.diva-portal.org/smash/get/diva2:906337/FULLTEXT01.pdf)
