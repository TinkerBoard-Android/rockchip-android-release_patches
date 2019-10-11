#   TvSettings Disable to adjust Volume Patch

1.Apply the ./packages/apps/TvSettings/0001-Feat-Disable-Adjust-Volume-in-TvSettings.patch in packages/apps/TvSettings.

2.Apply the ./frameworks/base/0001-Feat-Disable-to-adjust-Volume.patch in frameworks/base.

After applying patches in corresponding directories, compile the system and update.img to use this feature.

Switch TvSettings-Device Preferences-Sound-Disable to adjust volume to open, Android can't adjust the volume. Only keep the volume fixed. Now the volume is usually adjusted via an HDMI device.
