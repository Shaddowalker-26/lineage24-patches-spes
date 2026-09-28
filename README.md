# LineageOS 24.0 Custom Patches for Redmi Note 11 (spes)

These patches contain the custom changes used for the LineageOS 24.0
spes build.

## Patches

- `frameworks-base-Lineage24-custom.patch`
  - FLAG_SECURE ignore support
  - Three-finger screenshot framework support
  - Volume panel QS tile

- `Settings-Lineage24-custom.patch`
  - Three-finger screenshot Settings
  - FLAG_SECURE Settings toggle
  - Hotspot connected devices
  - Hotspot blocked devices
  - Hotspot maximum connected devices
  - Required Settings resources and assets

## Apply

From the LineageOS source root:

    cd frameworks/base
    git apply ../lineage24-patches/frameworks-base-Lineage24-custom.patch

    cd ../../packages/apps/Settings
    git apply ../../lineage24-patches/Settings-Lineage24-custom.patch

## SHA-256

Settings:
e9db9cc5a11f09995d7036d6fb1e584a60f12afbb0688b5a639524a5dd02766a

frameworks/base:
58e2fe3af2ac3fa03b796aaac0a16cf1c65e6ff8275df7895feddb8966336f21
