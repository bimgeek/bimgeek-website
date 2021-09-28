---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
# weight: 1
# aliases: ["/first"]
tags: ["tag1", "tag2"]
categories: ["category1", "category2"]
author: "Me" # multiple authors: ["Me", "You"]
showToc: false
TocOpen: false
draft: true
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
    image: "images/imageName" # or URL
    alt: "<alt text>"
    caption: "<text>"
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/<USERNAME>/<PROJECT_NAME>/content/{{ .Name }}"
    Text: "Suggest Changes"
    appendFilePath: true
---