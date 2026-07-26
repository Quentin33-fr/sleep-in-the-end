<div align="center">

![Sleep in the End](https://cdn.modrinth.com/data/cached_images/f837400aa1c40eea07207e739ea117365cd720f9_0.webp)

**A minimal datapack that allows sleeping in the End.**

![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Minecraft](https://img.shields.io/badge/Minecraft-26.2+-4CAF50?style=for-the-badge&logo=minecraft)
![Discord](https://img.shields.io/badge/Discord-itzchoko__-5865F2?style=for-the-badge&logo=discord)

</div>

---

## 📖 Description

**Sleep in the End** tweaks the End dimension rules to let players **sleep and set their respawn point** in a bed, just like in the Overworld.

By default, Minecraft prevents sleeping in the End and the Nether. This datapack removes that restriction for the End only, without altering any other dimension mechanics (Ender Dragon fight, crystals, portals, etc.).

## ✨ Features

- Allows sleeping in the End as soon as the environment is dark enough.
- Lets you **set your respawn point** in the End.

## 📦 Installation

1. Download the `sleep_in_the_end.zip` file (or clone this repository).
2. Place the `.zip` file into your world's `datapacks` folder:
   ```
   .minecraft/saves/<world_name>/datapacks/
   ```
3. In-game, run:
   ```
   /reload
   ```
4. Make sure the datapack is active:
   ```
   /datapack list enabled
   ```

## 🔧 Compatibility

| Minecraft Version | Compatible |
|---|---|
| 26.2+ | ✅ |
| Earlier versions | ⚠️ Untested |

> This datapack overrides the native `dimension_type` file for the End. If another datapack modifies `minecraft:the_end`, only the last one loaded will take effect.

## 🗂️ Project Structure

```
sleep_in_the_end/
├── pack.mcmeta
└── data/
    └── minecraft/
        └── dimension_type/
            └── the_end.json
```

## 🤝 Contributing

Suggestions and pull requests are welcome. For major changes, please open an *issue* first to discuss it. Discord: itzchoko_

## 📜 License

Distributed under the MIT License. See the `LICENSE` file for more details.

---

<div align="center">
Made with ❤️ by ItzChoko.</sub>
</div>
