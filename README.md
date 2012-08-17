bpmconsoleutil
==============

A custom bpm console util in ant for common task like deploy, backup an ear app. Is very specific for our project.

##Available targets:
```ant
	install		Install the ear
	backup		Backup the existent ear
	cleandeploy	Delete the ear from the jobs folder
	cleantemps	Delete work, temp and data from jboss
	copyear		Copy the ear to the deploy folder
	stop-jboss	Stop the jboss
```
