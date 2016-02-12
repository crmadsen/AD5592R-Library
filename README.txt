### Installation

1. If an external library folder has been created and added to EAGLE already, skip to step 6. 
2. In EAGLE, click on Options - Directories
3. Add the following to the Libraries line:

    > $EAGLEDIR\lbr;$HOME\external_lbrs (Windows)

    > $EAGLEDIR/lbr:$HOME/external_lbrs (OS X)

4. Click 'OK' to save changes.
5. Eagle will prompt to create the directory if it does not already exist. Note 
the location and choose 'Yes' to create the directory.
6. Find and open the 'external_lbrs' folder. Unzip and drag 'adafruit.lbr' into the 
   new 'external_lbrs' folder.
7. Restart Eagle. The library should be now be usable.

(README file modified from GitHub user davidk)
