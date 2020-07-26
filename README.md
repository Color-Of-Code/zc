# ZC - ZFS Commander
An ZFS administration tool inspired on Midnight commander


## Description

ZFS Commander is a simple front-end for the most commonly used zpool & zfs commands.


## Installation 

To compile and install ZFS comamnder, run the following commands:

    $ make
    $ sudo make install
    $ make clean

To uninstall run:

    $ sudo make uninstall


## Usage

As the execution of some ZFS operations require higher privilege run ZFS commander with sudo or doas:

    $ sudo zc


### Operation

Use TAB key to switch between the modes available. Use LEFT or RIGHT keys to navigate in between the two windows.




### Function Keys per Mode

|  Key  |       Pool      |    Dataset    |    Snapshot   |     Volume    |
|:-----:|:---------------:|:-------------:|:-------------:|:-------------:|
|**F1** |         -       |        -      |        -      |        -      |
|**F2** |         -       |        -      |        -      |        -      |
|**F3** |         -       |        -      |        -      |        -      |
|**F4** |         -       |        -      |        -      |        -      |
|**F5** |         -       |        -      |        -      |        -      |
|**F6** |         -       |        -      |        -      |        -      |
|**F7** |  *zpool scrub*  |        -      |        -      |        -      |
|**F8** | *zpool destroy* | *zfs destroy* | *zfs destroy* | *zfs destroy* |
|**F9** |         -       |        -      |        -      |        -      |
|**F10**|       Exit      |      Exit     |      Exit     |      Exit     |
