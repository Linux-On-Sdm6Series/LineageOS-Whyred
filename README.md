# CyanogenMod 14.1
# LineageOS 14.1
```
repo init -u git://github.com/Linux-On-Whyred/LineageOS.git -b cm-14.1
```
```
repo sync -vc -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --single-branch
```
```
source build/envsetup.sh
lunch lineage_whyred-userdebug
mka bacon -j$(nproc --all)
```
# 
#
# 
```
lineage-16.0-srfarias-device
git clone -b lineage-16.0-srfarias-device --single-branch https://github.com/Linux-On-Whyred/LineageOS device/xiaomi/whyred
```
```
lineage-16.0-srfarias-vendor
git clone -b lineage-16.0-srfarias-vendor --single-branch https://github.com/Linux-On-Whyred/LineageOS vendor/xiaomi/whyred
```
```
lineage-16.0-MyCats-device
git clone -b lineage-16.0-MyCats-device --single-branch https://github.com/Linux-On-Whyred/LineageOS device/xiaomi/whyred
```
```
lineage-16.0-MyCats-vendor
git clone -b lineage-16.0-MyCats-vendor --single-branch https://github.com/Linux-On-Whyred/LineageOS vendor/xiaomi/whyred
```
```
lineage-15.1-LOS-device
git clone -b lineage-15.1-LOS-device --single-branch https://github.com/Linux-On-Whyred/LineageOS device/xiaomi/whyred
```
```
cm-14.1-device
git clone -b cm-14.1-device --single-branch https://github.com/Linux-On-Whyred/LineageOS device/xiaomi/whyred
```
```
cm-14.1-vendor
git clone -b cm-14.1-vendor --single-branch https://github.com/Linux-On-Whyred/LineageOS vendor/xiaomi/whyred
```
```
lineage-17.0-srfarias-device
git clone -b lineage-17.0-srfarias-device --single-branch https://github.com/Linux-On-Whyred/LineageOS device/xiaomi/whyred
```
```
lineage-17.0-srfarias-device
git clone -b lineage-17.0-srfarias-vendor --single-branch https://github.com/Linux-On-Whyred/LineageOS vendor/xiaomi/whyred
```
```
lineage-17.1-srfarias-device
git clone -b lineage-17.1-srfarias-device --single-branch https://github.com/Linux-On-Whyred/LineageOS device/xiaomi/whyred
```
```
lineage-17.1-srfarias-device-common
git clone -b lineage-17.1-srfarias-device-common --single-branch https://github.com/Linux-On-Whyred/LineageOS device/xiaomi/sdm660-common
```
```
lineage-17.1-srfarias-vendor
git clone -b lineage-17.1-srfarias-vendor --single-branch https://github.com/Linux-On-Whyred/LineageOS vendor/xiaomi/whyred
```
```
lineage-17.1-srfarias-device-old
git clone -b lineage-17.1-srfarias-device-old --single-branch https://github.com/Linux-On-Whyred/LineageOS device/xiaomi/whyred
```
```
lineage-16.0-device-common [ Need lineage-16.0-device ]
git clone -b lineage-16.0-device-common --single-branch https://github.com/Linux-On-Whyred/LineageOS device/xiaomi/sdm660-common
```
```
lineage-16.0-device [ Need lineage-16.0-device-common ]
git clone -b lineage-16.0-device --single-branch https://github.com/Linux-On-Whyred/LineageOS device/xiaomi/whyred
```
```
lineage-15.1-device
git clone -b lineage-15.1-device --single-branch https://github.com/Linux-On-Whyred/LineageOS device/xiaomi/whyred
```
```
lineage-15.1-vendor
git clone -b lineage-15.1-vendor --single-branch https://github.com/Linux-On-Whyred/LineageOS vendor/xiaomi/whyred
```
















