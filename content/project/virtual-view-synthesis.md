+++
# Date this page was created.
date = "2017-11-02"

# Project title.
title = "Virtual View Synthesis"

# Project summary to display on homepage.
summary = "A simpler and straightforward approch for producing virtual views"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "pub/lb_vs.gif"

# Tags: can be used for filtering projects.
tags = ["computer-vision", "3D-Freeview-rendering"]

# Does the project detail page use math formatting?
math = false

+++

Depth-Image-Based Rendering (DIBR) of virtual views is a fundamental method in three dimensional 3-D video applications to produce different perspectives from texture and depth information. All DIBR methods suffer from artifacts in the resulting images, which are corrected by different post-processing. The proposed method is based on fundamental principles of3D-warping. The novelty lies in how the virtual view sample values are obtained from one-dimensional interpolation, where edges are preserved by introducing specific edge-pixels with information about both foreground and background data. This avoids fully the post-processing of filling cracks and holes.

{{< figure src= "/img/pub/vd.gif" title="View Synthesis using Depth-Image-Based Rendering" >}}

For more details of the project [follow](http://miun.diva-portal.org/smash/get/diva2:627745/FULLTEXT01.pdf)
