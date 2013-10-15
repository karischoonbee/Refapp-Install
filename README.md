HOWTO Setup OpenMRS EMR 2.0
===========================

Prerequisites
-------------

The following applications need to be installed already:

1. MySQL Server
2. Tomcat

Install Process
---------------

### Option 1

1. Prevent clashes with any previous installs by first renaming your ".OpenMRS folder" (the one
that contains the .properties file) or rename the openmrs.war file before staring the setup.
2. Copy the (possibly renamed) openmrs.war file to Tomcat's webapps directory (or upload it via the
web interface).
3. Make sure you do a clean setup and create a new blank database.
4. Copy the modules from the refapp-modules.zip file to your ".OpenMRS/modules folder"
5. Restart Tomcat


### Option 2 (more hacky)

1. Restore the database in refapp-database-latest.sql
2. Copy the (possibly renamed) openmrs.war file to Tomcat's webapps directory (or upload it via the
web interface).
3. Copy the modules from the refapp-modules.zip file to your ".OpenMRS/modules folder"
4. Restart Tomcat
