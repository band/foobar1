## 2021-04-26

Notes and observations on implementing PK's Massive Wiki Builder (MWB) software. These notes are particular to my own macOS computing setup.

1. Pre-requisites:
	- an existing Massive Wiki folder of markdown content
	- the Massive Wiki has a GitHub backup repository
	- Python3 installation (including pip)
	- Python virtual environment experience
2. Building a working model of using Python virtual environments
	- 
	- run the python code in a virtual environment; it is an extra step.
	- a good working practice is to activate a virtual environment in every directory that is the root for a Massive Wiki using this command:
	   `python3 -m venv venv`
	 - this create a `venv` directory containing the venv commands.
	 - update the `.gitignore` 