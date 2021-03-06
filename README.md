# The Code for America Brigade Website

## V3

This is the working branch for the third version of the Code for America Brigade website. 

V2 Can be found at http://www.codeforamerica.org/brigade/ and https://github.com/codeforamerica/brigade-alpha

V1 Can be found at http://old-brigade.codeforamerica.org/ and https://github.com/codeforamerica/brigade/tree/master

## Why

V1 Was a Rails site with many contributors. It served the Brigade well as it was growing. As Code for America became better at supporting the  volunteer groups, we needed something different.

The [CfAPI](http://github.com/codeforamerica/cfapi) was built as reaction to how Brigades were operating themselves. We now meet them where they are, instead of trying to get them to log into our site.

V2 was powered by the CfAPI and worked great, yet was built quickly with PHP and Javascript. It was kind of a cobweb of dependent parts.

V3 is meant to simplify the code and make it easier for Brigade members to get involved.

## Installation

The Code for America Brigade site is built on [Flask](http://flask.pocoo.org/) and Python with a little bit of Javascript. The `app.py` file describes the routes. The `templates` have the html.

* Set up a [virtualenv](https://pypi.python.org/pypi/virtualenv)

```
pip install virtualenv
virtualenv .venv
source .venv/bin/activate
```

* Install the required libraries

```
pip install -r requirements.txt
```

* To run locally

```
python app.py
```

Contacts
--------

* Andrew Hyder ([ondrae](https://github.com/ondrae))

Copyright
---------

Copyright (c) 2015 Code for America.