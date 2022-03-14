---
title:  "Darkmode Toggle (Windows 10)"
tags: [tech]
date: 2020-03-29T15:42:28+00:00
---

If you are looking for an automatic switch to dark/light mode at certain times, check out Armin Osaj's little program [Windows 10 Auto Dark Mode](https://github.com/Armin2208/Windows-Auto-Night-Mode).



I used it for a while but found myself constantly adjusting times, because of weather conditions making it brighter or darker in my room. Unfortunately Armin's program does not provide an instant switch option. Eventually I figured I'd be better served with a simple toggle between dark and light mode. YMMV.

So I wrote a very simple batch file that toggles the 2 relevant registry keys. The first changes the Windows theme, the second changes the theme of any apps that support it.

For those interested you can find my dark mode toggle attached. Review its code yourself and use at your own risk.

[darkmodetoggle.zip](/attachments/toggledarkmode.zip)