# WhatsApp
WhatsApp in [Nativefier](https://github.com/nativefier/nativefier) with [Custom CSS](https://userstyles.org/styles/228154/responsive-whatsapp-windows-11-style) with tray support.


# Build
Download and install [NodeJS](https://nodejs.org) and [Nativefier](https://github.com/nativefier/nativefier).
Run this command: (for mac, remove --tray start-in-tray)
```
nativefier "web.whatsapp.com" -n WhatsApp --single-instance --tray start-in-tray --inject "(For custom styles, only use .js files, optional)"
```
