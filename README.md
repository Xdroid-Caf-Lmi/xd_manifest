![XD](https://github.com/xyz-prjkt/xyz_assets/raw/main/xd_manifest.png)
# xdroidCAF | LA.QSSI.11 Android 11
an android based on CAF with Minimalist UI Design.

### Requirements
- Around 300GB disk space.
- Around 16GB RAM running Linux.

### Sync our source ###
```bash
 repo init -u https://github.com/Xdroid-Caf-Lmi/xd_manifest -b eleven
```
```bash
 repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###
```bash
 source build/envsetup.sh

 lunch xdroid_$device-userdebug

 # Or simply type lunch and pick from one of the targets

 make xd -j$(nproc --all)
```

### Credits ###
 * [**AOSP**](https://source.android.com/)
 * [**CAF**](https://source.codeaurora.org) [Old & ded]
 * [**CLO**](https://git.codelinaro.org/)
 * [**ConquerOS**](https://github.com/ConquerOS)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**DotOS**](https://github.com/DotOS)
 * [**Project404**](https://github.com/P-404)
 * [**POSP**](https://github.com/PotatoProject)

  .....and many more
