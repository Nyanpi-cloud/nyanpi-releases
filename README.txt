NYANPI (にゃんぴ)
=================
1. Double-click setup.bat (one time). It installs what the app needs and makes a desktop shortcut.
   If Node.js is missing it opens the download page - install the LTS version, then run setup.bat again.
2. Open Nyanpi from the shortcut.

Tabs
  Profile   - your AniList profile. "Customize" lets you drag/resize/hide widgets and change colours.
  Den       - your library. Add folders, press Scan; series are matched to AniList automatically.
  Discover  - browse anime. Open one -> "Find download" searches nyaa.si and sends it to qBittorrent.
  Settings  - AniList token (the Memento one is reused automatically), folders, qBittorrent, player.

Downloads need qBittorrent with the Web UI on (Tools > Options > Web UI). Files land in
<your library folder>\<anime title>, and the next Scan puts them in the Den.
