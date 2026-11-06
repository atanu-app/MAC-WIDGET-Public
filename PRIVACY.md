# Privacy Policy

_Last updated: 6 November 2026 · applies to KairoWidget 1.0.0 and later_

KairoWidget is built to keep everything on your Mac. **It collects nothing, sends nothing and has no servers.**

## What KairoWidget reads — on your Mac only

To show its widgets, KairoWidget reads information from macOS while it runs:

- **Performance:** CPU, memory, disk and GPU usage, and network transfer speeds.
- **Your processes:** names, icons, CPU and memory use of apps and processes that belong to your user account.
- **Listening ports:** which of your apps accept network connections, the folder they run from, and their command line (shown only when you choose **Stop**).
- **Hardware sensors:** temperatures, fan speeds, battery charge, health and charger details, and your Energy Mode setting.
- **Wi-Fi:** signal, speed, band, your local IP address and — only if you allow Location — the network's name.

This information is shown in the widgets and kept in memory for at most 10 minutes (for the graphs). It is never written to disk, logged, or sent anywhere.

## What KairoWidget stores

One settings file, `~/Library/Application Support/MacWidget/layout.json`, containing which widgets are open, where they are, and your alert, menu-bar and refresh choices. Delete it at any time to reset KairoWidget.

## What KairoWidget never does

- No analytics, tracking, advertising or crash reporting.
- No accounts and no sign-in.
- No internet connections. The only addresses KairoWidget ever opens are a port on your own Mac (when you click one in Network Access, in your browser) and pages of System Settings.
- No location tracking. Location permission is used only because macOS requires it before revealing the Wi-Fi network name; KairoWidget never requests or stores your position.

## Permissions

| Permission | Used for |
|---|---|
| Notifications | Showing the alerts you turn on |
| Location | Reading the Wi-Fi network name (optional) |
| Login Items | Starting at login, if you turn it on |

You can change any of these in **System Settings → Notifications**, **Privacy & Security → Location Services** and **General → Login Items**.

## Changes

If this policy changes, the new version will be published here with a new date and noted in the [Changelog](CHANGELOG.md).

## Questions

Open an issue at <https://github.com/atanu-app/MAC-WIDGET-Public/issues>.
