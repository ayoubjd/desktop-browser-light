Lite Browser for Windows 1.3
============================
RECOMMENDED: run LiteBrowser-Setup.exe  (installs for your user, no admin needed)
  - adds Lite Browser to the Start menu and to Settings > Apps > Installed apps
  - optional desktop shortcut, clean uninstaller
  - installs the Microsoft Edge WebView2 Runtime automatically if your PC lacks it
  - finish page: "Choose Lite Browser as my default browser" opens Windows Settings
    (Windows only lets YOU pick the default: choose Lite Browser for HTTP and HTTPS)
  - you can also do it later: Lite Browser > Settings > Default browser

PORTABLE: this folder also runs as-is (keep WebView2Loader.dll next to LiteBrowser.exe).
  Settings > Default browser > "Set as default..." registers the portable copy.

Features
- Tabs on TOP or LEFT (⇆ button). In left mode the panel can be minimized to an icon rail with
  the « / » button or Ctrl+B; while minimized it opens when you hover it and folds back when
  the mouse leaves
- Tab search (left: field at the top of the panel; top mode: 🔍 button; Ctrl+Shift+A): click it
  empty to see your recent and recently closed tabs, type to filter
- Ad/tracker blocker: built-in list that refreshes itself weekly (EasyList, EasyPrivacy, HaGeZi Pro,
  pop-up ad list, AdGuard DNS, StevenBlack), YouTube ad stripping + auto-skip (also for embedded
  YouTube players), guards inside video-player iframes, popup blocker, click-hijack overlay removal,
  script-redirect blocking, cosmetic hiding; per-site on/off (shield button)
- Chrome extensions (🧩 button): install from a Chrome Web Store link/ID or load an
  unpacked folder, or a downloaded .crx/.zip file. Extension Popup/Options pages open in a tab.
  If an install fails, the reason is shown and logged in %APPDATA%\LiteBrowser\extensions.log
- Dark mode, passwords (AES-256 + Windows DPAPI) with import/export CSV,
  bookmarks import/export, history, camera/microphone/location permission prompts
- One window: links opened from other apps go to the running browser
- Shortcuts: Ctrl+T/W/L/F/D/B, Ctrl+Tab, Ctrl+Shift+T, Ctrl+H

Data: %APPDATA%\LiteBrowser  (engine profile: %LOCALAPPDATA%\LiteBrowser)
