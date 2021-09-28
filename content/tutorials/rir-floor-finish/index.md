---
title: "Floor Finishes by Room using Grasshopper inside Revit"
date: 2021-09-16T20:29:54+03:00
# weight: 1
# aliases: ["/first"]
tags: ["tag1", "tag2"]
categories: ["category1", "category2"]
author: "Me" # multiple authors: ["Me", "You"]
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
    image: "images/FloorFinishByRoom-Thumbnail.jpg" # or URL
    alt: "<alt text>"
    caption: "<text>"
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
---

{{<youtube fA34G708GSg>}}

---

In this video, we are going to automate floor finish creation using Grasshopper inside Revit. Creating floor finishes is a task that can be automated easily and save us a huge amount of time. When room finishes are defined or embedded in a room's parameter, it doesn't make any sense to model floor finishes manually. We are going to create floor finishes from room boundaries using Grasshopper inside Revit. Lets get started!

<a href="files/FloorFinishesByRoom.rar" download>
    {{< button text="Tutorial Files">}}
</a>

## Requirements

- **Rhinoceros 7**
- **Rhino Inside Revit** - to install Rhino inside Revit, head over to [Rhino.Inside website.](https://www.rhino3d.com/inside/revit/1.0/)
- **Autodesk Revit** - I am using Revit 2022 in this tutorial.

{{< callout emoji="📌" text="Creating floors with curveloops is a new feature that came with version 2022. So if you are using an older version, it will create a new floor for each loop." >}}

