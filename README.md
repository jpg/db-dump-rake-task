DB Dump Rake Task
=================

What is this?
-------------

This is a rake task that dumps your entire database to a .sql file for your Rails environment.

Installation
------------

Copy the file db.rake into {rails project}/lib/tasks directory.

Usage
-----

    rake db:dump
    RAILS_ENV=production rake db:dump

Output
------

Creates a file called dump-env-YYYY-MM-DD.sql, where env is typically development, production, or test.

Compatibility
-------------

This works as advertised in Rails 3.2, and likely works in many other versions.

Limitations
-----------

Only works with mysql.

Author
------

[John Philip Green](https://github.com/jpg/)
