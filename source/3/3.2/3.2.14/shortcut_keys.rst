Chapter 3.2.14 Shortcut Keys
============================

Shortcut Keys is the program that manages the global hotkeys or keyboard shortcuts for Lubuntu.

.. note::
    The keyboard shortcuts are also managed by Openbox. Refer to Appendix F for more detail.

Usage
------
You can **Modify** a current keyboard shortcut by selecting the shortcut from the keyboard table, clicking the :guilabel:`Modify` button, then clicking on the shortcut button. A countdown will begin during which you should push the **keyboard shortcut combination** you want.  

You can **Remove** a keyboard shortcut by selecting the shortcut from the keyboard table, and clicking the :guilabel:`Remove` button. To swap to shortcut keys you can select two shortcuts with :kbd:`Control+ Left Click` then left click on the :guilabel:`Swap` button.

You can **Add** a new keyboard shortcut clicking the :guilabel:`Add` button. The shortcut field will be blank, click the :guilabel:`Shortcut` button to start the countdown, then press the **keyboard shortcut combination** you want to assign. Write a short description of what the keyboard shortcut does, for example "start drop down terminal", or "increases screen brightness" in the :guilabel:`Description` field. To make this execute a terminal command select the :guilabel:`command` radio button and enter the command.

To close shortcut keys press the :kbd:`Escape` key.

Screenshots
-----------

.. image:: shortcut_keys.png

.. image:: add_key_ex.png

Version
-------
Lubuntu ships with version 0.14.1 of Shortcut Keys.

How to Launch
-------------
To launch Shortcut Keys from the menu :menuselection:`Preferences --> LXQt settings --> Shortcut Keys`. The icon for Shortcut Keys button which looks like a keyboard. To launch Shortcut Keys from the command line run

.. code:: 

   lxqt-config-globalkeyshortcuts 
