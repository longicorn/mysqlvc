mysqlvc -- MySQL Version Controller
=====================

mysqlvc is MySQL Version Controller.

Installation
------------
    $ git clone git@github.com:longicorn/mysqlvc.git
    $ export PATH=/path/to/mysqlvc:$PATH
    $ mysqlvc init

Commands
------------
MySQL version list

    mysqlvc install list

Install MySQL

    $ mysqlvc install 5.6.14

Set global version

    $ mysqlvc use 5.6.14

Check current MySQL version

    $ mysqlvc curren

        5.6.14

Make Databae

    $ mysqlvc cluster create master

MySQL cluster start

    $ mysqlvc cluster start master

MySQL cluster stop

    $ mysqlvc cluster stop master

MySQL cluster delete
    $ mysqlvc cluster delete master

Settings
------------
msv/clusters/"version"/"cluster_name"/my.cnf
