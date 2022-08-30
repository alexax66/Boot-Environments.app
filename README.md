# Utilities [![Translation status](https://hosted.weblate.org/widgets/hellosystem/-/svg-badge.svg)](https://hosted.weblate.org/engage/hellosystem/)

## Boot Environments.app

This utility provides a simple settigs for ZFS Boot Environments.

![image](https://user-images.githubusercontent.com/2480569/97612525-d2e93180-1a17-11eb-90c4-5dd90ad67d7f.png)

Utility written in PyQt5, meant for use with [helloSystem](https://hellosystem.github.io/) and [GhostBSD](https://github.com/ghostbsd/).

This is a work in progress.

* No compilation needed, since PyQt5
* Focus on simplicity for the user
* Focus on simplicity in source code
* One Python source code file per app
* Tested on FreeBSD in [helloSystem](https://hellosystem.github.io/) and [GhostBSD](https://github.com/ghostbsd/)

Pull requests welcome.

## Translations

Translation happens on [Weblate](https://hosted.weblate.org/engage/hellosystem/). Everyone can contribute! Be sure to use the "Automatic suggestions" button which suggests translations from Deepl, Google Translate, Microsoft Translator, and various open source projects. This reduces the work to picking the most appropriate translation in many cases.

<a href="https://hosted.weblate.org/engage/hellosystem/">
<img src="https://hosted.weblate.org/widgets/hellosystem/-/287x66-grey.png" alt="Translation status" />
</a>

```
hardlink . -v -t -n # Dry run (change nothing, only explain)
hardlink . -v -t
```

This can be useful for making a change in all of the redundant copies at once.
