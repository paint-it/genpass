PyGenpass - Command Line Password Generator and Manager Tool
============================================================

How to run project?
===================
* Create a virtual environment on your local machine

.. code-block:: bash

    $ python3 -m venv new_env


* Activate virtual environment

.. code-block:: bash

    $ source new_env/bin/activate


* Make a local directory

* Clone project in your directory

.. code-block:: bash

    $ git clone https://github.com/paint-it/pygenpass.git

* Install using pip or setup.py

.. code-block:: bash

    $ pip install pygenpass


    $ python3 setup.py install

* Use command **pygenpass**

Command line options
====================
.. code-block:: bash

    $ pygenpass

    Options:

      --help  Show this message and exit.

    Commands:
      all     Show all passwords
      create  Create new password
      delete  Delete password
      modify  Update password
      save    Save existing passwords
      show    Show password
      version  Show Version

Examples
========
* This command will ask for portal name and will create random password

.. code-block:: bash

    $ pygenpass create

    Enter portal name [None]:
    Enter email id [None]:
    Enter portal url [None]:



* This command will ask for portal name and existing password

.. code-block:: bash

    $ pygenpass save

    Enter portal name [None]:
    Enter your password [None]:
    Enter email id [None]:
    Enter portal url [None]:

* This command will show password of particular portal

.. code-block:: bash

    $ pygenpass show

    Enter portal name [None]:

Dependencies
************
=============================================      ==================
     Features                                       Dependancy
=============================================      ==================
``Scripting Language``                              Python 3.0+
``Command-Line Option and argument parsing``        click
``Database Used``                                   SQLite3
``Password generator``                              diceware
=============================================      ==================

How to contribute to this project?
==================================
* Please read `contributing.md <https://github.com/paint-it/pygenpass/blob/master/contributing.md>`_
