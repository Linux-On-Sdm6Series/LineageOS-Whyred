# CyanogenMod 14.1
#
# LineageOS 14.1
#
```
repo init -u git://github.com/Linux-On-Whyred/LineageOS.git -b cm-14.1
```
#
```
repo sync -vc -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --single-branch
```
#
```
source build/envsetup.sh
lunch lineage_whyred-userdebug
mka bacon -j$(nproc --all)
```





















