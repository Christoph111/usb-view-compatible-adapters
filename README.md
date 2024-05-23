# USB View Compatible Adapters for MixEffect

Here is a table listing HDMI to USB/UVC adapters that are known to work or not work with MixEffect's USB View. Adapters marked with ✅ are known to work with USB View, and those marked with ❌ have problems listed in the Notes section.

- [USB View panel](https://docs.mixeffect.app/configure/switcher-pages/panels-and-buttons/usb-view)
- [External Camera Support](https://docs.mixeffect.app/configure/external-camera-support)

| Product    | Works | Notes |
| -------- | ------- | ------- |
| [4K HDMI to USB Video Capture Card, Cam Link Capture Card, Type-C 1080P HD Video Recorder](https://amzn.to/3y3CAUf)  | ✅ | Tested on ATEM Mini Pro, Mini Extreme ISO, and 2 M/E Constellation HD |
| [Elgato Cam Link 4K](https://www.elgato.com/us/en/p/cam-link-4k) | ✅ ||
| [Maravillosa tarjeta de captura de video, maravillosa 4K HDMI a 1080P USB C para juegos](https://www.amazon.es/gp/product/B093D6824V/) | ??? | Awaiting Testing |
| [XIIXMASK capturadora de Video, capturadora Audio y Video, Tarjeta de Captura USB 3.0 4K HDMI Loop-out, 1080P 60FPS/2K 30FPS](https://www.amazon.es/dp/B0CP659ZSV) | ❌ | Flashing Video |
| [Adaptador USB C HDMI,Adaptador USB C a HDMI 4K Adaptador Thunderbolt 3 a HDMI](https://www.amazon.es/dp/B0C9MD3WHP) | ❌ | Flashing Video |
| [Blackmagic WebPresenter HD (SDI->USB-C)](https://www.blackmagicdesign.com/de/products/blackmagicwebpresenter)  | ✅ | Works with any FullHD framerate up to 60fps |
| [Blackmagic UltraStudio Recorder 3G (SDI->Thunderbolt 4)](https://www.blackmagicdesign.com/de/products/ultrastudio/techspecs/W-DLUS-12)  | ❌ | Thunderbolt devices not supported yet (iOs restriction or Mix Effect update necessary?)  |
| [AVerMedia Live Gamer Portable 2 (HDMI->USB-A)](https://www.avermedia.com/de/product-detail/GC510)  | ❌ | Black Screen, no Image at all |

To add your HDMI-to-USB/UVC adapter to this table, fork this repo, make your change, and submit a pull request. Follow the format of the other entries in this document as your guide:

- First column should be the name of the product embedded in a markdown link.
- Second column should be ✅ or ❌ depending on whether the adapter works or not.
- Third column should be notes for the adapter. If you have tested this with multiple ATEMs and iPads, note them. If the adapter doesn't work, tell us what it showed (i.e. flashing video or dark screen).

![USB View in MixEffect](https://docs.mixeffect.app/~gitbook/image?url=https%3A%2F%2F3777554060-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-MaiI5oKYEXGU01L5yjC%252Fuploads%252FQtCHjbtr8n2o7FBroeLo%252Fusb-view-mixeffect.png%3Falt%3Dmedia%26token%3Dbbe7078a-21a4-4079-8196-38c5dcef846f&width=768&dpr=2&quality=100&sign=a9ca8e4317479764426c892284afc5264b6af14efcc94c5ea294782980bd7e18)
