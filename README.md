# local_manifest.xml
自分用LocalManifest
kltedcm for Resurrection Remix



<?xml version="1.0" encoding="UTF-8"?>

<manifest>

<project name="kbc-developers/proprietary_vendor_samsung" path="vendor/samsung" remote="github" />

<project name="CyanogenMod/android_hardware_samsung" path="hardware/samsung" remote="github" />

<project name="CyanogenMod/android_external_stlport" path="external/stlport" remote="github" />

<remove-project name="CyanogenMod/android_packages_apps_Nfc" path="packages/apps/Nfc" groups="apps_nfc,pdk-fs" />

<project name="kbc-developers/android_packages_apps_Nfc" path="packages/apps/Nfc" remote="github" />

<project name="kbc-developers/android_vendor_aojp" path="vendor/aojp" remote="github" >
<copyfile src="build.sh" dest="build.sh" />
<copyfile src="build_twrp.sh" dest="build_twrp.sh" />
</project>

<!-- kltedcm -->
<project name="kbc-developers/android_device_samsung_kltedcm" path="device/samsung/kltedcm" remote="github" />

<project name="kbc-developers/android_kernel_samsung_klte" path="kernel/samsung/klte" remote="github" />

<project name="kbc-developers/android_device_samsung_klte-common" path="device/samsung/klte-common" remote="github" />

<project name="kbc-developers/android_device_samsung_qcom-common" path="device/samsung/qcom-common" remote="github" />

<project name="CyanogenMod/android_device_samsung_msm8974-common" path="device/samsung/msm8974-common" remote="github" />

<project name="CyanogenMod/android_device_qcom_common" path="device/qcom/common" remote="github" />

<!-- sc03e -->
<project name="kbc-developers/android_device_samsung_smdk4412-common" path="device/samsung/smdk4412-common" remote="github" />

<project name="kbc-developers/android_device_samsung_smdk4412-qcom-common" path="device/samsung/smdk4412-qcom-common" remote="github" />

<project name="kbc-developers/kernel_samsung_exynos4412" path="kernel/samsung/exynos4412dcm" remote="github" />

<project name="kbc-developers/android_device_samsung_sc03e" path="device/samsung/sc03e" remote="github" />

<!-- twrp -->
<project name="omnirom/android_bootable_recovery" path="bootable/recovery-twrp" remote="github" revision="android-7.1"/>

<project name="CyanogenMod/android_external_busybox" path="external/busybox" remote="github"/>

</manifest>
