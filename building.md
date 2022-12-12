---
layout: page
title: "Building WALA"
sidebar-title: "Building"
---

* You must install these projects in order, as there are dependences

## Prerequisites 

* Installed JDK 8, with JAVA_HOME pointing to it 

* Installed Android SDK, including version 26.0.2, with ANDROID_HOME pointing to it 

* Recent Apache Maven on path 

## Building WALA Core 

* `git clone https://github.com/wala/WALA`

* `cd WALA`

* `./gradlew build`

* `mvn clean install -DskipTests`

## Building WALA IDE 

* `git clone https://github.com/wala/IDE`

* `cd IDE/com.ibm.wala.cast.lsp`

* `mvn clean install`

## Building WALA ML

* `git clone https://github.com/wala/ML`

* `cd ML`

* `mvn clean install`
