This repository contains scripts.js and tiers.xml used in Pokemon Online Server.

*** Installation instructions ***

Download as .zip (https://github.com/horou-dev/po-boilerplate/zipball/master) or tarball,
extract into the same folder with Pokemon-Online server executable.
Note: some builds on Windows systems (2.0.0x) are missing the SSL libraries making
the scripts impossible to reload from Github. (/updatescripts, /updatetiers etc.)

Forking the repo is recommended as these scripts contain hardcoded configuration parameters
only suitable for the server we are running.

*** Guidelines for contributors ***

USE THE TAB CHARACTER. The scripts use tabs and the mix of tab and spaces is what
causes the formatting issues at times.
You can set Notepad++ to use 4 spaces when the tab key is hit though if you use that to edit.
Settings->Preferences->Tab Settings

Using jshint for checking some coding style is recommended.
In particular, following practices are frowned upon:
- trailing whitespace
- undefined variables (always use var in the outermost scope for that variable)

Full list of contributors here: https://github.com/horou-dev/po-boilerplate/graphs/contributors with credit to https://github.com/po-devs/po-server-goodies/graphs/contributors
