---
title: "Project Objects to Topography"
date: 2022-03-04T14:58:12+03:00
# weight: 1
# aliases: ["/first"]
tags: ["english", "revit", "grasshopper", "topography"]
categories: ["rhino inside", "grasshopper"]
author: "BIMGEEK" # multiple authors: ["Me", "You"]
showToc: false
TocOpen: false
draft: false
hidemeta: false
comments: false
# description: "Description Text."
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
cover:
    image: "images/project-objects-to-topography.png" # or URL
    alt: "<alt text>"
    caption: "<text>"
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single pag
---

{{<youtube J5tBJeXMO1s>}}
---
Hello everyone👋,

The topic of this tutorial is the projection of components into given topography. This is a task that can be easily automated with a simple script. Otherwise, manual placement of each object into a slanted surface would take a lot of time and kill your joy of life :).  With this grasshopper script, we will get the location point of objects from Revit, project this point into Topography and use projected points as the new location point for tree families.

{{< callout emoji="📌" text="Revit and Grasshopper files used in the tutorial can be downloaded from the button below👇." >}}

<a href="files/BG-TutorialFiles-ProjectObjectsToTopography.rar" download>
    {{< button text="Tutorial Files">}}
</a>