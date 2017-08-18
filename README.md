# Quake Info

## An Amazon Alexa Skill using the public USGS Earthquake Data

## To Build

* `cd /gitlab/quakeinfo`
* `pip install virtualenv`
* `virtualenv ./venv`
* `source venv/bin/activate`
* `pip install requests`
* `cd venv/lib/python2.7/site-packages/`
* `zip -r9 ~/gitlab/quakeinfo/quakeinfo.zip *`
* `cd ~/gitlab/quakeinfo/`
* `zip -g quakeinfo.zip app.py`

Can just keep running the last command when changes are made. 

