---
layout: page
title: "WALA Ariadne: Installing in Spyder"
---

{% include downloading.md %}

 You need to use the development version of Spyder currently; even the
latest Spyder 4.0.0 beta does not seem expose LSP support.
 
## Steps

* Clone the development stream of Spyder: `git clone
https://github.com/spyder-ide/spyder`

* Run development Spyder: `python3 bootstrap.py`

* In Spyder, find Preferences -> Language
Server Protocol Manager-> Setup a new server

* Add a server for Python that invokes the Ariadne jar:
  * Language: `Python`
  * Address: `localhost:<port>`
  * Command to execute: `<JAVA_HOME>/bin.java -jar <ariadne jar> --mode server --port <port>`
