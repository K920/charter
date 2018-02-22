# Hardware Support checklist

![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) - Fully functional

![UNK](https://raw.githubusercontent.com/K920/charter/master/images/unk.png) - Unknown state

![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) - Does not apply

![X](https://raw.githubusercontent.com/K920/charter/master/images/x.png) - Not working

## Audio

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices MUST support audio playback for media content.
* Phones MUST support in-call audio.
* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) Phones MUST support speaker audio.
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) Tablet devices capable of in-call audio/speaker audio MUST support in-call/speaker audio.
* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) Devices SHOULD support any additional audio configuration inherent to their device (echo cancellation, extra mics, etc).
* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices MUST support any other audio output supported by their stock OS (ex. Headphone jack, USB-C, BT).
* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices with FM radio capabilities in their stock OS SHOULD support FM.

## RIL

* ![UNK](https://raw.githubusercontent.com/K920/charter/master/images/unk.png) All devices with RIL supported in their stock OS MUST support RIL for phone calls & data.
* ![UNK](https://raw.githubusercontent.com/K920/charter/master/images/unk.png) All devices with RIL supported in their stock OS MUST support emergency calling with a SIM inserted (112/911).
* ![UNK](https://raw.githubusercontent.com/K920/charter/master/images/unk.png) All devices with RIL supported in their stock OS SHOULD support emergency calling without a SIM inserted (112/911).
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) Data only devices (defined as devices that have a ril but does not support telephony stack due to hardware/firmware restrictions) are EXEMPTED from phone & emergency dialing requirements.

## Encryption

* ![UNK](https://raw.githubusercontent.com/K920/charter/master/images/unk.png) All devices that supported hardware-backed encryption on their stock OS MUST support hardware-backed encryption.
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All devices that shipped stock as forceencrypt SHOULD default to forceencrypt enabled.
* ![UNK](https://raw.githubusercontent.com/K920/charter/master/images/unk.png) All devices MUST support software encryption.

## Wifi

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices with Wi-Fi supported in their stock OS MUST support Wi-Fi.
* ![UNK](https://raw.githubusercontent.com/K920/charter/master/images/unk.png) All devices with Wi-Fi hotspot capabilities MUST support Wi-Fi tethering.

## USB

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices with a USB port MUST support file access via MTP.
* ![UNK](https://raw.githubusercontent.com/K920/charter/master/images/unk.png) All devices with USB tethering supported on their stock OS MUST support USB tethering.
* ![UNK](https://raw.githubusercontent.com/K920/charter/master/images/unk.png) All devices with a USB port & Data SHOULD support USB tethering.

## GPS

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices with GPS supported in their stock OS MUST support GPS.

## Bluetooth

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices with Bluetooth supported in their stock OS MUST support Bluetooth.
* All devices with Bluetooth SHOULD support Bluetooth tethering.
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All devices with aptX support in stock (non-beta releases) OS SHOULD support aptX.
* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices not shipping with aptX support in stock (non-beta releases) OS MUST NOT support aptX.

## Camera

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices with Camera supported in their stock OS MUST support Camera, in both front facing and rear camera configurations.
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All devices with Dual (or more) Rear Cameras SHOULD support all rear cameras.
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All devices with Dual (or more) Front Facing Cameras SHOULD support all front cameras.

## Video Recording

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices with Video Recording supported in their stock OS MUST support Video Recording, in both front facing and rear camera configurations.

## Display

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices with a built-in Display MUST support the Display at the same resolution and  density as the stock OS.
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All devices that do not include a built-in Display MUST support Display output via the hardware’s supported outputs (ex. Android TV - HDMI).
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All devices that support additional non-USB display interfaces SHOULD support those display output methods.
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All devices that support a USB-out display in their stock OS SHOULD support this display output (ex. MHL/Miracast/OTG).

## NFC

* ![X](https://raw.githubusercontent.com/K920/charter/master/images/x.png) All devices with NFC supported in their stock OS MUST support NFC.

## Fingerprint Sensor

* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All devices with a Fingerprint Sensor MUST support the Fingerprint Sensor if the stock OS supports it with Marshmallow or higher Android versions.
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All devices with a Fingerprint Sensor SHOULD support the Fingerprint Sensor if the stock OS supports it for all other Android versions.

## IR

* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All devices with an IR blaster SHOULD support IR blaster.

## Accelerometer

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices with an accelerometer MUST support the accelerometer.

## Gyroscope

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices with a gyroscope MUST support the gyroscope.

## Proximity

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices with a proximity sensor MUST support the proximity sensor.

## Light

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices with a light sensor MUST support the light sensor.

## Other Sensors

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All other sensors supported by a device’s stock OS SHOULD be supported in LineageOS.

## Accessories

* ![UNK](https://raw.githubusercontent.com/K920/charter/master/images/unk.png) All devices with proprietary accessories SHOULD support those accessories in LineageOS (ex. O-Click, Essential 360 Camera).

## Hardware Deviations

__Hardware deviations are defined as exemptions granted for hardware requirements above that worked in stock, but do not work in LineageOS.__

* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All hardware deviations from stock MUST be reported on the wiki page for the device, with a user understandable justification.

# Software support

## Lineage.mk

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) Device trees MUST contain a lineage.mk file with device declaration of lineage_[devicename].

## Lineage.Dependencies

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) Device trees MUST support a lineage.dependencies file for `breakfast` command & roomservice to be functional.
* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) This file MUST NOT include any dependencies outside of the "LineageOS" organization.

## Build Type

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices MUST be configured as userdebug releases.

## SELinux Enforcing

* ![X](https://raw.githubusercontent.com/K920/charter/master/images/x.png) All devices MUST be configured for SELinux Enforcing.

## Encryption

* ![UNK](https://raw.githubusercontent.com/K920/charter/master/images/unk.png) All devices MUST support software encryption.

## Verity

* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All devices MUST disable verity on the system image for userdebug builds.
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All devices SHOULD support verity on the vendor image.

## Updater

* ![UNK](https://raw.githubusercontent.com/K920/charter/master/images/unk.png) All devices with a shipping build of LineageOS MUST support upgrades via the native LineageOS Updater application & the recovery documented on the Wiki for that device.

## FRP

* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All devices with stock support of Factory Reset Protection (FRP) SHOULD support FRP when Google Applications are installed by the user.

## SafetyNet

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices MUST NOT alter SafetyNet validation responses.

## Root (su)

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices MUST NOT ship with su included.
* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices MUST support su installation via LineageOS provided ‘Extras’ download.

## Non-PIE Blobs

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) Devices MUST NOT use non-PIE binaries.

## Extract Files

* ![X](https://raw.githubusercontent.com/K920/charter/master/images/x.png) Devices MUST support a working extract files script in their device tree (or device tree dependencies) that reproduces an exact copy of the binaries required to build LineageOS from an existing LineageOS installation.
* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) Devices SHOULD use the global extract files script in vendor/lineage.
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) If a device maintainer elects to not use the common extract script, the maintainer MUST ensure that the wiki page for their device has valid instructions for operating the custom extract script.

## CVE

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) Devices MUST support CVE patches for “high profile” exploits and vulnerabilities (if the media is reporting on it, then we must have it patched).
* [NOTE: This will become a MUST once CVE autopatcher is live & automated]
* ![UNK](https://raw.githubusercontent.com/K920/charter/master/images/unk.png) Devices SHOULD receive regular CVE patches to the device kernel and dependencies.
* [To be in effect once CVE autopatcher is live & automated]
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) Device maintainers MUST review and/or accept patches provided by the CVE autopatcher tool.

## Firmware Assert

* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All devices MUST assert on known to be working firmware versions if some firmware versions are known to be non-working.

## Additional Features

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All devices SHOULD support in-kernel (MDSS, MDNIE or similar) LiveDisplay colour adjustment.

## Software Deviations

__Software deviations are defined as exemptions granted for software requirements above that worked in stock, but do not work in LineageOS.__

* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All software deviations from other LineageOS devices of the same type MUST be approved by Directors (ex. if you want to remove Music app, get approval).
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All software deviations from other LineageOS devices of the same type MUST be reported on the wiki page for the device, with a user understandable justification.
* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) Device maintainers MUST ship Jelly or another LineageOS sourced web browser.

# Quality of life
## Commit Authorship

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All non-original commits MUST have proper authorship attribution from the source it was taken from or adapted from.

## Copyrights

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All original contributions MUST be copyrighted as “(C) [YEAR] The LineageOS Project”.
* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All LineageOS copyrights MUST only be additive to the copyright header.
* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) Do not remove copyrights from CyanogenMod, Cyanogen Inc or any other upstream.

# Workflow:

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) Force pushing branches SHOULD be avoided.
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) In the event of a force pushed branch, backup branches of the pre-forced HEAD MUST be made.

# JIRA

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) Device maintainer(s) MUST have a JIRA account for bug tracking and cross-team collaboration.
* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) Device maintainer(s) MUST routinely triage, answer and close JIRA reports.
* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) Device maintainer(s) SHOULD make their JIRA name match their maintainer name as displayed on the Wiki.

