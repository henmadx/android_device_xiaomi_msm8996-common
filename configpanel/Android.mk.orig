LOCAL_PATH := $(call my-dir)
include $(CLEAR_VARS)

LOCAL_SRC_FILES := $(call all-java-files-under, src)
LOCAL_CERTIFICATE := platform
LOCAL_PRIVILEGED_MODULE := true
LOCAL_PACKAGE_NAME := ConfigPanel
<<<<<<< HEAD
LOCAL_PRIVATE_PLATFORM_APIS := true

LOCAL_USE_AAPT2 := true

LOCAL_STATIC_ANDROID_LIBRARIES := \
    android-support-v4 \
    android-support-v7-appcompat \
    android-support-v7-preference \
    android-support-v7-recyclerview \
    android-support-v13 \
    android-support-v14-preference \

#LOCAL_STATIC_JAVA_LIBRARIES := \
 #   org.lineageos.platform.internal

LOCAL_RESOURCE_DIR := \
    $(LOCAL_PATH)/res \
  #  $(TOP)/packages/resources/devicesettings/res

LOCAL_PROGUARD_FLAG_FILES := proguard.flags

LOCAL_MODULE_TAGS := optional

include frameworks/base/packages/SettingsLib/common.mk

=======

LOCAL_PRIVATE_PLATFORM_APIS := true

LOCAL_STATIC_JAVA_LIBRARIES := \
    android-support-v7-appcompat \
    android-support-v7-recyclerview

LOCAL_AAPT_FLAGS := \
    --auto-add-overlay \
    --extra-packages android.support.v7.appcompat \
    --extra-packages android.support.v7.recyclerview

LOCAL_RESOURCE_DIR := \
    $(LOCAL_PATH)/res \
    frameworks/support/v7/appcompat/res \
    frameworks/support/v7/recyclerview/res

LOCAL_PROGUARD_FLAG_FILES := proguard.flags

LOCAL_PRIVILEGED_MODULE := true
LOCAL_MODULE_TAGS := optional

>>>>>>> 37822b80... msm8996-common: Fix ConfigPanel for AOSP-9.x
include $(BUILD_PACKAGE)
