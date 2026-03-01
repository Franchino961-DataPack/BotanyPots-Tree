# BotanyPots Tree

A Minecraft datapack that adds tree sapling recipes for the BotanyPots mod.

[![en](https://img.shields.io/badge/lang-en-red.svg)](README.md)
[![it](https://img.shields.io/badge/lang-it-green.svg)](MD/README.it.md)

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

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs or issues
- Suggest new features or improvements
- Submit pull requests

## 🔗 Links

- [BotanyPots Mod](https://www.curseforge.com/minecraft/mc-mods/botany-pots)
- [Minecraft Wiki - Trees](https://minecraft.fandom.com/wiki/Tree)

## 📝 Changelog

See [CHANGELOG.en.md](MD/CHANGELOG.en.md) for version history and updates.

## 💬 Support

If you encounter any issues or have questions:
- Check existing issues in the repository
- Create a new issue with detailed information
- Include your Minecraft version and BotanyPots version

---

**Note**: This datapack requires the BotanyPots mod to be installed. It will not work in vanilla Minecraft.
