+++
# Date this page was created.
date = "2017-11-02"

# Project title.
title = "Deep-learning"

# Project summary to display on homepage.
summary = "Robocode: Unique address generation"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "deep/robocode.gif"

# Tags: can be used for filtering projects.
tags = ["Deep-learning"]

# Does the project detail page use math formatting?
math = false

+++

According to the United Nations, Four billion people are ‘invisible’ due to lack of an address. Recent initiatives tend to name unknown areas by geocoding, which uses latitude and longitude information. Nevertheless settlements abut roads and such addressing schemes are not coherent with the road topology. Instead, our algorithm starts with extracting roads and junctions from satellite imagery utilizing deep learning. Then, it uniquely labels the regions, roads, and houses using some graph- and proximity-based algorithms.

{{< figure src= "/img/deep/robocode.gif" title="Robocode proceesing steps" >}}

For more details of the project: [Source1](https://github.com/facebookresearch/street-addresses)
