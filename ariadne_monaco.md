# Installing Ariadne in Monaco

## Prerequisites

* The [Yarn](https://yarnpkg.com/lang/en/) manager for JavaScript must be installed on your system 

## Steps

### Build Client

* `cd monaco-example` in your WALA IDE directory

* `yarn install`

### Build Server

* Install server support for Tomcat 9 in Eclipse

* Import the `com.ibm.wala.cast.lsp.tomcat` project

* Add `com.ibm.wala.cast.python.ml-0.0.1-SNAPSHOT.jar` in Properties -> Deployment Assembly of that project

* Run the project on the server

### Open Editor

* In a browser, open IDE/monaco-example/lib/index.html

