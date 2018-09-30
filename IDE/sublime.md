---
layout: page
title: "WALA Ariadne: Installing in Sublime"
---

{% include downloading.md %}

## Prerequisites

* Sublime Text 3

## Steps

* In your Sublime packages directory (`~/Library/Application
Support/Sublime Text 3/Packages` on the Mac), `git clone
https://github.com/sourcegraph/sublime-lsp`

* Copy or link `sublime/LSP.sublime-settings` from your WALA IDE to
  ~/Library/Application Support/Sublime Text 3/Packages/User/LSP.sublime-settings (on the Mac)

* Edit that file to set the JDK home and `com.ibm.wala.cast.python.ml-0.0.1-SNAPSHOT.jar` to their locations on your system
