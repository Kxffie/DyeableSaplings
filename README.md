# Dyeable Saplings

View on Modrinth: https://modrinth.com/datapack/dyeable-saplings

A simple Minecraft datapack that lets you dye any sapling into a specific tree type. Just combine any sapling with a matching dye in a crafting table to get the new sapling.

## Features

* Shapeless recipes for all eight sapling types:

  * Oak ← green dye
  * Spruce ← brown dye
  * Birch ← white dye
  * Jungle ← lime dye
  * Acacia ← orange dye
  * Dark Oak ← black dye
  * Cherry ← pink dye
  * Pale Oak ← light gray dye
* Works on Minecraft 1.21.4 and up
* No commands or functions required, just pure crafting recipes

## Installation

1. Download or clone this repo into your world’s `datapacks` folder:

   ```bash
   git clone https://github.com/kxffie/dyeable-saplings.git
   ```
2. Open your world in Minecraft 1.21.4+ and run:

   ```mcfunction
   /reload
   ```
3. Confirm the datapack is active:

   ```mcfunction
   /datapack list
   ```

## Usage

1. Open a crafting table.
2. Place any sapling in one slot.
3. Place the matching dye in any other slot.
4. Take the new sapling from the result box.

Example: oak sapling + pink dye → cherry sapling (no visual change, but recipe confirms pack is working)

## File structure

```
DyeableSaplings/
├ pack.mcmeta
├ pack.png        # icon displayed in the datapack list
└ data/
  └ dyeablesaplings/
    └ recipes/
      ├ dye_to_oak_sapling.json
      ├ dye_to_spruce_sapling.json
      ├ dye_to_birch_sapling.json
      ├ dye_to_jungle_sapling.json
      ├ dye_to_acacia_sapling.json
      ├ dye_to_dark_oak_sapling.json
      ├ dye_to_cherry_sapling.json
      └ dye_to_pale_oak_sapling.json
```

## Modrinth page

Check out more details and downloads on Modrinth:
[https://modrinth.com/user/kxffie](https://modrinth.com/user/kxffie)

## Contributing

Feel free to open issues or pull requests. If you find a bug or have an idea for a new feature, let me know.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
