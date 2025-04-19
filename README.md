# Iosevka Nerd Font

![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/shadowy-pycoder/Iosevka-nerd-font/total)

Patched with [Font Patcher](https://github.com/ryanoasis/nerd-fonts?tab=readme-ov-file#font-patcher) from [Iosevka version 33.2.1](https://github.com/be5invis/Iosevka/releases/tag/v33.2.1)

Commands used to patch fonts:

```shell
docker run --rm -v ./in:/in:Z -v ./out:/out:Z -e "PN=16" nerdfonts/patcher -c --progressbars --mono
```

```shell
docker run --rm -v ./in:/in:Z -v ./out:/out:Z -e "PN=16" nerdfonts/patcher -c --progressbars
```