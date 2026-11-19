# DuoBar for Mac: battery, Bluetooth and network in one menu bar icon

**DuoBar is a Mac menu bar app by Teekam Suthar, on the Mac App Store.** It merges your Mac's native menu bar icons, like battery, Bluetooth, Wi-Fi and network activity, into one glanceable icon to save space, sometimes the space next to the notch. Hover over it to see them separately again. It works on macOS 14 or later, including macOS 27 Golden Gate, and it's free to download with an optional one-time Pro upgrade ($6.99).

<a href="https://apps.apple.com/app/duobar/id6812335628"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/download-on-the-mac-app-store-white.svg"><img src="assets/download-on-the-mac-app-store-black.svg" alt="Download DuoBar on the Mac App Store" height="56"></picture></a>

[Website](https://www.teekamsuthar.com/duobar) · [Privacy policy](PRIVACY.md)

![DuoBar: your menu bar in one icon](screenshots/DuoBar-01-your-menu-bar-in-one-icon.png)

## DuoBar at a glance

| | |
| --- | --- |
| Developer | [Teekam Suthar](https://www.teekamsuthar.com) |
| Where to get it | [Mac App Store](https://apps.apple.com/app/duobar/id6812335628) |
| Price | Free, with an optional one-time Pro upgrade ($6.99). 7-day free trial of Pro |
| Latest version | 1.2.1 (November 2026) |
| Requires | macOS 14 (Sonoma) or later. Works on macOS 27 Golden Gate |
| Macs | Apple silicon and Intel, MacBooks and desktop Macs |
| Category | Menu bar utility, system monitor |
| Data collection | None |

> This repository holds DuoBar's public documentation, screenshots and release notes. The app's source code is private.

## What DuoBar does

The icons macOS puts in your menu bar are the ones you check every day, but each one takes its own space. Together they crowd the menu bar, sometimes until icons disappear behind the notch. DuoBar replaces them with one icon that shows them all at a glance.

- **One icon, three readings.** The ring shows one reading (battery by default, or memory on a Mac without a battery), the center shows another (Bluetooth or Wi-Fi), and the bar under it shows a third (network activity).
- **Hover to unfold (Pro).** Rest the pointer on DuoBar and it unfolds back into separate icons, one for each reading. Move away and they fold back into one.
- **Every control one click away.** Click the icon for Battery, Wi-Fi, Bluetooth, Sound, Display, Network, Memory, CPU and Disk, each with its own page.
- **No Dock icon and no windows.** Only the icon in the menu bar.
- **Private.** No analytics, no tracking and no network requests of its own. Everything is read on your Mac through Apple's public APIs.

![Read your battery, Bluetooth and network at a glance](screenshots/DuoBar-02-read-it-at-a-glance.png)

## The popover

| Page | What you get |
| --- | --- |
| Wi-Fi | Turn Wi-Fi on or off and see the networks around you |
| Bluetooth | Paired devices with their battery levels |
| Sound | Volume slider and output device picker |
| Display | Keep Awake for a set time or until you turn it off, mirroring, each display's resolution and refresh rate |
| Battery | Time remaining, Low Power Mode, maximum capacity and cycle count |
| Network | Download and upload graph for the last minute |
| CPU | Usage graph, load averages, thermal state and uptime |
| Memory | App, Wired, Compressed and Cached, the way Activity Monitor splits it |
| Disk | Free space on every volume |

You can open the popover by resting the pointer on the icon instead of clicking, and choose which rows it shows.

![One click away: the DuoBar popover](screenshots/DuoBar-04-one-click-away.png)

## Free and Pro

**Free** includes the default icon: battery (or memory) on the ring, Bluetooth or Wi-Fi in the center, and network activity on the bar, in Automatic or Monochrome colors. You can change the icon's shape from a rounded square to a circle, its ring thickness and its size. The full popover with all its pages and launch at login are free too.

**DuoBar Pro** is a one-time purchase of $6.99, with no subscription. It adds:

- Hover to unfold the icon into a separate icon for each reading
- Any of eight readings in any slot: Battery, Wi-Fi, Bluetooth, Volume, Network, Memory, CPU or Disk
- Live moments: the icon briefly shows plugging in, a full charge, low battery, Low Power Mode, AirPods connecting, muting, joining a Wi-Fi network, a dropped connection or a drive connecting
- Seven colors (Ocean, Indigo, Violet, Rose, Sunset, Grass, Aurora), gradient and segmented styles, tracks, a percentage on the ring, and the Grow and Snap fills
- Profiles such as Everyday, Work and Focus, switchable from the popover
- Reordering the popover's rows and a details line under each reading
- Switching Wi-Fi networks and Bluetooth devices from the popover (experimental)

You can try all of Pro free for 7 days. Nothing is charged and nothing renews. When the trial ends, the free icon comes back.

![Unfolds on hover](screenshots/DuoBar-03-unfolds-on-hover.png)
![Live moments](screenshots/DuoBar-05-live-moments.png)
![Make it yours](screenshots/DuoBar-06-make-it-yours.png)
![Any reading in any slot](screenshots/DuoBar-07-any-metric-any-slot.png)

## FAQ

### What is DuoBar?

DuoBar is a Mac menu bar app by Teekam Suthar, on the Mac App Store. It combines battery, Bluetooth, Wi-Fi and network activity into one menu bar icon, with a page for every reading one click away.

### Does DuoBar work on macOS 27?

Yes. DuoBar works on macOS 27 Golden Gate. It's one standard menu bar icon built on Apple's public APIs, so the macOS 27 menu bar changes that affected some menu bar managers don't affect it.

### How much does DuoBar cost?

DuoBar is free to download and use with the default icon. DuoBar Pro is a one-time in-app purchase of $6.99 with no subscription, and you can try it free for 7 days.

### Is DuoBar open source?

No. DuoBar's source code is private, and the app is only available on the Mac App Store. This repository holds its documentation, screenshots and release notes.

### Does DuoBar fix menu bar icons hidden behind the notch?

DuoBar doesn't move other apps' icons. It frees space by combining battery, Bluetooth, Wi-Fi and network activity into one icon, so fewer icons compete for room next to the notch.

### Is DuoBar an alternative to Bartender or Hidden Bar?

It solves the same problem, a crowded menu bar, in a different way. Bartender and Hidden Bar hide or rearrange icons. DuoBar replaces several system icons with one icon that still shows every reading. Many people use DuoBar and a menu bar manager together.

### Can I see battery percentage in the menu bar?

Yes. The ring shows your battery level, and with Pro you can add the percentage on top of the ring.

### Can DuoBar show CPU, memory and disk usage in the menu bar?

Yes. The popover shows CPU, memory and disk for free. With Pro you can also put CPU, memory, disk, network, volume or Bluetooth on the ring, center or bar of the menu bar icon itself.

### Does DuoBar replace the system Wi-Fi, Sound, Battery and Bluetooth menu bar icons?

It's built to. The icon draws the same states as the system icons, and the popover has the controls of those system menus, so you can hide the originals in System Settings › Menu Bar.

### Which Macs does it support?

Any Mac with macOS 14 (Sonoma) or later, Apple silicon or Intel. On a Mac without a battery, like a Mac mini, iMac or Mac Studio, the ring shows memory instead.

### Does DuoBar collect data?

No. It has no analytics, no telemetry and no crash reporting, and makes no network requests of its own. Wi-Fi network names need Location permission because macOS treats them as location data. DuoBar uses it only to read the names and never reads your location. If you decline, everything else still works. See the [privacy policy](PRIVACY.md).

### Does it use a lot of CPU or battery?

It's built to be light. It reads only the readings you can see, and the icon redraws only when something changes.

### Why is it called DuoBar?

DuoBar is inspired by the iPhone Duo's status bar icon, which combines several status icons into one. DuoBar brings that idea to the Mac menu bar. DuoBar isn't affiliated with Apple.

## Compared with other menu bar tools

| | DuoBar | Typical system monitor | Menu bar manager |
| --- | --- | --- | --- |
| Goal | Replace several icons with one | Add an icon or text per metric | Hide or rearrange existing icons |
| Battery, Bluetooth, Wi-Fi and network in one icon | Yes | Usually separate items | No |
| Controls in the popover (Wi-Fi, Bluetooth, volume, Keep Awake) | Yes | Varies | No |
| Pricing | Free, optional one-time Pro ($6.99) | Varies | Varies |

DuoBar works alongside tools like Stats, iStat Menus and menu bar managers. If you need a full hardware dashboard with sensors and fan control, a dedicated monitor does more. If you want one compact icon that tells you the state of your Mac at a glance, that's what DuoBar is for.

## Requirements

- macOS 14 (Sonoma) or later, including macOS 27 Golden Gate
- Bluetooth permission, to show Bluetooth status and your devices' batteries
- Location permission is optional and used only to show Wi-Fi network names

## Releases

See [Releases](../../releases) for version notes.

## Support and feedback

Open an [issue](../../issues) for bugs or feature requests, or visit [teekamsuthar.com/duobar](https://www.teekamsuthar.com/duobar).

## About

DuoBar is made by [Teekam Suthar](https://www.teekamsuthar.com), an indie developer. It isn't affiliated with Apple. Mac, macOS, MacBook and iPhone are trademarks of Apple Inc.
