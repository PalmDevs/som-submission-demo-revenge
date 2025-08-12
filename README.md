# Submission: Revenge (Discord Mobile Client Modification)

[Summer of Making](https://summer.hack.club/coo) demo for [Revenge](https://github.com/revenge-mod) (the 'Next' version).

- [Project on Summer of Making](https://summer.hackclub.com/projects/6412)
- [Project on GitHub](https://github.com/revenge-mod/revenge-bundle-next)
- [Our Discord server](https://discord.com/invite/ddcQf3s2Uq)

## 🛑 READ ME!

In the GitHub release, you'll see multiple APK files. Download **ALL** of them and follow these instructions:

1. Install [SAI](https://github.com/Aefyr/SAI/releases/tag/4.5).
2. Open SAI and tap the **Install APKs** button at the bottom.
3. Tap **Internal file picker** and grant storage permissions.
4. Locate and select **ALL** APK files you've just downloaded.
5. Tap **Install**.
6. SAI will ask for permissions to install, grant it.
7. Back out of Settings and tap the Install prompt.

### ✅ Verify that the installation works

Once logged into Discord, head into its Settings and make sure the Revenge section appears at the top, like so:

<img width="403" height="355" alt="image" src="https://github.com/user-attachments/assets/8b8fd62f-3013-494b-b686-93f23a58a6c0" />

## ❓ What does the GitHub release contain?

The release contains a prebuilt version of Revenge. A patched Discord Android (293.6 Alpha) build.

It is patched via LSPatch with a custom version of [RevengeXposed](https://github.com/revenge-mod/revenge-xposed) that only executes a bundled-in `revenge.bundle` file.  
This means no extra network requests (and no remote code execution).

### 🤔 Is this... safe?

Yes, but if you don't trust me, simply follow the [install instructions](https://github.com/revenge-mod/revenge-bundle-next?tab=readme-ov-file#%EF%B8%8F-download) here to get Revenge Next working by yourself.

### ⚠️ Disclaimers

- The build only contains [my own plugins](https://github.com/PalmDevs/revenge-next-plugins). Revenge Next is in its very early stages, and external plugins aren't supported yet. I hope you understand why it is so limited at the moment.
- Plugin states currently **DO NOT** save. Most plugins will be enabled by default and you will have to disable them manually every launch. Plugin settings are saved, however.
- This is a client modification, which is against Discord's Terms of Service, but Discord themselves act indifferently on modified clients, and there are no known cases of people being banned for this.
- This repository is not affiliated with the Revenge organization. The Revenge team will never release anything like this.
