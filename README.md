                                                    >>  DevilianOS <<

An AOSP based rom.

Please read the [AOSP building instructions](http://source.android.com/source/index.html) before proceeding.

# ======== # ======== # ======== # ======== #

To initialize your local repository, use this command:

    $  repo init -u https://github.com/DevilianOS-Project/manifest -b pie

To sync the repository, use this command:

    $  repo sync --force-sync

To Build, use following command this will create the required environment.

    $  build/envsetup.sh 
    
For Official Devices
This command will load all of our proprietary makefiles for compiling
Run this command:
    $  lunch && make bacon

For unofficial builds.
Change device with your device code name. Ex.- mido, tissot, dumpling, etc.
    $  lunch_<devicecodename>-<userdebug/eng) && make bacon

# ======== # ======== # ======== # ======== #
