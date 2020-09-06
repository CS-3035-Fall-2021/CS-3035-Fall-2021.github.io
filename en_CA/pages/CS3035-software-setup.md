# CS 3035 Software Setup

## TL;DR

- We will be using Java 8 with IntelliJ
- If at all possible install all course software on your own computer
- Otherwise, install software so you can get access to a virtual machine containing all of the course software
- All course software is free and should run on Windows, Mac and Linux
- We also use git but the version built into IntelliJ will be sufficient

## Overview

You have two options for getting setup for the course. The much preferred option is to install software on your own computer. However, if this is not possible there is an FCS Ubuntu Linux virtual machine image (referred to as the FCS VM below) that was created for CS 3035, or you can install software yourself on your own computer. Below you will find instructions on how to run the VM and how to install on your own system.

## Preferred Option: Installing Software for your own computer

### Install Java 8

- Download and install the latest version of the Oracle Java 8 SDK: [Oracle 8 JDK](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)
  - see below for why we should use Java version 8
- On Windows, it will also be a good idea to set your JAVA_HOME environment variable: [instructions for setting JAVA_HOME on Windows](https://confluence.atlassian.com/doc/setting-the-java_home-variable-in-windows-8895.html)

### Install IntelliJ

- We will be using IntelliJ for writing Code, and there are a number of helpful extensions that should be installed
- [Download and Install IntelliJ Community Edition 12 LTS](https://www.jetbrains.com/idea/download/#section=windows)
- Once you install you can configure how you like
- But there is an additional step below for adding in Scene Builder

### Install Scene Builder

#### Option 1

- Scene Builder is a JavaFX app for building JavaFX interfaces that can be integrated into IntelliJ
- The easiest way to to do this is to create a new JavaFX project and download it automatically
  - From the launch window choose "New Project"
  - Choose "JavaFX" for the project type
  - Name the project anything you like
  - Open the sample.fxml file
  - At the bottom of the editor window click the "SceneBuilder" tab
  - Click the "Download Scene Builder Kit" link

#### Option 2

- This is not needed if you did the above but you can also [Download Scene Builder as a standalone app for Java 8](https://gluonhq.com/products/scene-builder/#download)
- You can then manually associate your Scene Builder executable with IntelliJ: ```Settings → Languages & Frameworks → JavaFX → Path to SceneBuilder```

## Alternative Option: Running an FCS VM

The Java VM has the big advantage that all the software has already been installed for you. You can either download the VM and run it locally on your machine. Or, you can actually run the VM on an FCS computer by using a Remote Desktop session.

Both of these options are a little awkward and I would recommend installing the software on your own computer if at all possible.

- Option 1: [Install Virtual Box](https://www.virtualbox.org/wiki/Downloads) and [download the VM for CS3035](https://www.dropbox.com/s/ucrm12ikbkqpl89/fcs-vm-cs3035.ova?dl=1).
- Option 2: [Instructions for using the VM through Remote Desktop](https://www.cs.unb.ca/help/remote-lab-gui-access.shtml) - Follow the instructions and find the CS3035 VM.

## Git

There is a lot of software available to assist in working with Git. Our use should be relatively straightforward and so the version built into IntelliJ will be the one that is supported for the course.

## More info on Java Versions

The VM and lab computers use Java version 10.

For your own systems we recommend Java version 8.

### Why do Java Versions Matter

Java is going through some rapid changes that have made things a little complicated. The purpose of this guide is to assist you in installing a version of Java and VS Code that will work on your personal system.

One major challenge that has arisen is that beginning with Java 11, JavaFX is a separate download... getting Java 11 or later, and Java FX to work can be tough. So, we recommend using Oracle Java 8 on your personal computers, since it includes JavaFX.
