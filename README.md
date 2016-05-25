# twrp
repo init -u git://github.com/lj50036/platform_manifest_twrp_omni.git -b twrp-6.0
repo sync
 cd <source-dir>; . build/envsetup.sh; lunch omni_<device>-eng; mka recoveryimage
