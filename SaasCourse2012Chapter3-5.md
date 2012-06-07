###Notes

* Stuff looks like they are below 3.2 which is weird, assets still sit in the assets folder in rails root
* View code written with HAML

###Trip Through a Rails App Request

1. Routes map incoming URLs to controller action and extract any optional params
1. Controller actions set instance variables to be usable with the views. All of these get smashed away in `params[]`
1. Controller action eventually render the view

###Rails Philosophy

* Convention over configuration: In Rails this really means naming follows certain conventions, therefore no need for config files
* DRY <- we know this, Don't Repeat Yourself

###Database

* Rails offers 3 separate environments that correlate to a different database for each (dev, test, production)
* Migrations change database but are really just simple scripts that describe the changes needed for the database
* Migrations are sweet because they are reversible, and version controllable, AND awesome, AND reliable/automatable
* Migrations are created through `rails g migration migrationName`
* Migration table is held around so it knows when new and already run migrations are sitting around
* Life really begins at the creation or the modification of Models/Migrations in a rails app.