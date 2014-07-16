SaberDroid (WIP)
================

By SaberMod and AOSPAL.


Optimizations (WIP):
--------------------

 * -O3
 * strict-aliasing (level 3)
 * odex and deodex builds
 * SaberMod GCC 4.9+ (kernel)
 * SaberMod GCC 4.8+ (ROM)
 * SaberMod GCC 4.8/4.9+ (host)
 * modular implemented via vendor
 * Graphite
 * pthread
 * gold LD


How to sync and build:
----------------------

    repo init -u git://github.com/SaberDroid/manifest.git -b <BRANCH>
    repo sync -j<#>
    . build/envsetup.sh
    lunch
    make -j<#>
    
    <BRANCH> = branch you want to use (i.e: kitkat)
    <#>      = number of threads or jobs you wish to use for syncing or building
               CAUTION: higher threads on sync will take up more bandwidth
                        & higher threads on build will use more CPU power!
