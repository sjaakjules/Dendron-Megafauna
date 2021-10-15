---
id: l8NojJvWuJrGAfc4j0ZKm
title: Project Structure
desc: ''
updated: 1634282545148
created: 1634269245118
---

This project is organised as four parts

### Research Cluster

The research cluster is a hierarchically organised,  interconnected set of annotations, notes and documents. The research cluster provides tnhe significance for the project. It is broken down into three major sub-clusters:

- project
- methods
- concepts

The research cluster is hosted on github and uses the dendron framework.

### Source Environment

The source environment is a multi-format, multi-scalar, semi-structured  dataset specific to a place. It is comprised of:

- GIS information
- aerial lidar
- terrestrial lidar
- sychrotron tomographic data

The source environment is self-hosted using the potree and 3Js frameworks.

### Actions

Actions are metadata linking the research cluster with the source environment. Actions are described using the following markers:

- point cloud styling (javascript: specify annotations, colours, lines, callouts, buttons, animations)
- point cloud location (xyz vector embedded within the URL).

Where possible, notes in the research cluster should be linked to the source environment with styling and location markers.

### Stories

Stories are paths through the project. They can take the form of

- freeform, exploritary and DIY stories participants can construct for themselves by exploring the research cluster on GitHub
- videos, gifs and images describing key stories
