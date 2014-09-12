Copyright 2014 - The CyanogenMod Project
Copyright 2014 - The LiquidSmooth Project

Device configuration for HTC One M8 (2014) Unified

NOTE: This device is configured for multirom support. As such, you need to replace the "bootable/recovery" path in your source tree with @task650's custom TWRP by manually adding the following to your roomservice.xml:


  <remove-project name="android_bootable_recovery" />
  <project name="task650/bootable_recovery_twrp" path="bootable/recovery" remote="gh" revision="kitkat" />

