## Ship FOSS apps to your ROMs
### Usage
1. Add `<name="android_vendor_oss-addons" remote="https://github.com/hrzndelta-experimentations" path="vendor/oss-addons" revision="main"/>` to your local_manifests
2. Sync the repo
3. Add `$(call inherit-product, vendor/oss-addons/oss-addons.mk)` to your device makefile
4. Build it!

### This repo included (and some can be updated with F-Droid)
- BreezyWeather (Freenet weather app)
- Fennec (Firefox based browser)
- Gramophone (Minimal music player)
- HeliBoard (Customisable keyboard)
- Lawnchair (Customisable launcher based on Launcher3) (GitHub: [Goooler's LawnchairRelease](https://github.com/Goooler/LawnchairRelease))
- Lawnicons (Themed icon made by the devs at Lawnchair) (IzzyOnDroid)
- ProtonVPN (VPN service from Swizzerland)
- Shizuku (Privileged api for apps that supports it) (IzzyOnDroid)
- Smartspacer (Modifies your At a glance) (GitHub: [KieronQuinn's Smartspacer](https://github.com/KieronQuinn/Smartspacer))

> [!NOTE]
> I'm planning to add Lawnchair Quickstep in the future. due to previous breakage in Lawnchair's Quickstep in Android 15, this currently isn't possible. until then, I will use crDroid's Launcher3 as Quickstep

> [!IMPORTANT]
> You're free to remove or add other apps to this vendor. to do so, modify the `oss-addons.mk`
