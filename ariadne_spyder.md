# Installing Ariadne in Spyder

## Steps

* Clone the apprpriate development stream of Spyder: `git clone
https://github.com/andfoy/spyder`

* Switch to appropriate branch: `git checkout language_server_adapter`

* run development Spyder: `python bootstrap.py`

* In Spyder, find Preferences -> Language
Server Protocol Manager-> Setup a new server

* Add a server for Python that invokes the Ariadne jar
