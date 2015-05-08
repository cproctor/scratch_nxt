Scratch NXT Extension
=====================

The Scratch NXT Extension is a helper app which allows you to control a LEGO
MINDSTORMS XNT brick using Scratch. 

Installation & Setup
--------------------

1. Install the Scratch 2 Offline Editor. Instructions are here:
   http://scratch.mit.edu/scratch2download/
   (If OS X tells you it cannot be installed because it's from an unidentified
   developer, open System Preferences and select the "Security and Privacy" 
   pane.)

2. Install the Scratch NXT Extension by running these commands in Terminal.
   When you are asked to enter your password, you will not see the letters
   you type appear on the screen. This is normal.

        sudo easy_install pip
        sudo pip install scratch_nxt_extension

4. Start the Scratch Hue Helper by running this command in Terminal. Right
   before you run this for the first time, press the button on the Hue Base
   Station in Room 6.

        scratch_nxt_helper

5. Start the Scratch 2 Offline Editor. Then, holding down the shift key, click 
   on the "File" menu and select "Import Experimental HTTP Extension." You will 
   be asked to select a file; choose the file called "scratch_nxt_extension.s2e"
   on your Desktop.

6. Now you can control a NXT block using Scratch. Look in
   the "More Blocks" pane to see the available commands.


About
-----

This package provides a helper app to allow the Scratch 2 Offline Editor to 
control a NXT brick. Instructions for implementing 
a helper app are at http://wiki.scratch.mit.edu/w/images/ExtensionsDoc.HTTP-9-11.pdf.

This extension was written by Chris Proctor, who teaches 6th and 7th grade 
Computer Science at the Girls' Middle School in Palo Alto, CA.
