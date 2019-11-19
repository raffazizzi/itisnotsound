---
title: "Video: Creating a TEI Customization with the new Roma"
thumb: /images/foriromani.jpg
tags:
  - TEI
  - TEI Council
  - ODD
categories:
  - Text Encoding
comments: true
date: 2019-11-18 12:00:00
---

<div class="iins-photo_header">
  <img class="center" style="margin-top: -175px" alt="Alba sul Foro Romano by Stefano Lovato" src="/images/foriromani.jpg"/>
</div>

> [Photo CC BY 2.0 Stefano Lovato.](https://www.flickr.com/photos/101165136@N07/27834339605)

As part of my tenure in the [Text Encoding Initiative](https://tei-c.org) Technical Council, I worked on a new online tool to customize the TEI XML schema. You can find it at <https://romabeta.tei-c.org>.

I have just published a video demo / tutorial that guides the viewer through some typical customization operations. My approach to TEI customization definitely comes through in this video, but I hope it'll be useful to others, too!

The video centers around a customization to represent the [OpenITI mARkdown scheme](https://alraqmiyyat.github.io/mARkdown/), which I created for the [OpenITI](http://openiti.org) project.

<iframe src="https://player.vimeo.com/video/373995865" width="640" height="357" frameborder="0" allow="fullscreen" allowfullscreen></iframe>

## What is a TEI customization?

The TEI module for writing or customizing an XML markup language (the “tagdocs” module of chapter 22, “Documentation Elements”), as well as a file defining or customizing an XML language using these elements, is typically referred to as One-Document-Does-it-all or ODD. The procedural nature of these elements makes it possible to develop form-based user interfaces to generate ODD; indeed, the current tool for customizing the TEI schema, [Roma](<http://roma.tei-c.org>), is widely used by the TEI community to generate project-specific schemata. Roma, however, does not fully reflect the possibilities of the ODD subset of elements, and has been afflicted by a number of bugs and issues, many of which remain unresolved or are too complex to be fixed by the TEI Technical Council.

The TEI Technical Council has opted to create a replacement for Roma from scratch, using modern web technologies, expanding the number of features supported, and focusing on user interface. So I've set to develop a web application using the popular front-end libraries React and Redux. Just like the current version of Roma, this new version relies on the TEI Stylesheets to perform ODD transformations, including from ODD to XML schema formats. To perform these transformations, Roma interacts with [OxGarage](http://www.tei-c.org/oxgarage/), an on-line service for TEI transformations.
