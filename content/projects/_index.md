+++
title = "My projects"
description = "Projects page of ..."
template = "prose.html"

[extra]
title = "Projects"
subtitle = "These are some of the projects I’ve been working on — some are still in progress, others are finished, but each reflects something I’ve learned or built along the way."
+++

{{ collection(file="projects.toml") }}