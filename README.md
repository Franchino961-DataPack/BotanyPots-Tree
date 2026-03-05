# 🌳 BotanyPots Trees

A Minecraft datapack that adds tree sapling recipes for the BotanyPots mod.

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)]()
[![Minecraft](https://img.shields.io/badge/Minecraft-1.21.1-green.svg)](https://www.minecraft.net/)
[![Pack Format](https://img.shields.io/badge/Pack%20Format-61-lightgrey.svg)]()
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[![en](https://img.shields.io/badge/lang-en-red.svg)](README.md)
[![it](https://img.shields.io/badge/lang-it-green.svg)](MD/README.it.md)

> 📝 **Changelog**: See [CHANGELOG.en.md](MD/CHANGELOG.en.md) for version history.

## 📋 Description

This datapack provides custom recipes for growing various tree saplings in Botany Pots. It includes recipes for all vanilla Minecraft tree types, allowing you to efficiently grow trees in compact botany pots.

## ✨ Features

- **Complete Tree Collection**: Recipes for all vanilla Minecraft trees
- **Optimized Growth Times**: Balanced growth rates for fair gameplay
- **Configurable Drops**: Each tree provides saplings and logs with customizable chances

## 🌳 Supported Trees

- Oak
- Birch
- Spruce
- Acacia
- Dark Oak
- Jungle
- Cherry
- Mangrove

## 📦 Requirements

- **Minecraft**: 1.21.4+ (or compatible version)
- **BotanyPots Mod**: Required for the datapack to function
- **Forge/Fabric**: Depending on your BotanyPots version

## 🔧 Installation

1. Download the datapack
2. Place the datapack folder in your world's `datapacks` folder
   - Location: `.minecraft/saves/[YourWorldName]/datapacks/`
3. Reload datapacks in-game using `/reload` or restart the world
4. Verify installation with `/datapack list`

## 🎮 Usage

1. Craft or obtain a Botany Pot (from the BotanyPots mod)
2. Add appropriate soil (dirt-based soils work for all trees)
3. Plant any supported sapling
4. Wait for the pot to grow and automatically harvest drops
5. Collect logs and additional saplings from the pot

## ⚙️ Configuration

Each crop recipe can be customized by editing the JSON files in:
```
data/botanypots/recipe/minecraft/crops/
```

Parameters you can adjust:
- `grow_time`: Time in ticks for full growth cycle (1200 = 60 seconds)
- `chance`: Drop probability (0.0 to 1.0)
- `minRolls`/`maxRolls`: Number of items dropped per harvest

## ❓ FAQ

**Q: Does this work on existing worlds?**
A: Yes, add the datapack to your world and run `/reload`.

**Q: Can I use this with other datapacks?**
A: Generally yes, unless another datapack modifies BotanyPots tree recipes in the same namespace.

**Q: Does this work without BotanyPots?**
A: No. The BotanyPots mod is required — the datapack will be inactive without it.

**Q: Can I customize growth speed or drops?**
A: Yes! Edit the JSON files in `data/botanypots/recipe/minecraft/crops/`. See the Configuration section for details.

## 📄 License

This project is licensed under the [MIT License](LICENSE). Feel free to include it in your modpacks!

## 👤 Author

**Franchino961** — [GitHub](https://github.com/Franchino961-DataPack)

## 🤝 Contributing

Contributions are welcome!
- Open an [Issue](../../issues) to report bugs or suggest new recipes
- Open a [Pull Request](../../pulls) to contribute

## 🗨️ Support

If you encounter any issues or have questions:
- Check [existing issues](../../issues)
- Create a new issue including: Minecraft version and BotanyPots version

## 🔗 Links

- [BotanyPots Mod](https://www.curseforge.com/minecraft/mc-mods/botany-pots)
- [Minecraft Wiki - Trees](https://minecraft.fandom.com/wiki/Tree)

## 📝 Changelog

See [CHANGELOG.en.md](MD/CHANGELOG.en.md) for full version history.

---

> ⚠️ **Note**: This datapack requires the BotanyPots mod to be installed. It will not work in vanilla Minecraft.
