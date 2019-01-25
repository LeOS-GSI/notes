rm -rf hardware/qcom/audio-caf/msm8996 && git clone https://github.com/blackmiddow/hardware_qcom_audio-caf.git -b pie-caf-8996 hardware/qcom/audio-caf/msm8996 && rm -rf hardware/qcom/media-caf/msm8996 && git clone https://github.com/blackmiddow/hardware_qcom_media-caf.git -b pie-caf-8996 hardware/qcom/media-caf/msm8996 && 
rm -rf hardware/qcom/display-caf/msm8996 && git clone https://github.com/blackmiddow/hardware_qcom_display-caf.git -b pie-caf-8996 hardware/qcom/display-caf/msm8996 && rm -rf vendor/qcom/opensource/interfaces && git clone https://github.com/blackmiddow/android_vendor_qcom_opensource_interfaces.git -b pie vendor/qcom/opensource/interfaces 

## DEVICE TREES ##
git clone https://github.com/blackmiddow/device_xiaomi_oxyge.git -b rr device/xiaomi/oxygen && git clone https://github.com/blackmiddow/device_xiaomi_msm8953-common.git -b pie device/xiaomi/msm8953-common && git clone https://github.com/blackmiddow/vendor_xiaomi_oxygen.git -b pie vendor/xiaomi && git clone https://github.com/blackmiddow/kernel_xiaomi_oxygen.git -b vol-1 kernel/xiaomi/msm8953

## Audio, Media and display hals ## 

## rm -rf hardware/qcom/display && git clone https://github.com/sandyorton7/display hardware/qcom/display && rm -rf hardware/qcom/media && git clone https://github.com/sandyorton7/media hardware/qcom/media && rm -rf hardware/qcom/audio && git clone https://github.com/sandyorton7/audio hardware/qcom/audio ##

## Carbon Beta rom hals ##

rm -rf hardware/qcom/audio && git clone https://github.com/CarbonBeta/android_hardware_qcom_audio.git -b cr-7.0 hardware/qcom/audio && rm -rf hardware/qcom/media && git clone https://github.com/CarbonBeta/android_hardware_qcom_media.git -b cr-7.0 hardware/qcom/media && rm -rf hardware/qcom/display && git clone https://github.com/CarbonBeta/android_hardware_qcom_display.git -b cr-7.0 hardware/qcom/display && rm -rf hardware/qcom/audio-caf/msm8996 && git clone https://github.com/CarbonBeta/android_hardware_qcom_audio.git -b cr-7.0-caf-8996 hardware/qcom/audio-caf/msm8996 && rm -rf hardware/qcom/media-caf/msm8996 && git clone https://github.com/CarbonBeta/android_hardware_qcom_media.git -b cr-7.0-caf-8996 hardware/qcom/media-caf/msm8996 && rm -rf hardware/qcom/display-caf/msm8996 && git clone https://github.com/CarbonBeta/android_hardware_qcom_display.git -b cr-7.0-caf-8996 hardware/qcom/display-caf/msm8996

## android file host upload link-- ##
curl --ftp-pasv -T RevengeOS-2.2-Pasta-UNOFFICIAL-h930-20190103-0741.zip ftp://Scissordragonboy:IOs3gFSCyEtv@uploads.androidfilehost.com


## search and replace-- ##
 find -type f -exec sed -i 's/h930/h931/g' {} \;

## important booting hals

## rm -rf hardware/qcom/wlan && git clone https://github.com/sandyorton7/wlan hardware/qcom/wlan && rm -rf hardware/qcom/power && git clone https://github.com/sandyorton7/power hardware/qcom/power && rm -rf hardware/qcom/bt && git clone https://github.com/sandyorton7/bt hardware/qcom/bt ##

git clone https://github.com/Scissordragonboy/device_xiaomi_oxygen.git -b po device/xiaomi/oxygen



git clone https://github.com/Scissordragonboy/device_xiaomi_msm8953-common.git -b pie device/xiaomi/msm8953-common












nano vendor/xiaomi/msm8953-common/Android.mk

nano device/xiaomi/oxygen/camera/QCamera2/Android.mk

nano device/xiaomi/oxygen/vendorsetup.sh

nano device/xiaomi/oxygen/aosp_oxygen.mk

nano vendor/aosp/vendorsetup.sh

cd vendor/aosp/config
