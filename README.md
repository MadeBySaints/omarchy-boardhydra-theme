# BoardHydra theme for Omarchy

A violet-black theme with blue, teal, green and gold accents for [Omarchy](https://omarchy.org/), based on [BoardHydra](https://boardhydra.com), with hydra and kanban-board wallpapers.

![Preview](preview.png)

## Screenshots

| Hydra wallpaper | Board wallpaper with BoardHydra Desk |
| --- | --- |
| ![BoardHydra hydra wallpaper with blue, teal and green heads on a violet-black desktop](screenshots/hydra-desktop.png) | ![BoardHydra Desk displaying sample cards in the Holo style over the board wallpaper](screenshots/board-desktop.png) |

The live cards, search, filters and Holo styling in the board screenshot come from the optional [BoardHydra Desk plugin](https://github.com/MadeBySaints/omarchy-boardhydra-desk). The theme supplies the wallpaper and desktop palette.

<details>
<summary>Lock screen preview</summary>

![BoardHydra lock screen](preview-unlock.png)

</details>

## Install

```bash
omarchy theme install https://github.com/MadeBySaints/omarchy-boardhydra-theme.git
```

The theme installs as `boardhydra` and is applied right away. You can switch back to it later with `omarchy theme set boardhydra`.

## Update

```bash
omarchy theme update
```

## Wallpapers

- `1-hydra.png`: the BoardHydra hydra
- `2-board.png`: a kanban board with painted columns. It is meant to be used with the [BoardHydra Desk](https://github.com/MadeBySaints/omarchy-boardhydra-desk) shell plugin, which draws live cards on top of it.

Use `omarchy theme bg next` to cycle between them.

## Remove

```bash
omarchy theme remove boardhydra
```

## License

The config files (`colors.toml`, `icons.theme`) are MIT licensed. The wallpapers and unlock artwork are © madebysaints, all rights reserved: you can use them as part of this theme but not reuse or modify them elsewhere. See [LICENSE](LICENSE) for details.
