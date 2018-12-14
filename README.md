rm -rf hardware/qcom/audio-caf/msm8996 && git clone https://github.com/PotatoProject/hardware_qcom_audio.git -b baked-caf-8996 hardware/qcom/audio-caf/msm8996 && rm -rf hardware/qcom/media-caf/msm8996 && git clone https://github.com/PotatoProject/hardware_qcom_media.git -b baked-caf-8996 hardware/qcom/media-caf/msm8996 && 
rm -rf hardware/qcom/display-caf/msm8996 && git clone https://github.com/PotatoProject/hardware_qcom_display.git -b baked-caf-8996 hardware/qcom/display-caf/msm8996 && rm -rf vendor/qcom/opensource/interfaces && git clone https://github.com/blackmiddow/android_vendor_qcom_opensource_interfaces.git -b pie vendor/qcom/opensource/interfaces && rm -rf vendor/xiaomi && git clone https://github.com/blackmiddow/vendor_xiaomi.git -b posp vendor/xiaomi && rm -rf kernel/xiaomi && git clone https://github.com/blackmiddow/kernel_xiaomi_oxygen.git -b pie kernel/xiaomi/msm8953 && 
rm -rf hardware/qcom/wlan && git clone https://github.com/sandyorton7/wlan hardware/qcom/wlan && 
rm -rf hardware/qcom/power && git clone https://github.com/sandyorton7/power hardware/qcom/power && rm -rf hardware/qcom/display && git clone https://github.com/sandyorton7/display hardware/qcom/display && rm -rf hardware/qcom/media && git clone https://github.com/sandyorton7/media hardware/qcom/media && 
rm -rf hardware/qcom/bt && git clone https://github.com/sandyorton7/bt hardware/qcom/bt









git clone https://github.com/Scissordragonboy/device_xiaomi_oxygen.git -b po device/xiaomi/oxygen



git clone https://github.com/Scissordragonboy/device_xiaomi_msm8953-common.git -b pie device/xiaomi/msm8953-common







rm -rf hardware/qcom/audio && git clone https://github.com/sandyorton7/audio hardware/qcom/audio




nano vendor/xiaomi/msm8953-common/Android.mk

nano device/xiaomi/oxygen/camera/QCamera2/Android.mk

nano device/xiaomi/oxygen/vendorsetup.sh

nano device/xiaomi/oxygen/aosp_oxygen.mk

nano vendor/aosp/vendorsetup.sh

cd vendor/aosp/config
