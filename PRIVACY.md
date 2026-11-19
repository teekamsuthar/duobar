# Privacy Policy for DuoBar

**Last updated:** October 14, 2026

DuoBar ("the app") is a macOS menu-bar utility developed by Teekam Suthar. This
policy explains what data the app accesses and, more importantly, what it does not
collect, store remotely, or share.

## Summary

DuoBar does not collect, transmit, sell, or share any personal data. It has no
analytics, no telemetry, no crash reporting, and makes no network requests of its
own. Everything DuoBar shows you is computed locally, on your Mac, using public
Apple system APIs, and never leaves your device.

## What DuoBar reads, and why

DuoBar reads the following system information solely to display it to you in the
menu bar and popover, and to act on your own clicks:

- **Battery** — charge level, power source, charging state, time remaining, Low Power
  Mode, and battery health (maximum capacity and cycle count), via Apple's public
  power-source and IOKit APIs.
- **Wi-Fi** — connection state, signal strength, and whether a network path is
  available, via CoreWLAN and `NWPathMonitor`. To show the name of the network you
  are on and the networks around you, DuoBar asks for **Location** permission, because
  macOS treats Wi-Fi network names as location data. DuoBar uses that permission only
  to read network names: it never reads, stores or shares your location. If you
  decline, everything else keeps working and network names are simply not shown. When
  you join a network from DuoBar, the password you type is passed to macOS and, once
  the join succeeds, saved in your Mac's login keychain so DuoBar can rejoin that
  network for you later. It never leaves your Mac, and you can delete it at any time in
  Keychain Access (items labelled "DuoBar Wi-Fi").
- **Bluetooth** — whether Bluetooth is on, the names of your paired devices, whether
  they are connected, and their battery level where the device reports one, via
  IOBluetooth and CoreBluetooth. DuoBar connects or disconnects a device only when you
  click it, and never pairs with new devices.
- **Sound** — your audio output devices, output volume and mute state, via Core Audio,
  so you can see and change them from the popover. DuoBar never records or listens to
  audio.
- **CPU, Memory, Disk, Network** — local system counters read through public Apple
  APIs (host statistics, load averages, volume capacity, and kernel interface counters),
  plus your Mac's local network address. Network Activity reads existing traffic
  counters; it does not generate or inspect any network traffic itself, and DuoBar
  never contacts a server to find your public IP address.
- **Displays** — the names of your connected displays, their resolution, refresh rate,
  arrangement, HDR state and color profile, via Apple's public Quartz Display Services,
  so you can see and change them from the popover. DuoBar never captures, records or
  reads what is on your screen. **Keep Awake** asks macOS not to sleep the display while
  it is on.
- **Drives** — when an external drive is connected or ejected, its name, via Disk
  Arbitration, so DuoBar can briefly acknowledge it in the menu bar. DuoBar never reads
  the contents of any drive.

None of this data is stored outside your device, logged, or transmitted anywhere.
Readings exist only in memory to draw the current indicator and popover, and disappear
when the app is closed.

## Data storage

Your preferences — which metric is assigned to which slot, your appearance and hover
choices, and whether DuoBar launches at login — are stored locally in `UserDefaults` on
your Mac. This data never leaves your device and is not accessible to us or any third
party.

## Purchases

DuoBar Pro is a one-time, non-consumable in-app purchase processed entirely by
Apple through StoreKit. DuoBar itself never sees or stores your payment
information. Entitlement status is verified directly with Apple's servers
(`Transaction.currentEntitlements`) each time the app launches; DuoBar does not
maintain its own purchase records or accounts.

## Third parties

DuoBar does not integrate any third-party SDKs, analytics services, or
advertising networks. No data is shared with any third party because no data
leaves your device in the first place.

## Children's privacy

DuoBar does not knowingly collect any information from anyone, including
children, because it does not collect information at all.

## Changes to this policy

If this policy changes, the updated version will be posted here with a revised
"Last updated" date. Material changes will also be reflected in the app's App
Store release notes.

## Contact

Questions about this policy or DuoBar's data practices can be sent to:
**teekam.suthar1+duobar@gmail.com**
