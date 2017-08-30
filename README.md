The PureNexus Project
=====================

Getting Started
---------------

To build PureNexus from source, you'll need to be familiar with
[Git and Repo](http://source.android.com/download/using-repo).


To initialize your local repository, use this command:

	repo init -u https://github.com/PureNexusProject/manifest.git -b o

Then to sync source, use this command:

	repo sync

After syncing is done, do one of the following to build:

    bash build.sh --help

OR

    1.) . build/envsetup.sh
    2.) brunch xxxx yyyy
    
    xxxx= device name aka shamu
    yyyy= build type (user,userdebug,eng)*

    *if no build type is specified "user" is default

Enjoy, Stick around for a while AOSP Building is Fun!!!

[PureNexus Community](https://plus.google.com/u/0/communities/103055954354785266764) on Google+

[PureNexusProject-Legacy](https://github.com/PureNexusProject-Legacy) Old Source and Reference code
