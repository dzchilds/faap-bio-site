+++
# Projects widget.
# This widget displays all projects from `content/project/`.
widget = "projects"
active = true
date = "2018-01-01T00:00:00"

title = "People"
subtitle = "Group members and associates"

# Order that this section will appear in.
weight = 20

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
  name = "all"
  tag = ".person"

[[filter]]
  name = "post docs"
  tag = ".post-doc"

[[filter]]
  name = "phd students"
  tag = ".phd-student"

+++

