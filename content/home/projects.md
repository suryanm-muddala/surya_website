+++
# Projects widget.
# This widget displays all projects from `content/project/`.

date = "2017-10-15"
draft = false

title = "Projects"
subtitle = ""
widget = "projects"

# Order that this section will appear in.
weight = 10

# View.
# Customize how projects are displayed.
# Legend: 0 = list, 1 = cards.
view = 1

# Filter toolbar.

# Default filter index (e.g. 0 corresponds to the first `[[filter]]` instance below).
filter_default = 0

# Add or remove as many filters (`[[filter]]` instances) as you like.
# Use "*" tag to show all projects or an existing tag prefixed with "." to filter by specific tag.
# To remove toolbar, delete/comment all instances of `[[filter]]` below.
[[filter]]
  name = "All"
  tag = "*"

[[filter]]
  name = "Deep Learning"
  tag = ".Deep-learning"

[[filter]]
  name = "Active Noise Control"
  tag = ".Active-Noise-Control"

[[filter]]
  name = "Depth Based Inpainting"
  tag = ".Depth-Based-Inpainting"

  [[filter]]
    name = "3D and Free View Rendering"
    tag = ".3D-Freeview-rendering"

+++
