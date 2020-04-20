# Almazen
Cloud service for home inventory

Ever wondered if there were still some aspirins 
left? Or whether your stock of beers requires 
some reload? Almazen is a web service that 
helps you keep your home inventory up to date.

## Features

This app is yet to be developed. This is a 
list of features we want to have implemented 
in a first development cycle.

* User access to inventory is private and 
secure.
* User can have inventories of different
locations. A location may be a room, a closet...
* User can have inventories of different
categories. For instance, medicines, food, etc.
* User can add, edit and remove items from
inventories.
* User can search for a product name.
* User can query for all products in all his/
her locations and or categories.

## Software components

The core element of Almazen is a MySQL database.
 This database is manipulated through a Python 
API. Several components might act as frontend. 
The easiest seems to be a web app. But desktop 
or mobile apps might be nice to have too.

A first implementation of Almazen will provide
only the Python API and the DB. Source code for
these components can be found in these repos:

* MySQL [database](https://github.com/samueloquien/almazen-db).
* Python [API](https://github.com/samueloquien/almazen-api).
