# FixedTree

Nokia 2.2 TWRP Tree

Credits: Lopestom for the oukitel wp5 twrp tree i based this off

https://github.com/lopestom

***UNTESTED AS OF SPEAKING WILL BE TESTING WHEN IT BUILDS THIS WILL BE UIPDATED WHEN I HAVE TESTED IT***

***DOESNT*** BUILD!

This trees android version?

Android 11

What build?

3270 00WW

How to build?

First sync minimal omni manifests

```repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp.git -b twrp-11```

now sync

```repo sync```

Second clone this twrp tree

```git clone https://github.com/SmallPP420/FixedTree.git device/nokia/Wasp```

Now build

```export ALLOW_MISSING_DEPENDENCIES=true; . build/envsetup.sh; lunch twrp_Wasp-userdebug; mka recoveryimage```
