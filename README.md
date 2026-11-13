# Petit Copter (Xbox) - English Translation Patch

English translation of **Petit Copter** for the original Xbox (Japanese release). It translates the menus, missions, names and messages (about 190 strings).

> **This repository contains no game data.** It only stores the differences between the Japanese `Default.xbe` and the translated one. You need your own legally obtained copy of the game. Your original files are never modified.

## What you need

- Your own Japanese *Petit Copter* disc, extracted to a folder (the one that contains `Default.xbe`)
- Python 3.6+ (for the script), **or** any xdelta tool

## How to apply

### Option A: Python script (Windows, Linux, macOS)

```
python PetitCopter_EN_patcher.py "<Japanese game folder>" "<NEW output folder>"
```

Run it without arguments and it will ask for the two folders. Add `--xbe-only` to write only the patched `Default.xbe` instead of copying the whole game.

### Option B: xdelta

Apply `PetitCopter_EN_v1.0.xdelta` to your `Default.xbe` with xdelta3, xdeltaUI or Delta Patcher.

Then play the output folder on a softmodded console or an emulator.

## Checksums (SHA-256)

| File | SHA-256 |
|---|---|
| Original Japanese `Default.xbe` | `2fef30cd1663c2abcf62f479143c9d87ac21b17c6ebd7f4d5b613b7b96d06512` |
| Patched English `Default.xbe` | `daa26948209eaf69aa0cf73d501bbbf6a1db9f9fc2d2c4063065377a6e26b6af` |

If your original does not match, you have a different dump or version and the patcher will refuse to run.

## Known limitations

- Text only. The title logo and text inside images are not translated.
- Translation made with the help of AI (Claude) and reviewed by XadPT. Corrections are welcome: open an issue or a pull request.

## Credits

Patch and translation review by **XadPT**.

## License

The patcher script is released under the MIT License (see `LICENSE`). *Petit Copter* and its contents belong to their respective owners; this project is not affiliated with them.
