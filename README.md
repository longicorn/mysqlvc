mysqlvc -- MySQL Version Controller
=====================

mysqlvc is MySQL Version Controller.

Installation
------------
    $ git clone git@github.com:longicorn/mysqlvc.git /path/to/mysqlvc/
    $ export PATH=/path/to/mysqlvc/bin:$PATH
    $ export PATH=/path/to/mysqlvc/libexec:$PATH
    $ mysqlvc init

Commands
------------
MySQL version list

    mysqlvc install list

Install MySQL

    $ mysqlvc install 5.6.14

Set global version

    $ source /path/to/mysqlvc/versions/VERSION/env

Check current MySQL version

    $ mysqlvc current

        5.6.14

Make Databae

    $ mysqlvc cluster create master

MySQL cluster start

    $ mysqlvc cluster start master

MySQL cluster use console

    $ mysqlvc cluster use master

MySQL cluster stop

    $ mysqlvc cluster stop master

MySQL cluster delete
    $ mysqlvc cluster delete master

Settings
------------
clusters/VERSION/CLUSTER_NAME/my.cnf
