---
title: "{{ replace .Name "_" " " | title }}"
date: {{ .Date }}
# weight: 1
# aliases: ["/first"]
tags: ["first"]
author: "Benoit Hamel"
# author: ["Me", "You"] # multiple authors
showToc: true
tocopen: false
draft: true
hidemeta: false
comments: false
description: "Desc Text."
canonicalURL: # TODO : build un canonical URL avec les variables HUGO
ShowCanonicalLink: false
CanonicalLinkText: 
disableHLJS: true # to disable highlightjs
disableShare: true
ShareButtons: []
disableAnchoredHeadings: false
hideSummary: false
hideFooter: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowCodeCopyButtons: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
robotsNoIndex: false
cover:
    image: # image path/url
    alt: # alt text
    caption: # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
    responsiveImages: true
# editPost:
#    URL: "https://github.com/<path_to_repo>/content"
#    Text: "Suggest Changes" # edit text
#    appendFilePath: true # to append file path to Edit link
---
