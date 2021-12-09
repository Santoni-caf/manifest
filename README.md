Santoni CAF
===========

Getting started
---------------

To get started with Android/LineageOS, you'll need to get
familiar with [Repo](https://source.android.com/source/using-repo.html) and [Version Control with Git](https://source.android.com/source/version-control.html).

To initialize your local repository using the LineageOS trees, use a command like this:
```
repo init --depth=1 -u https://github.com/Santoni-caf/manifest
```
Then to sync up:
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
