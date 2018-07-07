# Installing Ariadne in JupyterLab

## Prerequisites

* The [Yarn](https://yarnpkg.com/lang/en/) manager for JavaScript must be installed on your system 

## Steps

### Build Client

* `git clone https://github.com/juliandolby/jupyterlab-monaco`

* `cd jupyterlab-monaco`

* `yarn install`

* `yarn run build`

* `jupyter labextension link`

### Build Server

* Install server support for Tomcat 9 in Eclipse

* Import the `com.ibm.wala.cast.lsp.tomcat` project

* Add `com.ibm.wala.cast.python.ml-0.0.1-SNAPSHOT.jar` in Properties -> Deployment Assembly of that project

* Run the project on the server

### Open Editor

* In the jupyterab-monaco directory, `jupyter lab`

