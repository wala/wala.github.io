---
layout: page
title: "WALA Ariadne: Installing in PyCharm"
---

{% include downloading.md %}

## Prerequisites

* Recent PyCham

* PyCharm must have LSP plugin installed

## Steps

* Optionally, [build our modified LSP plugin for the Intellij family](/ariadne_pycharm_lsp_plugin)

* In PyCharm, find Preferences -> Languages & Frameworks -> Language
Server Protocol -> Server Definitions

* Add a `Raw command` as an absolute path to `ML/com.ibm.wala.cast.python.ml/run.sh`
