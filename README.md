# uacconfigs

The purpose of this repo is to be defintive authority for system configurations (AVL) at UAC. This includes ATEM, Dante, ColorSource, Q-SYS Core, dLive and Bose.

# Exporting Data

Every environment has its own procedure for exporting its configuration data so that it can be added to this repo.

## ATEM

Open the ATEM Control Software on CUMU-G001, and go to File -> Save Settings. Save the file as atem-master. Then copy that to a repo clone then execute git add, commit and push commands.

## GrandMA3 

Use the gear icon, upper left of screen, select "Backup", then "Save As", and then enter a file name patterned after today's data (eg 2026-10-02), and then touch "Save" in the lower right corner. (or use the command "SaveShow "2026-10-03" "). Then copy that to the repo, add, commit and push.

## Dante

Open Dante Controller on any of the production Macs and go to File -> Save Presets. Save the file as dante-master. Then copy that to a repo clone then execute git add, commit and push commands. This needs to be done when everything is turned on.

## dLive

You need to have a USB stick that you insert into USB 'Data' port on the top left corner of the surface. Press the 'Util/Shows' button. Update the 'Master' show and then copy that show to the USB stick. The file name will be ....tar.gz Then on a computer, copy the ... directory to a repo clone then execute git add, commit and push commands.

## Companion

Go to the companion website on CUMU-G001, and then to the Import/Export option on the left side. Choose "Export Configuration" and save the file as "master_config.companionconfig". 

## QSYS Core

TBD

## Bose

TBD

## ColorSource (decomissioned)

You need to have a USB stick that you insert into USB port on the back. The push the 'setup' button on the screen and ... some other keystrokes to save the show to the USB key. Then on a computer, copy the Shows directory to a repo clone then execute git add, commit and push commands.
