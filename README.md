Getting Started
---------------
**To initialize your local repository, use command:**
```bash
repo init -u https://github.com/SerasaOS/android_manifest.git -b unsub --git-lfs
```

**Sync up with this command:**
```bash
repo sync -c --no-clone-bundle --optimized-fetch --prune --force-sync -j$(nproc --all)
```

Building the System
-------------------
 **Initialize the ROM environment with the envsetup.sh script.**
```bash
. build/envsetup.sh
```

**Lunch your device after cloning all device sources if needed.**
```bash
lunch morbid_devicecodename-buildtype
```

**Start compilation**
```bash
mka bacon
```

Credits
---------------
* [**AOSPA**](https://github.com/AOSPA)
* [**crDroid**](https://github.com/crdroidandroid)
* [**DotOS**](https://github.com/DotOS)
* [**LineageOS**](https://github.com/LineageOS)
* [**PixelStar**](https://github.com/Project-PixelStar)
* [**Project Kaleidoscope**](https://github.com/Project-Kaleidoscope)
* [**Xdroid-OSS**](https://github.com/xdroid-oss)
