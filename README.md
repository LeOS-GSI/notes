 

## DEVICE TREES ##
git clone https://github.com/oxygen-pie/bootleggers_device_xiaomi_oxygen.git -b pie device/xiaomi/oxygen && git clone https://github.com/oxygen-pie/device_xiaomi_msm8953-common.git -b pie device/xiaomi/msm8953-common && git clone https://github.com/blackmiddow/vendor_xiaomi_oxygen.git -b pie vendor/xiaomi && git clone https://github.com/blackmiddow/kernel_xiaomi_oxygen.git -b pie kernel/xiaomi/msm8953


## nougat trees
##   git clone https://github.com/kenzolo/android_device_xiaomi_oxygen.git -b cm-14.1 device/xiaomi/oxygen && git clone https://github.com/ashwinr64/android_vendor_xiaomi_oxygen.git -b cm-14.1 vendor/xiaomi/oxygen && git clone https://github.com/rakeshraimca/Xiaomi_Nougat_oxygen-.git -b nougat kernel/xiaomi/msm8953    ##

## Carbon Beta rom hals ##

###   rm -rf hardware/qcom/audio && git clone https://github.com/CarbonBeta/android_hardware_qcom_audio.git -b cr-7.0 hardware/qcom/audio && rm -rf hardware/qcom/media && git clone https://github.com/CarbonBeta/android_hardware_qcom_media.git -b cr-7.0 hardware/qcom/media && rm -rf hardware/qcom/display && git clone https://github.com/CarbonBeta/android_hardware_qcom_display.git -b cr-7.0 hardware/qcom/display && rm -rf hardware/qcom/audio-caf/msm8996 && git clone https://github.com/CarbonBeta/android_hardware_qcom_audio.git -b cr-7.0-caf-8996 hardware/qcom/audio-caf/msm8996 && rm -rf hardware/qcom/media-caf/msm8996 && git clone https://github.com/CarbonBeta/android_hardware_qcom_media.git -b cr-7.0-caf-8996 hardware/qcom/media-caf/msm8996 && rm -rf hardware/qcom/display-caf/msm8996 && git clone https://github.com/CarbonBeta/android_hardware_qcom_display.git -b cr-7.0-caf-8996 hardware/qcom/display-caf/msm8996 && rm -rf vendor/qcom/opensource/interfaces && git clone https://github.com/blackmiddow/android_vendor_qcom_opensource_interfaces.git -b pie vendor/qcom/opensource/interfaces   ###

## android file host upload link-- ##
curl --ftp-pasv -T RevengeOS-2.2-Pasta-UNOFFICIAL-h930-20190103-0741.zip ftp://Scissordragonboy:IOs3gFSCyEtv@uploads.androidfilehost.com

## Havoc-OS device tree

## git clone https://github.com/blackmiddow/havoc_device_xiaomi_oxygen.git -b havoc device/xiaomi/oxygen && git clone https://github.com/blackmiddow/device_xiaomi_msm8953-common.git -b havoc device/xiaomi/msm8953-common && git clone https://github.com/Mohzunedbrt/Vendor_xiaomi_common.git -b arrow-9.x vendor/xiaomi && git clone https://github.com/rakeshraimca/Kernel_xiaomi_oxygen.git -b lineage-16 kernel/xiaomi/msm8953  ##


## search and replace-- ##
 ##  find . -maxdepth 1 -type f -exec sed -i 's/foo/bar/g' {} \;  ##

## important booting hals

## rm -rf hardware/qcom/wlan && git clone https://github.com/sandyorton7/wlan hardware/qcom/wlan && rm -rf hardware/qcom/power && git clone https://github.com/sandyorton7/power hardware/qcom/power && rm -rf hardware/qcom/bt && git clone https://github.com/sandyorton7/bt hardware/qcom/bt ##


## rm -rf hardware/qcom/audio && git clone https://github.com/sandyorton7/audio hardware/qcom/audio && rm -rf hardware/qcom/media && git clone https://github.com/sandyorton7/media hardware/qcom/media && rm -rf hardware/qcom/display && git clone https://github.com/sandyorton7/display hardware/qcom/display ##


###    nano vendor/xiaomi/msm8953-common/Android.mk

###   nano device/xiaomi/oxygen/camera/QCamera2/Android.mk

###   nano device/xiaomi/oxygen/vendorsetup.sh

###   nano device/xiaomi/oxygen/aosp_oxygen.mk

###   nano vendor/aosp/vendorsetup.sh    

###   cd vendor/aosp/config

###   rm -rf hardware/qcom/audio && git clone https://github.com/CarbonBeta/android_hardware_qcom_audio.git -b cr-7.0 hardware/qcom/audio && rm -rf hardware/qcom/media && git clone https://github.com/CarbonBeta/android_hardware_qcom_media.git -b cr-7.0 hardware/qcom/media && rm -rf hardware/qcom/display && git clone https://github.com/CarbonBeta/android_hardware_qcom_display.git -b cr-7.0 hardware/qcom/display && rm -rf hardware/qcom/audio-caf-msm8996 && git clone https://github.com/CarbonBeta/android_hardware_qcom_audio.git -b cr-7.0-caf-8996 hardware/qcom/audio-caf-msm8996 && rm -rf hardware/qcom/media-caf-msm8996 && git clone https://github.com/CarbonBeta/android_hardware_qcom_media.git -b cr-7.0-caf-8996 hardware/qcom/media-caf-msm8996 && rm -rf hardware/qcom/display-caf-msm8996 && git clone https://github.com/CarbonBeta/android_hardware_qcom_display.git -b cr-7.0-caf-8996 hardware/qcom/display-caf-msm8996 && rm -rf vendor/qcom/opensource/interfaces && git clone https://github.com/blackmiddow/android_vendor_qcom_opensource_interfaces.git -b pie vendor/qcom/opensource/interfaces   ###


#### OWN HALS #####

rm -rf hardware/qcom/media-caf/msm8996 && git clone https://github.com/blackmiddow/hardware_qcom_media-caf.git -b pie-caf-8996 hardware/qcom/media-caf/msm8996 && rm -rf hardware/qcom/display-caf/msm8996 && git clone https://github.com/blackmiddow/hardware_qcom_display-caf.git -b pie-caf-8996 hardware/qcom/display-caf/msm8996


