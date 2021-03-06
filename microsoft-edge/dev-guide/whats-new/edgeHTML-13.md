---
description: This page provides an overview of what's new in EdgeHTML 13.
title: What's New in EdgeHTML 13
author: libbymc
ms.author: libbymc
ms.date: 5/30/2017
ms.topic: article
ms.prod: microsoft-edge
keywords: edge, web development, html, css, javascript, developer
---

# What's New in EdgeHTML 13
Here are the changes shipped with EdgeHTML 13, the engine powering the Microsoft Edge browser in the [first major update](https://blogs.windows.com/windowsexperience/2015/11/12/first-major-update-for-windows-10-available-today/) for Windows 10 (11/2015, Build 10586). For an overview of changes to the overall Microsoft Edge browser, see [Introducing EdgeHTML 13, our first platform update for Microsoft Edge](https://blogs.windows.com/msedgedev/2015/11/16/introducing-edgehtml-13-our-first-platform-update-for-microsoft-edge/).

Here's the permalink for the following list of changes: [https://aka.ms/devguide_edgehtml_13](https://aka.ms/devguide_edgehtml_13).

## Features

### CSS

EdgeHTML 13 supports new CSS features, including:
* [CSS Mutability Pseudo-classes](https://developer.microsoft.com/microsoft-edge/platform/status/cssmutabilitypseudoclasses/)
* [CSS Range Pseudo-classes](https://developer.microsoft.com/microsoft-edge/platform/status/cssrangepseudoclasses/)
* CSS [initial](https://developer.microsoft.com/microsoft-edge/platform/status/cssinitialvalue/) and [unset](https://developer.microsoft.com/microsoft-edge/platform/status/cssunsetvalue/) keywords

### Encrypted Media Extensions
Microsoft Edge now supports the new unprefixed [Encrypted Media Extensions](http://www.w3.org/TR/encrypted-media/) APIs. Encrypted Media Extensions (EME) extends the video and audio elements to enable Digital Rights Management (DRM) protected content without using plug-ins. Read more about EME: [Encrypted Media Extensions](https://docs.microsoft.com/microsoft-edge/dev-guide/multimedia/encrypted-media-extensions).

### Graphics

EdgeHTML 13 introduces the following graphics updates:
* [Canvas ellipse](https://developer.microsoft.com/microsoft-edge/platform/status/canvas2dellipse/)
* [Canvas blending modes](https://developer.microsoft.com/microsoft-edge/platform/status/compositingandblendingincanvas2d/)
* [`<picture>` element](https://developer.microsoft.com/microsoft-edge/platform/status/pictureelement/)
* [SVG external content](https://developer.microsoft.com/microsoft-edge/platform/status/svgexternalcontent/)


### User Input
The following features introduced in EdgeHTML 13 improve user input:
* [`<meter>` element](https://developer.microsoft.com/microsoft-edge/platform/status/meterelement/)
* [`oninvalid` event handler for the element document and window](https://developer.microsoft.com/microsoft-edge/platform/status/oninvalideventhandler/)

### Pointer Lock
Microsoft Edge now supports the Pointer Lock API (previously called Mouse Lock) for access to raw mouse movement, locking the target of mouse events to a single element, eliminating limits of how far mouse movement can go in a single direction, and removing the cursor from view. 


## New APIs in EdgeHTML 13

Here's the full list of new APIs in EdgeHTML 13. They are listed in the format of **[interface name].[api name]**.
<iframe height='584' scrolling='no' title='New APIs in EdgeHTML 13' src='//codepen.io/MSEdgeDev/embed/vmzxEY/?height=584&theme-id=23761&default-tab=result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/MSEdgeDev/pen/vmzxEY/'>New APIs in EdgeHTML 13</a>by MSEdgeDev (<a href='http://codepen.io/MSEdgeDev'>@MSEdgeDev</a>) on <a href='http://codepen.io'>CodePen</a>.</iframe>