## Licensing

* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All Kernel contributions MUST be GPLv2.
* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) All Android contributions SHOULD be Apache 2.0 licensed.
* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) Any contribution to an existing Apache 2.0 project MUST fall under Apache Compliance Category A.
* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) Any contribution to an existing Apache 2.0 project MUST NOT be in Apache Compliance Category X.

## Wiki

* ![UNK](https://raw.githubusercontent.com/K920/charter/master/images/unk.png) All devices with a shipping build of LineageOS MUST have a wiki page with valid installation instructions.
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All devices with a shipping build of LineageOS MUST document Hardware Deviations from stock capabilities.
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) All devices with a shipping build of LineageOS MUST document Software Deviations from other LineageOS releases of the same device type.

## Stability

* ![UNK](https://raw.githubusercontent.com/K920/charter/master/images/unk.png) No "screen of death" issues.
* ![UNK](https://raw.githubusercontent.com/K920/charter/master/images/unk.png) Battery - no abnormal power drains.
* ![OK](https://raw.githubusercontent.com/K920/charter/master/images/ok.png) CPU Profiling - no overclocks by default.

## Recovery

* ![X](https://raw.githubusercontent.com/K920/charter/master/images/x.png) Maintainers MUST document for users on the Wiki a valid Recovery image by which to install LineageOS zip files.
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) Devices that do not have traditional Recovery images MUST support & document another means of installation for LineageOS zip files.
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) Maintainers SHOULD verify that Teamwin Recovery Project (TWRP) official distributions work for LineageOS installation.
* ![DNA](https://raw.githubusercontent.com/K920/charter/master/images/dna.png) Failures in official TWRP recoveries should be raised with the TWRP team or remedied by the maintainer.
* ![X](https://raw.githubusercontent.com/K920/charter/master/images/x.png) Maintainers SHOULD provide a custom recovery link in Wiki documentation if TWRP does not officially support their device.

__This document is licensed CC-BY-3.0, with portions adapted from Google’s CDD requirements.__
