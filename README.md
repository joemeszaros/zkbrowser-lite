ZooKeeper Browser - Lite
========================

Required Modules
----------------
* kazoo
* web.py

Installing
----------

    sudo easy_install web.py
    sudo easy_install kazoo

or

    sudo aptitude install python-webpy
    sudo aptitude install python-kazoo


Running
-------
Export environment variable ZOOKEEPER to the zookeeper client endpoint and run project

    export ZOOKEEPER=192.168.1.1:2181
    python code.py [port]

Now point your browser to http://localhost:8080. If you do not set ZOOKEEPER variable, a default Zookeeper address will be tried.

Screenshot
----------
![Sample Output](http://aminsblog.files.wordpress.com/2010/12/zkbrowser-lite.png)

