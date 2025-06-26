## Ship FOSS apps to your ROMs
### Usage
1. Add `<name="android_vendor_oss-addons" remote="" path="vendor/oss-addons" revision="main"/>` to your local_manifests
2. Sync the repo
3. Add `$(call inherit-product, vendor/oss-addons/oss-addons.mk)` to your device makefile
4. Build it!
### This repo included (and can be updated with F-Droid)
- Fennec (Firefox based browser)
- Gramophone (Minimal music player)
- HeliBoard (Customisable keyboard)
- ProtonVPN (VPN service from Swizzerland)
- Shizuku (TempRoot for apps that supports it)
