Get a copy of backup-unagi

    Choose Open with Archive Manager
    Once the Archive Manager starts up, extract the directory to build-b2g/B2G
    Run export ANDROIDFS_DIR=~/build-b2g/B2G/backup-unagi 

Build

    Switch to your terminal
    Run ./config.sh unagi (this will take about an hour)
    Run ./build.sh (this will take even longer) 

Flash

    Disconnect your device
    Remove and re-insert the battery of the device
    Follow the steps in the section Connect the Unagi
    Run ./flash.sh (this will take a couple of minutes) 

That's it!

Power on the device and enjoy using Firefox OS! 
