# Installing Ariadne in Eclipse

## Prerequisites

* Eclipse Oxygen or Photon

* Eclipse needs [PyDev](http://www.pydev.org/) installed

* Eclipse must have
  [LSP4E](https://projects.eclipse.org/projects/technology.lsp4e) installed

## Steps

* Create a command for a Java 8 exeutable with arguments `-jar <your
  location of com.ibm.wala.cast.python.ml-0.0.1-SNAPSHOT.jar> --mode stdio`.

* In Preferences -> Language Servers, add that command as a server for
Python files.

* You may see more Ariadne results if you open Python files in the generic editor.
