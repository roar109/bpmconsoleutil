bpmconsoleutil
==============

A custom ant script to deploy, backup and clean temps and projects from a server. We use Jboss AS at the moment. You can run the complete script with "install" or individual targets.


##What we need?
Only an ant distribution to run the script, an ear app and a JBoss AS.

Available targets:
--------------
```ant
	install		Install the ear(backup, cleandeploy, cleantemps, copyear).
	backup		Backup the existent ear.
	cleandeploy	Delete the ear from the jobs folder.
	cleantemps	Delete work, temp and data from jobs.
	copyear		Copy the ear to the deploy folder.
	stop-jboss	Stop the jboss as.
```

This ant archive use only individual and simple tasks like copy, delete and ant-zip. No extra stuff to complicate the life.

Libraries used
--------------
* [Ant Contrib](http://ant-contrib.sourceforge.net/)