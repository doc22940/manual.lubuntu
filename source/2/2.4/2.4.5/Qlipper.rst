Chapter 2.4.5 Qlipper
=====================

Qlipper is the default clipboard manager for Lubuntu.

Usage
------

Qlipper is  a clipboard manager automatically started in the system tray. To view your clipboard history left click on the icon that looks like a clipboard or press :kbd:`Control+Alt+V`. To make your item from your history the selected one left click on the item of your history in the menu. If you temporarily want your clipboard history not to be saved or shown you can close Qlipper by right clicking on the clipboard icon and selecting :menuselection:`Quit`. To clear your clipboard history like if you copied a password you can right click on the clipboard history and select :menuselection:`Clear clipboard history`.

Screenshot
-----------
.. image:: qlipper.png

Customizing
-----------
If you really want an item to always show up right click on the clipboard and press the :menuselection:`Configure` then click on the :guilabel:`Sticky Items` divider and press the add button and add what you want always to be listed in Qlipper. To change how many items get displayed in qlipper in total right click on Qlipper and configure with the gear icon and change :guilabel:`Clipboard Entries Count` to your desired number of entries. To change how many characters show up on qlipper from the same configuration screen change :guilabel:`Maximum Display Size`. To change the tray icon image to something custom press the button next to :guilabel:`Tray icon image` which has an option to load a custom tray icon. This icon will bring up a dialog where you navigate to where your new icon will be. To choose your icon press the :guilabel:`Select icon` button. 
 
To synchronize your clipboard and selection clipboards check the :guilabel:`Use Platform Specific Extensitons(Advanced)` checkbox first. To toggle having your clipboard saved to storage as soon as possible check/uncheck the :guilabel:`Synchronize history to storage instantly` checkbox. Next to have two seperate clipboard synchrnoized select the :menuselection:`No synchornization of clipboard & PSE` menu item. To select an item and have uniform clipboard select :menuselction:`Synchronize clipboard & PSE instantly`. To have qlipper lose its stored history when you close Qlipper check the :guilabel:`Clear Items on Exit` checkbox. To not have whitespace after pasting each line check the :guilabel:`Trim Whitespaces for Every Line` checkbox. To change your keyboard shortcut to bring up the menu from qlipper use the :guilabel:`Keyboard Shortcut` button. To clear this keyboard shortcut press the :guilabel:`x` button to the right.

.. image:: qlipperprefrences.png

Version
-------
Lubuntu ships with version 5.1.2 of Qlipper. 

How to Launch
-------------
By default Qlipper should autostart and should be on the bottom right of your panel. If you need to get it running and it is not go to the menu :menuselection:`Accessories --> Qlipper`.
To launch it from the command line run 

.. code::

   qlipper

The icon for qlipper looks like a white piece of paper with a few lines of writing in different columns.
