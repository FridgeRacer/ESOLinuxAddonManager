[![aksdev-blog](https://img.shields.io/badge/blog-akselmo.dev-blue?style=flat-square)](https://akselmo.dev)
[![mastodon](https://img.shields.io/mastodon/follow/106864208846697693?color=%233088D4&domain=https%3A%2F%2Fmastodon.technology&logo=mastodon&style=flat-square&logoColor=white)](https://mastodon.technology/@huntra)
[![itchio](https://img.shields.io/badge/itch.io-akselmo-%23FA5C5C?style=flat-square&logo=itch.io&logoColor=white)](https://akselmo.itch.io/)
[![ko-fi](https://img.shields.io/badge/ko--fi-donate-%23FF5E5B?style=flat-square&logo=ko-fi&logoColor=white)](https://ko-fi.com/L4L57FOPF)
[![discord](https://img.shields.io/discord/475097536160595979?color=%235865F2&label=aks_dev%20discord&logo=discord&style=flat-square&logoColor=white)](https://discord.gg/PZkYZRx)

# ESOLinuxAddonManager
Very simple addon manager for Elder Scrolls Online running on Linux. Well, more a downloader for now.

Currently it's quite ugly but it gets the job done!

## How to use
* Download the app from releases
* Put it in any empty folder you wish
* Make sure the app has permissions to run (is set to executable)
* After opening the app, add
  * Your ESO addon location. For example, for me it is `/mnt/sda3/steam/steamapps/compatdata/306130/pfx/drive_c/users/steamuser/My Documents/Elder Scrolls Online/live/AddOns/`
  * Paste links to ESOUI.com addon pages, one per line. One link should look like, for example: `https://www.esoui.com/downloads/info602-Azurah-InterfaceEnhanced.html`
  * Press download
  * If you have issues, the text below download button should tell you whats happening
* All your data is saved to text files
  * List of addons are in `addons.txt`
  * The ESO addon location is saved in `addonslocation.txt`

**Check issues for TODO and bugs!**

## How to build
* Make sure you have PyGObject installed: [https://pygobject.readthedocs.io/en/latest/](https://pygobject.readthedocs.io/en/latest/)
* To run the app from python, just type `python3 main.py`
* You can build the app into single file with `pyinstaller main.py --onefile`

## Contributing
If you want to contribute, hop on my Discord! [https://discord.gg/PZkYZRx](https://discord.gg/PZkYZRx)

I have no proper guidelines yet set so I want to chat about it first.
