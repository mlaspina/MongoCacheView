# MongoCacheView
See what is in your MongoDB WT Cache and how it's being used.

usage:

&nbsp;&nbsp;&nbsp;&nbsp;**display in mongo shell:** mongo "*connection string*" mongoCacheView.js

&nbsp;&nbsp;&nbsp;&nbsp;**output in json format:** mongo "*connection string*" --eval "var format='Json'" mongoCacheView.js > *file.out*
