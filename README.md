manifest
========

AOSPSM Manifest (WIP)

How to sync and build:
----------------------
    repo init -u git://github.com/AOSPSM/manifest.git -b kitkat
    repo sync -j<DESIRED THREADS>
    . build/envsetup.sh
    lunch
    <PICK DEVICE>
    make -j<DESIRED THREADS> bacon
