<!--
    FOSScraft - A free and open-source Minecraft launcher based on Prism Launcher
    Licensed under GPLv3.
-->
 > # *Currently Under Construction*
 > *No Downloads available, don't even try the links, almost none of the fosscraft.org / download links work, working on it*
# FOSScraft

> A free and open-source Minecraft launcher

Easily manage multiple Minecraft installations with a modern, streamlined interface.

---

## Installation
> Working on download links, for now please download from [here](https://github.com/FOSScraft/FOSScraft/releases)

All downloads and instructions for FOSScraft can be found on our [Website](https://fosscraft.org/download).

Last build status can be found in the [GitHub Actions](https://github.com/FOSScraft/FOSScraft/actions) tab (this also includes the pull requests status).

### Development Builds

> ⚠️ **Devlopment builds are not intended for most users,** There may be bugs and other instabilities, You have been warned.

There are development builds available through:

- [GitHub Actions](https://github.com/FOSScraft/FOSScraft/actions) (includes builds from pull requests opened by contributors)
- [nightly.link](https://nightly.link/FOSScraft/FOSScraft/workflows/build/develop) (this will always point only to the latest version of develop)

These have debug information in the binaries, so their file sizes are relatively larger.

Prebuilt Development builds are provided for **Linux**, **Windows** and **macOS**.

For **Arch**, **Debian**, **Fedora**, **OpenSUSE (Tumbleweed)** and **Gentoo**, respectively, you can use these packages for the latest development versions:

- [AUR: fosscraft-git](https://aur.archlinux.org/packages/fosscraft-git)
- [Fedora COPR: fosscraft-nightly](https://copr.fedorainfracloud.org/coprs/fosscraft/)
- [openSUSE Build Service](https://build.opensuse.org/project/show/home:fosscraft)

These packages are also available to all the distributions based on the ones mentioned above.

---

## Community & Support

Feel free to create a GitHub issue if you find a bug or want to suggest a new feature. We have multiple community spaces where other community members can help you:

### Discord Server

Join our Discord community: [fosscraft.org/discord](https://fosscraft.org/discord) 

---

## Translations

The translation effort for FOSScraft is hosted on [Weblate](https://hosted.weblate.org/projects/fosscraft/launcher/) and information about translating FOSScraft is available at [github.com/FOSScraft/Translations](https://github.com/FOSScraft/Translations).

---

##  Building
> For Now, refer to the FOSScraft docs [here](fosscraft.github.io) as none of these links

If you want to build FOSScraft yourself, check the build instructions:

- [Windows](https://fosscraft.org/wiki/development/build-instructions/windows/)
- [Linux](https://fosscraft.org/wiki/development/build-instructions/linux/)
- [macOS](https://fosscraft.org/wiki/development/build-instructions/macos/)
- [OpenBSD](https://fosscraft.org/wiki/development/build-instructions/openbsd/)

---

## Sponsors & Partners

**Open Collective**

Support FOSScraft by [becoming a backer](https://opencollective.com/fosscraft).

> **Sponsers of the Original Prism Launcher project**
>   - JetBrains
>   - Netlify
>   - MacStadium
  
---

##  Building and Customization

If you are building FOSScraft for your distribution, please make sure to set the `Launcher_BUILD_PLATFORM` to a slug representing your distribution. Examples are `archlinux`, `fedora` and `nixpkgs`.

Go through `CMakeLists.txt` and update FOSScraft's API keys to your own or set them to empty strings (`""`) to disable specific functionality if needed (the program will still compile but those features will be disabled).

Note that if you build this software with the provided API keys in `CMakeLists.txt`, you are accepting the following terms and conditions:

- [Microsoft Identity Platform Terms of Use](https://docs.microsoft.com/en-us/legal/microsoft-identity-platform/terms-of-use)
- [CurseForge 3rd Party API Terms and Conditions](https://support.curseforge.com/en/support/solutions/articles/9000207405-curse-forge-3rd-party-api-terms-and-conditions)

If you do not agree with these terms and conditions, then remove the associated API keys from the `CMakeLists.txt` file by setting them to an empty string (`""`).

---

##  License

**All launcher code is available under the [GPL-3.0-only license](https://github.com/FOSScraft/FOSScraft/blob/develop/LICENSE).**
FOSScraft will **Always** be **Free & Open Source**, This project is and was not built for monetary gain and I won't sell out
All Related assets are under the CC BY-SA 4.0 license.

---

© 2025 FOSScraft. Licensed under GPLv3.
