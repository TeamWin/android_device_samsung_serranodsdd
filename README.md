## TWRP device tree for Samsung Galaxy S4 Mini (International Dual SIM)
## serranods, serranodsdd, serranodsub, serranodsxx

Add to `.repo/local_manifests/serranodsdd.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  <project name="ripee/twrp_android_device_samsung_serranodsdd" path="device/samsung/serranodsdd" remote="github" revision="android-7.1" />
</manifest>
```

Then run `repo sync` to check it out.

To build:

```sh
. build/envsetup.sh
lunch omni_serranodsdd-eng
mka recoveryimage
```

