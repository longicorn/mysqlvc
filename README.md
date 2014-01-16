mysqlvc -- MySQL Version Controller
=====================

mysqlvc is MySQL Version Controller.

Installation
------------
    # git clone
    $ git clone git@github.com:longicorn/mysqlvc.git /path/to/mysqlvc/

    # set PATH
    $ export PATH=/path/to/mysqlvc/bin:$PATH
    $ export PATH=/path/to/mysqlvc/libexec:$PATH

    # set library path on Linux
    $ export LD_LIBRARY_PATH=$HOME/.mysqlvc/lib:$LD_LIBRARY_PATH
    # set library path on Mac
    $ export DYLD_LIBRARY_PATH=$HOME/.mysqlvc/lib:$DYLD_LIBRARY_PATH
    or
    $ export DYLD_FALLBACK_LIBRARY_PATH=$HOME/.mysqlvc/lib:$DYLD_FALLBACK_LIBRARY_PATH

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

    $ mysqlvc use

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
