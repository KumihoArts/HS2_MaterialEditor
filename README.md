# HS2 Material Editor - Enhanced UI Fork

A fork of [KK_Plugins](https://github.com/IllusionMods/KK_Plugins) MaterialEditor, rebuilt with a significantly enhanced UI for **HoneySelect 2**. This repo contains only the MaterialEditor source.

## Features

- **Dark mode** - full theme toggle in F1 config, live without restart
- **Window and tooltip opacity** - background panels fade, text stays opaque
- **Collapsible renderer/material rows** - with persistent collapse state
- **Section collapse** - collapse entire Renderers or Materials section via footer
- **Sticky section bars** - section header follows scroll position
- **Edited property indicators** - changed properties in cyan/bold, visible when collapsed
- **Dockable texture preview panel** - locks to ME window, free aspect ratio resize
- **Inline renderer enable toggle** - always visible on renderer rows
- **Persist search toggle** - filter survives object selection changes
- **Custom font selector** - JetBrains Mono, Cascadia Mono, Noto Sans, Arial (F1 config)
- **Styled sliders** - distinct track, fill, and circular handle per theme
- **Flat squared UI style** throughout
- **HS2 Maker stay-open** - ME refreshes instead of closing when switching outfit/hair

## Installation

1. Install [BepInEx v5](https://github.com/BepInEx/BepInEx/releases), [BepisPlugins](https://github.com/IllusionMods/BepisPlugins/releases), and [IllusionModdingAPI](https://github.com/IllusionMods/IllusionModdingAPI/releases)
2. Download `HS2_MaterialEditor.dll` from the [Releases](../../releases) page
3. Place it in `[HS2 install]\BepInEx\plugins\HS2_Plugins\`  
4. Remove any pre-existing `HS2_MaterialEditor.dll` first

> This replaces the stock MaterialEditor. Do not run both at the same time.

## Building from source

Requires Visual Studio 2022+ with the .NET desktop development and Game development with Unity workloads, and .NET Framework 4.6 targeting pack. All NuGet dependencies resolve automatically on first build.

Open `KK_Plugins.sln`, right-click `MaterialEditor.HS2` > **Build**.  
Output: `bin\build\HS2.MaterialEditor\HS2_MaterialEditor.dll`  

## Based on

[KK_Plugins](https://github.com/IllusionMods/KK_Plugins) by DeathWeasel1337 / ManlyMarco - GPL-3.0

## License

GPL-3.0 - see [LICENSE](LICENSE)
