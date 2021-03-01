---
title: Introduction
sidebar: mydoc_sidebar
permalink: mydoc_introduction.html
folder: mydoc
---

## Overview

This site provides documentation, training, and other notes for the Jekyll Documentation theme. There's a lot of information about how to do a variety of things here, and it's not all unique to this theme. But by and large, understanding how to do things in Jekyll depends on how your theme is coded. As a result, these additional details are provided.

The instructions here are geared towards technical writers working on documentation. You may have a team of one or more technical writers working on documentation for multiple projects. You can use this same theme to author all of your documentation for each of your products. The theme is built to accommodate documentation for multiple products on the same site.

## Tutorial

In this this quick tutorial we are going to create a custom battery


### <b> <i> Step 1 - Creating a Mod </i> </b>

Lets start by creating a mod first to store our battery

This will allow us to add extra functionality to a simulation component

- Launch Unreal Engine
- Open up the Baby Lizard project
- Press the "Create UGC" button on the toolbar
- Give your new mod a name and press "Create Mod"

<br/>

![Image 1](./Resources/Images/QuickTutorial_01.png)

<br/>

![Image 2](./Resources/Images/QuickTutorial_02.png)


<br/>
<hr/>

### <b> <i> Step 2 - Creating a Battery </i> </b>

<br/>

Next we need to create a new battery blueprint

On the content folder of our new mod we created:

- Right-Click and create a new blueprint
- Under all classes, search for BskSimpleBattery
- Press the "Select" button and give your blueprint a name

<br/>

![Image 3](./Resources/Images/QuickTutorial_03.png)

<br/>

![Image 4](./Resources/Images/QuickTutorial_04.png)

<br/>

<br/>
<hr/>

### <b> <i> Step 3 - Editing our Battery </i> </b>

<br/>

Below is the blueprint graph for out battery

If you are not familiar with Unreal Engine, we sugest watching the official tutorial:

- [Intro to Blueprints: Blueprint Introduction | 01 | v4.8 Tutorial Series | Unreal Engine](https://www.youtube.com/watch?v=EFXMW_UEDco)

The left panel shows the simulation events and variables that our custom battery uses

In the example we are creating a battery that has a leak on it's charge by updating the final message

<br/>

![Image 5](./Resources/Images/QuickTutorial_05.png)


<br/>

![Image 6](./Resources/Images/QuickTutorial_06.png)

<br/>
<hr/>

### <b> <i> Step 4 - Packaging your new Mod </i> </b>

<br/>

Once you are happy to package your new battery or custom components:

- Press the "Package UGC" button in the toolbar

![Image 7](./Resources/Images/QuickTutorial_07.png)

<br/>
<hr/>

### <b> <i> Step 5 - Congratulations </i> </b>

Congratulations on making your first mod! You are now ready to submit your mod to our simulation pipeline

We will update out documentation more in the future with more tutorials on how to use our editor

Feel free to contact us if you require any assistant or information

<br/>











Some of the more prominent features of this theme include the following:

* Bootstrap framework
* [Navgoco multi-level sidebar](http://www.komposta.net/article/navgoco) for table of contents
* Ability to specify different sidebars for different products
* Top navigation bar with drop-down menus
* Notes, tips, and warning information notes
* Tags for alternative navigation
* Advanced landing page layouts from the [Modern Business theme](http://startbootstrap.com/template-overviews/modern-business/).

## Getting started

To get started, see [Getting Started][index].

{% include links.html %}
