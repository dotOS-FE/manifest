dotOS Fan Edition
===========

Welcome to dotOS Fan Edition rom! Thank you for choosing us.

## Download source code ##

First, you need to prepare your build environment and download latest source code:

```bash
repo init -u https://github.com/dotOS-FE/manifest -b dot11
```

## Sync source code ##

Then, you need to sync source code:

```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

## Build it! ##

Now, you are ready! You can build Thunder-StROMs:

```bash
source build/envsetup.sh
lunch dot_<devicecodename>-userdebug
make bacon
```
-----------------------------------------------------------------------------

Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**DirtyUnicorns**](https://github.com/dirtyunicorns)
 * [**PixelExperience**](https://github.com/PixelExperience)