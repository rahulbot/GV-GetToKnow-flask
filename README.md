Flask Example - Get To Know : Global Voices
===========================================

Small example Flask applicaton for the MAS.s60 course.

Installation
------------

Make sure you havy Python 2.7 (and the pip package manager).

You also need to install the flask and feedparser libraries

```
pip install flask
pip install feedparser
```

Use
---

Run this command and then visit `localhost:5000` with a web browser

```
python gettoknow.py
```

Deploying
---------

First, prep your Ubuntu machine:
```
sudo aptitude install python
sudo aptitude install libapache2-mod-wsgi
sudo easy_install pip
sudo pip install feedparser
sudo pip install flask
```

Now follow the instructions for Configuring Apache:
  http://flask.pocoo.org/docs/deploying/mod_wsgi/

