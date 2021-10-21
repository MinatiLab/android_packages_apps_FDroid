# F-Droid #
-------------------------------------------------------------------------------------------
### About F Droid ###

* F-Droid is an installable catalogue of FOSS (Free and Open Source Software) applications for the Android platform.
* Reported working fine on Android 10/11 AOSP ROMs.

## Building FDroid ##
* Clone this repository in `packages/apps/FDroid` in your ROM's Sourcecode & Build FDroid by adding following command in your Makefile.
 
```
# F-Droid
PRODUCT_PACKAGES += \
    FDroid
```

## Notes ##
* F-Droid is a FOSS Software, ( Please see https://www.f-droid.org/ for more ).
* Apk is Imported from https://f-droid.org/FDroid.apk
