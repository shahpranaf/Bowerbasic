# Bowerbasic
Working with Bower Demo - IMP Commands
===========================================

npm install bower -g
 
bower install jquery
bower install jquery#2.2.1
bower uninstall jquery
 
bower info jquery -> know all version available
 
bower update -> Update all
bower update jquery -> Update single library
 
bower list -> Packages installed in prjct
 
bower init -> to generate bower.json
 
.bowerrc -> File to change location of package
 
bower install jquery --save -> To add dependency in bower.json
bower install jquery --save -dev -> to add to dev dependency list in bower.json
 
bower uninstall jquery --save -> To remove dependency in bower.json
 
bower cache list
bower cache clean
 
bower install jquery -o  -> offline mde - install from cache
 
bower help
bower help install
 
bower info jquery
bower info jquery#1.9.0
 
bower lookup angular -> To look git repo
 
bower prune -> remove extraneous package
 
Flags
==================================================================
bower install jquery -q -> Quiet install
bower install jquery -s-> Very silent
bower install jquery -v-> Verbose same as regular
bower install jquery -j > output.json


bower register <name>
