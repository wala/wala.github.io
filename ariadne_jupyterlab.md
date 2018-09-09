# Installing Ariadne in JupyterLab

## Prerequisites

* The [Yarn](https://yarnpkg.com/lang/en/) manager for JavaScript must be installed on your system 

* [JupyterLab](https://blog.jupyter.org/jupyterlab-is-ready-for-users-5a6f039b8906) must be installed

* J2EE server that supports WebSockets.  We have successfully used
Tomcat 9

## Steps

### Build Client

* `git clone https://github.com/juliandolby/jupyterlab-monaco`

* `cd jupyterlab-monaco`

* `yarn install`

* `yarn run build`

* `jupyter labextension link`

### Get Ariadne for WebSockets

* Download [WALA Ariadne J2EE war](https://github.com/wala/ML/blob/gh-pages/com.ibm.wala.cast.python.ml.j2ee/target/com.ibm.wala.cast.python.ml.j2ee-0.0.1-SNAPSHOT.war?raw=true)

* Deploy WAR file as `wala-ariadne.war` to server; for Tomcat, copy to webapps directory

* Run server

### Open Editor

* In the jupyterab-monaco directory, `jupyter lab`

* If needed, adjust the WAR file URL in `Settings -> Advanced Settings
  Editor -> Monaco Editor -> lspServer`.  The protocol must be `ws`
  and check the hostname, port and path.  For Tomcat 9, the path
  should be `wala-ariadne/websocket`
