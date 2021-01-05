# LSDisJ

Disassembly of [Little Sound DJ](https://www.littlesounddj.com/lsd/index.php).
This targets the latest stable version at the time of writing, `8.5.1`.

## Prerequisites

  - [Git](https://git-scm.com/downloads)
  - [LSDj 8.5.1](https://www.littlesounddj.com/lsd/latest/rom_images/) (download to `path/to/LSDisJ/src/lsdj.gb`)
  - [Python](https://www.python.org/)
  - [rgbds](https://github.com/gbdev/rgbds)

## Usage

```bash
# Install
git clone --recursive https://github.com/rbong/LSDisJ

# Create src/lsdj.asm
make disassemble

# Recompile lsdj.gb
make

# Remove everything
make clean
```

## External Links

  - [LSDPatcher](https://github.com/jkotlinski/lsdpatch) (can be used to patch kits, palettes, and fonts)
  - [Emulicious](https://emulicious.net/) (can be used for debugging)
  - [Awesome Game Boy Development list](Awesome Game Boy Development) (Game Boy development resources)
