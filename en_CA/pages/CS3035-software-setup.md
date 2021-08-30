# CS 3035 Software Setup

## TL;DR

- We will be using Java 16 with IntelliJ
- Install all course software on your own computer
- All course software is free and should run on Windows, Mac and Linux
- We also use git but the version built into IntelliJ will be sufficient
- Our second class will be used to demonstrate software setup

## Overview

We will install the latest versions of the tools available as of the first day of class. 

## Preferred Option: Installing Software for your own computer

### Minimum Hardware Requirements

- The Faculty of Computer Science has made recommendations about the minimum requirements for your coursework.
- These are also appropriate and sufficient for this course.
- Please see: <https://www.cs.unb.ca/help/students/recommended-hardware.shtml>

### Install IntelliJ IDEA Edu

- We will be using IntelliJ IDEA Edu for writing Code
- [Download and Install IntelliJ IDEA Edu](https://www.jetbrains.com/edu-products/download/#section=idea)
- Once you install you can configure the IDE how you like
- But there is an additional step below for adding in Scene Builder

### Java 16

- Once you have installed IntelliJ on your computer you can install Java 16 from inside IntelliJ
- Simply create a new Java project from the project creation dialogue click the dropdown and choose to install Java 16 (if you don't already have it installed)
- Here is a [simple video to show the step](https://www.jetbrains.com/idea/guide/tips/download-jdk/) 

### Install Scene Builder

There are two general options for getting Scene Builder. Option 1 will be the most convenient for both installation and use, but you are able to do both.

#### Scene Builder Option 1

- Scene Builder is a JavaFX app for building JavaFX interfaces that can be integrated into IntelliJ
- The easiest way to to do this is to create a new JavaFX project and download it automatically
  - From the launch window choose "New Project"
  - Choose "JavaFX" for the project type
  - Name the project anything you like
  - Open the sample.fxml file
  - At the bottom of the editor window click the "SceneBuilder" tab
  - Click the "Download Scene Builder Kit" link

#### Scene Builder Option 2

- This is not needed if you did the above but you can also [Download Scene Builder as a standalone app for Java 8](https://gluonhq.com/products/scene-builder/#download)
- You can then manually associate your Scene Builder executable with IntelliJ: ```Settings → Languages & Frameworks → JavaFX → Path to SceneBuilder```

## Git

There is a lot of software available to assist in working with Git. Our use should be relatively straightforward and so the version built into IntelliJ will be the one that is supported for the course. See [Using Git](pages/../CS3035-assignments-with-git.md)
