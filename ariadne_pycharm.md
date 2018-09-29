# Installing Ariadne in PyCharm

## Prerequisites

* Recent PyCham

* PyCharm must have LSP plugin installed

* PyCharm must be invoked in a context where JAVA_HOME points to a
Java 8 JDK

## Steps

* Optionally, [build our modified LSP plugin for the Intellij family](../ariadne_pycharm_lsp_plugin)

* In PyCharm, find Preferences -> Languages & Frameworks -> Language
Server Protocol -> Server Definitions

* Add a `Raw command` as an absolute path to `ML/com.ibm.wala.cast.python.ml/run.sh`
