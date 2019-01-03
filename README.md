# Generic List Notes app example

A starter app for a Vue Pouchdb Couchdb PWA. This is specifically a generic notes app.

Copy this app and edit it to whatever specific need you have.

## install and startup

 - clone repo https://github.com/dgleba/gen-list-notes.git
 - copy .env.example to .env
 - edit .env
 - edit docker-compose.yml -- edit labels for caddy
 - make gc  ( start genlist and couchdb - but not caddy-gen just yet. )
 - adjust to get that working.
 - docker-compose up   -- to start everything
 
 
 - visit couch at:  http://192.168.88.42:6222/
 - http://192.168.88.42:6222/_utils/#login
 - visit app at: http://192.168.88.42:6221 
 

## Features

 - offline
 - syncs to couchdb
 - autocomplete from user defined list
 - search notes (the main table in this case)
 - login feature to know who edited what information.
 
 
## App design

 - The main table has the notes and most info. The main table is the notes table in this example.
 - autocomplete info like category or tag is copied into the main table from supporting lists.
 
 