Chapter 3.1.8 LXQt sudo
=======================

LXQt-sudo is the default way to launch graphical applications with administrative privileges on Lubuntu.

Usage
------
LXQt-sudo is used to open graphical programs as an administrator. 

.. warning::

 Modifying the wrong system configuration files with adminstrator privileges could make your system unable to boot or for you to be unable to login.

To use lxqt-sudo is important to not change your config files as if you did with sudo. You will need administrative privileges to edit config files but make sure you know what you are doing. To actually use LXQt sudo you will need to type your password into the :guilabel:`Password` field and then press the :guilabel:`OK` button. To not run your command as root if you decide against it press the :guilabel:`Cancel` button. To copy the command you are running as root press the button with two sheets of paper.

Version
-------
Lubuntu ships with 0.14.1 of lxqt-sudo. 

Screenshot
----------

.. image:: lxqt-sudo.png

How to Launch
-------------
To launch lxqt-sudo from the command line to run Featherpad with administrative privileges use 

.. code::

   lxqt-sudo featherpad

You can also run lxqt-sudo from the runner for example type in

.. code:: 

   lxqt-sudo pcmanfm-qt 

into the runner to launch pcmanfm-qt with administrative privileges without opening a terminal.
