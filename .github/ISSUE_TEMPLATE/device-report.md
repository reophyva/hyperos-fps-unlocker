---
name: Device report
about: Report whether Voltframe works on your device
title: "[Device] <model> - <works / doesn't work>"
labels: device-report
---

> ⚠️ **Issues are public.** Don't paste serial numbers, IMEI, account names, Wi-Fi names,
> or full `dumpsys` / `getprop` output. Only the one line below is needed.

**Device model:**
**HyperOS version:**
**Android version:**
**Games tested:**
**Result:** works / doesn't work

<!-- Optional, if you have ADB: paste ONLY the matching lines -->
```
adb shell dumpsys activity service com.miui.powerkeeper | grep fpsconfig
```
