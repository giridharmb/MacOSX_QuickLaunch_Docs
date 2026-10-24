# Release Notes

## 1.4.0 — 2026-10-24

- **Favorites:** star links to pin them in a Favorites section at the top of the menu. They also come first in the search launcher and get first pick of leader-key letters.
- **Website icons:** URL links show the site's own icon, fetched directly from the site and cached.
- **Custom icons:** give any link an image or another app's icon (choose or drag and drop). Custom icons sync through iCloud.
- Settings › Advanced › **Refresh Website Icons**.
- Settings written by older versions keep loading unchanged.

## 1.3.0 — 2026-10-24

- **Preferences redesigned** as a classic toolbar window: General, Shortcuts, Sync, Advanced and About. About shows the app icon, version, and links to docs and support.
- **Live shortcut test:** after recording, press the shortcut once to confirm it reaches QuickLaunch. If it never arrives, something else is intercepting it. Click any status icon to test again.
- **More conflicts detected:** custom App Shortcuts from System Settings and Services keyboard shortcuts, with no permission needed.
- Fixed: the leader-key overlay could be cut off at the top and bottom.

## 1.2.0 — 2026-10-24

New
- **Leader key**: one shortcut, then a single letter, opens any link. Letters are automatic or can be set per link.
- **Search launcher** with fuzzy search, most used links first, and ⌘1–⌘9.
- **Cheat sheet** overlay listing all your shortcuts.
- **Workspaces**: one shortcut opens several links in order.
- **Pause shortcuts while chosen apps are in front** (games, VMs, remote desktop).
- **Add the frontmost app** straight from the menu bar menu.
- **Insights**: usage counts, unused shortcuts, and suggestions for apps you open often by hand.
- **Cycle windows** of the frontmost app *(Accessibility, optional)*.
- **Window placement** when launching apps: halves, maximize, center *(Accessibility, optional)*.
- **App menu conflict scan**: warns about shortcuts used in running apps' menus *(Accessibility, optional)*.
- **Automatic updates** (Sparkle), with "Check for Updates…" in the menu and in Settings.

## 1.1.0 — 2026-10-24

- New app icon.
- **Show in menu bar** preference (Settings › General). You can hide the menu bar icon and your shortcuts keep working; open QuickLaunch again to get back to the Manage window. ⌘-dragging the icon out of the menu bar also turns this off.
- The menu bar icon now matches the app icon.

## 1.0.0 — 2026-10-24

First release.

- Global keyboard shortcuts for apps, URLs, files/folders, shell commands and Shortcuts.app shortcuts.
- Shortcut recorder that checks for conflicts with macOS system shortcuts, other apps' global
  hotkeys, other QuickLaunch links and common app shortcuts.
- Status indicator for each link, a "last triggered" readout, an on-screen confirmation overlay
  and Test mode.
- Groups (as menu sections or submenus), drag-to-reorder, drag & drop from Finder, search and
  sort by name.
- Pressing an app's shortcut while it is in front hides the app.
- Recent items, Pause All Shortcuts, browser choice for URL links.
- iCloud Drive sync (most recent change wins, with automatic local backup).
- JSON import (merge or replace) and export.
- Launch at login and an optional Dock icon.
