# Mac App Store listing — QuickLaunch (App Store edition)

Paste these into App Store Connect. Character limits are Apple's.

| Field | Value |
|---|---|
| Name (30) | QuickLaunch – Hotkey Launcher |
| Subtitle (30) | Open anything with a keystroke |
| Bundle ID | com.giridharmb.QuickLaunch |
| SKU | QUICKLAUNCH-MAC-001 |
| Primary category | Productivity |
| Secondary category | Utilities |
| Price | Free |
| Age rating | 4+ (no objectionable content) |
| Copyright | © 2026 Giridhar Bhujanga |
| Support URL | https://giridharmb.github.io/MacOSX_QuickLaunch_Docs/support.html |
| Marketing URL | https://giridharmb.github.io/MacOSX_QuickLaunch_Docs/ |
| Privacy Policy URL | https://giridharmb.github.io/MacOSX_QuickLaunch_Docs/privacy.html |
| App Privacy | Data Not Collected |
| Export compliance | Uses only exempt encryption (HTTPS) — `ITSAppUsesNonExemptEncryption = NO` is in the build |
| Screenshots | `appstore/screenshots/01-menu … 08-settings.png` (8 × 2880×1800, upload in this order) |

## Promotional text (170)

Bind any app, website, file, script or Shortcut to a keystroke. Conflict-checked when you record it, verified live when you press it.

## Keywords (100)

hotkey,shortcut,launcher,keyboard,app launcher,menu bar,productivity,quick,switcher,leader key

## Description (4000)

QuickLaunch lives in your menu bar and opens anything with a keystroke: apps, websites, files and folders, scripts, and Shortcuts.

SHORTCUTS THAT DON'T FIGHT YOUR MAC
• Record a combination and QuickLaunch checks it against macOS system shortcuts, other apps' global hotkeys and your other links before saving it.
• Press it once to confirm it works. If the press never arrives, QuickLaunch tells you something else is using it.
• A status icon on every link shows whether it's active, and why not if it isn't.

MORE THAN HOTKEYS
• Leader key: press one shortcut, then a single letter. Open dozens of things while remembering just one combination.
• Search launcher: fuzzy search over all your links, favorites first.
• Cheat sheet: see every shortcut at a glance.
• Workspaces: one shortcut opens several links at once.
• Favorites: star links to pin them at the top of the menu.
• Real icons: website links show the site's own icon, and any link can use a custom image.
• Press an app's shortcut again to hide it.

THOUGHTFUL DETAILS
• Pause shortcuts automatically while games, virtual machines or remote-desktop apps are in front.
• Test mode shows a confirmation instead of launching, so you can check every shortcut safely.
• Insights: see what you use, what you never touch, and apps you open often without a shortcut.
• Groups, drag-to-reorder, import and export.
• Syncs through your own iCloud account.

PRIVATE BY DESIGN
No accounts, no analytics, no tracking. QuickLaunch is only told when one of your shortcuts is pressed.

## Review notes (for App Review)

QuickLaunch is a menu bar app (LSUIElement): after launch it shows a lightning-bolt icon in the menu bar, and the Manage window opens on first launch.

To test:
1. In the Manage window click + › Application… and pick Calculator.
2. Click "Record Shortcut" on that row and press ⌃⌥⌘K. Press it again when asked: the row's status turns into a green seal.
3. Switch to any other app and press ⌃⌥⌘K: Calculator opens.

Global shortcuts use the public Carbon RegisterEventHotKey API; no Accessibility or Input Monitoring permission is requested. Shell scripts can only be run from the app's Application Scripts folder (NSUserUnixTask). No account or sign-in is required.
