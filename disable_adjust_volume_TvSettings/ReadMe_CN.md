#   TvSettings禁用音量调节补丁

1.在packages/apps/TvSettings目录上打上./packages/apps/TvSettings/0001-Feat-Disable-Adjust-Volume-in-TvSettings.patch的补丁。

2.在frameworks/base目录打上./frameworks/base/0001-Feat-Disable-to-adjust-Volume.patch的补丁。

在两个目录打上对应的补丁后，编译系统即可正常使用此功能。

打开TvSettings-Device Preferences-Sound-Disable to adjust volume后，Android系统即无法调节音量，只保留当前音量大小，此时一般通过调节HDMI设备音量来控制音量大小。
