bpmconsoleutil
==============

A custom ant script to deploy, backup and clean temps and projects from a server. We use Jboss AS for the moment. You can run the complete script with "install" or individual targets.


#What we need?
Only an ant distribution to run the script.
And ear app
A JBoss AS

##Available targets:
```ant
	install		Install the ear(backup, cleandeploy, cleantemps, copyear)
	backup		Backup the existent ear
	cleandeploy	Delete the ear from the jobs folder
	cleantemps	Delete work, temp and data from jboss
	copyear		Copy the ear to the deploy folder
	stop-jboss	Stop the jboss
```

This use only individual and simple task like copy, delete and use the ant-zip task. No extra stuff to complicate the life.