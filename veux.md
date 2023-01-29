![Device Changelog](https://github.com/Evolution-X/manifest/raw/tiramisu/EvoBanner.png)

## v7.5 Veux/Peux
```
veux: Use dex2oat64
veux: Update blobs from latest global
veux: Set block_binder_thread_on_incoming_calls prop
veux: overlay: Keep raw value for the carrier config overlay
veux: Set auto brightness mode on by default
veux: wifi: Switch gEnablePowerSaveOffload to 5
veux: wifi: Smarter decisions on whether to use 2/5Ghz AP
veux: wifi: Remove entry for gEnableNUDTracking
veux: wifi: Disable RX wakelock feature
veux: wifi: Enable QPower and Deep sleep at the same time
veux: wifi: Increase max bss count
veux: wifi: Add parameters for Hotspot 2.0
veux: wifi: No BSS flush for 2018 devices
veux: Stop explicitely building netutils-wrapper-1.0
veux: Build mtdservice interface lib from source
veux: Switch to source-built mlipay interface
veux: Move to common IFAAService
veux: Set BUILD_BROKEN_VENDOR_PROPERTY_NAMESPACE
veux: sepolicy: Label more camera props
veux: Move fastrpc_shell_3 init to post-fs
veux: sepolicy: Allow camera hal to read mnt_vendor_file
veux: sepolicy: Label soc:fpc1020/wakeup_enable
veux: Reformat sepolicy file
veux: Update mi_thermald sepolicy from sm6375-common
veux: sepolicy: Don't grant system_server access to fingerprint props
veux: sepolicy: Label fingerprint props as restricted vendor
veux: sepolicy: Switch to lineage hal macros for mlipay attribute def…
veux: Add missing mlipay sepolicy from Xiaomi-SM8250 tree
veux: sepolicy: Allow platform app to find SoterService
veux: Move to common Xiaomi fingerprint HIDL
veux: overlay: Configure additional camera framerates
veux: overlay: Configure aux camera for Aperture
veux: Enforce RRO for all resource overlays
veux: Enable set channel on NDP setup
veux: wifi: Configure correct overlay configuration.
veux: Enable zygote critical window
veux: gps: Update to LA.UM.9.14.r1-19200.02-LAHAINA.QSSI13.0
veux: qcc-tr: Define new AID for qcc-trd
veux: config.fs: Add mapping for imsdaemon
veux: config.fs: init: add AID_VENDOR_FASTRPC group for fastrpc
veux: Slim up filesystem configuration
veux: Use RSA4096 key also for vbmeta_system
veux: Removing GSI keys
veux: Switch BtAudio to AIDL
veux: Drop qti thermal 2.0 service hals
veux: Remove non-existing or implicitly included IPACM packages
veux: Remove A2DP input module in audio policy configuration
veux: extract-files: Allow extracting proprietary-files for recovery
veux: Add Aperture to config_cameraAuxPackageAllowList
veux: Migrate vendor.camera.aux.packagelist to overlay
veux: Remove QTI BT stack bits
veux: Move BT profiles props to vendor
veux: overlay: Remove BT related configs
veux: Remove Bluetooth power overlays
veux: Don't override bluetooth name on recovery
```
