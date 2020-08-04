# MS Access Asset Inventory converted to Jam.py 

Welcome! 

This is the MS Access Asset Inventory (wip) converted to Web with Jam.py Application Builder:

https://msaccess.herokuapp.com/

What we see is completely automated Application from below DB model. No additional development, however it is still in WIP.

The App database design after automated conversion to Sqlite3 with ESF database migration toolkit and imported to Jam.py:

![MS Access Database](https://github.com/platipusica/AssetInventoryMSAccess/blob/master/images/MSAssetInv.png)



About Jam.py Application Builder
------------

Please visit for more info about the Jam.py:

http://jampyapplicationbuilder.com/

and more Demos:

https://jampy-aliases.herokuapp.com

https://redhatsatellite.herokuapp.com

https://sambashares.herokuapp.com/

https://jampy.pythonanywhere.com


How to run the App in *your* environment?
------------

Open https://msaccess.herokuapp.com/builder.html , click on Project/Export. The downloaded file will be used for below Import.
This procedure is applicable for any of the above Demo Applications.



Jam.py Installation
------------

### Dependencies

 * python 2.7 // python 3.x
 * For MySQL database access: mysqlclient, libmysqlclient-dev
 * For Oracle database access: cx_oracle
 * For Firebird database access: fdb
 * For Jam.py Reports editing/creation: LibreOffice

## Installing an official release with pip


The easiest is to use the standalone pip installer.

If you’re using Linux, Mac OS X or some other flavor of Unix, enter the command:
```
sudo pip install jam.py 
```
at the shell prompt. If you’re using Windows, start a command shell with administrator privileges and run the command:
```
pip install jam.py
```
This will install Jam.py in your Python installation’s site-packages directory.


## Installing an official release manually

Download the package archive from https://github.com/jam-py/jam-py/tree/master

Create a new directory and unzip the archive there.

From the above directory, enter the command:

```
sudo python setup.py install
```

This will install Jam.py in your Python installation’s site-packages directory.

## Running the Demo App

Navigate to jam.py installation demo folder, enter the command:
```
python server.py
```

You'll have the Demo App running at http://localhost:8080

## Create a new App from above Export file

```
mkdir newapp
cd newapp
jam-project.py
python server.py
```
The new and empty App will run at http://localhost:8080

Please visit http://jam-py.com/docs/intro/index.html for complete Getting Started Introduction and Import of above file.


Hopefully this helps!

License MIT, free to use.
