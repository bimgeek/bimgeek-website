---
title: "Create Sheets from Excel"
date: 2022-03-21T18:30:09+03:00
# weight: 1
# aliases: ["/first"]
tags: ["english", "revit", "grasshopper", "beginner"]
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
    image: "assets/create-sheets-from-excel.png" # or URL
    alt: "<alt text>"
    caption: "<text>"
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single pag
---

{{<youtube VU7ezkzVwgM>}}
---

This is a **classic** one! You've probably come across some version of this tutorial if you made any search about Dynamo. Let me show you how you can do it in Grasshopper🦗. In this video, I created a pretty basic script. This script reads sheet data (sheet number, sheet name, etc...) from Excel then creates new sheets in Revit using this data. After the sheets have been created, the script updates specific sheet parameters using the Excel data. 

This is a pretty standard workflow. A lot of the times we prefer working with Excel data just because how easy it is to generate rows of data. Lets jump into how we can leverage the power of Excel within Grasshopper.

{{< callout emoji="📌" text="Revit and Grasshopper files used in the tutorial can be downloaded from the button below👇." >}}

<a href="assets/BG-TutorialFiles-CreateSheetsFromExcelRIR.rar" download>
    {{< button text="Tutorial Files">}}
</a>