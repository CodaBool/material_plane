# CodaBool Fork
- just removed low battery notification on sensor
- remove notification about game pause

## Download
`https://raw.githubusercontent.com/CodaBool/material_plane/refs/heads/main/module.json`

## Links
- [GitHub Repository](https://github.com/CodaBool/material_plane)
- [Releases](https://github.com/CodaBool/material_plane/releases)

# Change details
- src/IRtoken/IRtoken.js
  - `if (game.paused) {` comment this whole conditional
- mine/src/Misc/misc.js
  - `updatePowerState` set
