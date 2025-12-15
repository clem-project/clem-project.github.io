---
layout: about
title: Home
permalink: /
subtitle: |
  <a href="https://www.diverse-team.fr/">DiverSE @ University of Rennes</a>, France <br/>
  <a href="https://se.jku.at">BISE @ Johannes Kepler University Linz</a>, Austria.

# profile:
#   align: right
#   image: prof_pic.jpg
#   image_circular: false # crops the image to make it circular
#   more_info: >
#     <p>555 your office number</p>
#     <p>123 your address street</p>
#     <p>Your City, State 12345</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Behavioral models are widely used in science and engineering for representing different kinds of
systems, such as software-intensive, cyber-physical, and economic systems. Such models usually
need to be first designed, then implemented, and finally executed before results can be observed to
answer particular questions about the systems. Each time the model is changed to reflect evolving
requirements, alternative scenarios or potential improvements, the entire process must be restarted.
The initial model state must be prepared and the full previous execution history must be replayed to
see the effects on the results.

Live modeling challenges the strict design-first/execute-later approach by enabling users to
seamlessly transition between design and execution phases. This makes it possible to render the
effects of a design change visible directly on an already running execution without requiring a full
restart and replay of the execution history. Furthermore, combining live modeling with exploratory
modeling enables the direct exploration of a model’s design space as well as its runtime states. This
allows design alternatives to be compared in experimental settings and accelerates the exploration
of the design space.

Although preliminary studies of both live and exploratory modeling have been conducted, there is
still no systematic modeling language engineering approach for designing and executing behavioral
models with the support of such facilities. Consequently, these facilities must be redeveloped for
each new modeling language. Furthermore, to the best of our knowledge, there is currently no
guiding framework for the sound combination of live and exploratory modeling.
This project will develop a tool-supported methodology to enable live and exploratory modeling. In
particular, scenarios such as the interactive use of live modeling in the context of the exploration and
the efficient comparison of several alternative model designs will be studied for the first time. This
sound combination of live and exploratory modeling will provide the necessary support for design
space exploration, trade-off analysis, and decision making.

The integration of several advanced modeling techniques is required for the efficient replay of model
interaction and effective design model synthesis to realize immediate feedback and direct
manipulation for behavioral models. We will therefore develop a novel architecture for model
execution engines that offers interactive model execution. This architecture will also support the
necessary tool interfaces and language protocols for integrating interactive model exploration tools.
Moreover, we will establish language design principles to enable these capabilities for any modeling
language.