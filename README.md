platform_manifest
=================
Android for Samsung Ace (cooper)

$ repo init -u git://github.com/utak3r/platform_manifest.git -b AOKP-legacy

$ repo sync

$ source build/envsetup.sh

$ lunch aokp_cooper-userdebug

$ make -j2
