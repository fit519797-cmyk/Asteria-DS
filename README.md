# Eclipse of Asteria — Nintendo DS Homebrew

This is an original Nintendo DS homebrew game project designed for the DS Player emulator.

## Fastest build

This repository includes a GitHub Actions workflow. Upload the folder contents to a GitHub repository, then open **Actions** and run **Build Asteria DS**. The workflow uses the official devkitPro devkitARM container and uploads `Asteria.nds` as a downloadable artifact.

The DS build uses devkitARM/libnds, which is the standard DS homebrew toolchain. See devkitPro's DS examples and DS-homebrew documentation for the toolchain/build model.

## Controls
- D-pad: move
- A: interact / attack / continue
- B: back / run
- X: catch
- START: reserved for menu expansion

This game uses original names, creatures, maps, dialogue and graphics concepts; it does not include proprietary Pokémon/Pearl assets.
