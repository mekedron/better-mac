# Better Mac
This repository provides a list of must-have applications and tweaks for MacOS to increase productivity and overall experience when using your Apple device.

## Productivity

Despite the fact that MacOS is a really good and polished OS, there are still plenty of things missing. So here are a couple of programs that could fix it; pick one you like more:
- **[ClipSlop](https://mekedron.github.io/ClipSlop/)** — 🌟 **FEATURED** 🌟 — Free AI writing tool for macOS. Fix grammar, translate, rewrite, or format text with a hotkey. Works with ChatGPT, Anthropic, and Ollama.
- [Bringr](https://github.com/mekedron/Bringr) — Radial pie-menu window switcher for macOS. Summon a wheel with a gesture, hover an app to fan out its windows with live previews, and click to bring one forward; no Cmd-Tab, no Mission Control.
- [VoiceInk](https://tryvoiceink.com) — 🌟 **FEATURED** 🌟 — Near-instant local-first voice-to-text transcription for macOS. [My license-free fork](https://github.com/mekedron/PatchedVoiceInk).
- [Rectangle](https://rectangleapp.com/) [OpenSource] - Incredibly powerful window manager! It allows you to snap your application windows to different corners and provides a lot of useful and easy-to-remember shortcuts for arranging your Mac's windows!
- [MacsyZones](https://github.com/rohanrhu/MacsyZones) [OpenSource] - Free and Open Source analog of FansyZones on Windows, but for macOS! It's a must-have for a wide screen monitor user.</s> <s><b>Deprecated:</b> Use BetterTouchTool for snapping windows.</s> - Unfortunately better attached tool didn't work for me because it was making dragging of windows to laggy.
- <s>[Snap](https://apps.apple.com/us/app/snap/id418073146) [Free?] - Allows you to open your pinned dock apps with shortcuts! A must-have tool that makes your tasks much easier and more efficient.</s> <b>Deprecated:</b> Use Hammerspoon. Or BetterTouchTool (you can use [this shell script](https://gist.github.com/mekedron/55bdef0820c02094c3454ef169886305) or import from the code field below - paste to you address bar to import). But i highly recommend the Hammerspoon. 
- [Dockey](https://dockey.publicspace.co/) [Free] - Makes your dock faster. Removes open delay for the dock.
- [Pika](https://superhighfives.com/pika) [OpenSource] - Color picker! Now you can see what the color is just with a small shortcut.
- [AutoRaise](https://github.com/sbmpost/AutoRaise) [OpenSource] - Focuses or raises your windows on hover! It's very useful for a multi-monitor setup and mostly opens your windows in full-size mode. I would really like to use it myself, but only focus mode works poorly with JetBrains tools...
- <s>[TextSniper](https://textsniper.app/) [Shareware] - A smiple shortcut that a copies any text from screen or image to your clipboard! Must have!</s> <b>Deprecated:</b> Use [ClipSlop](https://mekedron.github.io/ClipSlop/) - it supports basic OCR features out of the box.
- [Hammerspoon](https://github.com/Hammerspoon/hammerspoon) [Opensource] - I highly recommend this tool for all the customizations you might need related to shortcuts or any other macOS automation. In the era of AI agents and coding tools, you can ask them to get what you need and you will because they are really good at this. You can check my config [here](https://github.com/mekedron/hammerspoon-config).
- [Amphetamine](https://apps.apple.com/us/app/amphetamine/id937984704) [Free] - Tool that keeps your mac awake. Better alternative to Caffeine. Killer feature: let you to prevent your mac from sleep even when the lid is closed, which is super cool for modern era of AI agents.
  

## System Tweaks

And here are a couple of other important apps related to the system itself:

### Battery

- [AlDente](https://apphousekitchen.com/) [Trialware, [OpenSource](https://github.com/AppHouseKitchen/AlDente-Charge-Limiter)] - Manually control your MacBook's charging to increase its lifespan. It's a replacement for "Optimized Battery Charging," which is almost useless on MacBooks.
- [Battery Toolkit](https://github.com/mhaeuser/Battery-Toolkit) [OpenSource] - Analog for AlDente, please choose one.

### Storage

- [AppCleaner](https://freemacsoft.net/appcleaner/) [Free] - A must-have! Cleans up garbage after you delete applications. Completely free and without useless features.
- [Grand Perspective](https://apps.apple.com/us/app/grandperspective/id1111570163) [Shareware] - Disk space analyzer. Always helps me find out the reason for the lack of space.

### Security

- [Little Snitch](https://www.obdev.at/products/littlesnitch/index.html) [Shareware] - Network filter. You can see which programs connect to the internet and block access, like a firewall.

### Other

- [FinderFix](https://synappser.github.io/apps/finderfix/) [Free] - INCREDIBLY USEFUL. This prevents Finder from picking a random place on the screen when you open it. Must-have.

## External Hardware

### Keyboard, Mouse, Touchpad

When you plug in an external mouse, you'll notice how strange its behavior is. The scroll direction is wrong, and there's unnecessary scroll acceleration. It works fine if your mouse is Apple's, but mice from other vendors are almost unusable. Check out the following apps that help you fix it:
- [Linear Mouse](https://linearmouse.app/) [OpenSource] - Allows you to disable external mouse acceleration and reverse scroll direction upon mouse plug-in.
- <s>[BetterTouchTool](https://folivora.ai/) [Trialware] - An exceptionally powerful tool for configuring touchpad and keyboard shortcuts.</s> After a year of use, I realized that, unfortunately, this tool is not flexible enough for my needs. It is very difficult to configure, and it causes my MacBook to stutter. I currently highly recommend **Hammerspoon** (productivity section).

### Screen

When you connect an external display to your MacBook or Mac Mini, you may notice something strange with its resolution. The external display picture is blurry on the MacBook or lacks sharpness, and when you open Display Settings, you may not see the proper resolution for your display. There are a couple of options you can check to fix your issue; pick only one:
- [DisplayBuddy](https://displaybuddy.app/) [Trialware] - I use this one with on my MacBook with Samsung Odyssey OLED G9.
- [BetterDisplay](https://github.com/waydabber/BetterDisplay?tab=readme-ov-file) [Freemium] - I used only this one for setting completely custom HiDPI resolution for my external monitor on MacBook Pro.
- [MonitorControl](https://github.com/MonitorControl/MonitorControl) [OpenSource] - Can't see if it supports setting custom HiDPI resolution, but worth trying.

### Sound

- [SwitchAudioSource](https://github.com/deweller/switchaudio-osx) - A small console utilite for Mac to switch audio sources. I use this in combination with BetterTouchTool to have shortcuts to switch between speakers and headphones.

## Content Editing

### Video

- [HandBreak](https://handbrake.fr/) - Incredibly nice tool that can help you to convert your .mov screen recordings into .mov or .mp4 format offline.
