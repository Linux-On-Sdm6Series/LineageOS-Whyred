# CyanogenMod 14.1   |   LineageOS 14.1

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
export JACK_SERVER_VM_ARGUMENTS="-Dfile.encoding=UTF-8 -XX:+TieredCompilation -Xmx4g"
jack-admin kill-server && jack-admin start-server
lunch lineage_whyred-userdebug
mka bacon -j$(nproc --all)
```





















