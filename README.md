# Monaco Fira Code Nerd Font

Monaco Font with Fira Code ligatures and complete Nerd Font patched. Regular, medium, and bold.

## Modifications

[Fira Code 6.2](https://github.com/tonsky/FiraCode/releases/tag/6.2) is used as the base font. I modified the width, hight and spacing to align with the Monaco font. Then, I use the [MonacoB](https://github.com/vjpr/monaco-bold/tree/b77db4b6fc2e9df074f8db59cead862d7068e3d7) to replace all ASCII characters (0-127). Finally, I patched the font with [Nerd Fonts 3.0.2](https://github.com/ryanoasis/nerd-fonts/releases/tag/v3.0.2) complete glyphs.

### Font weights

- `Regular`: combination of `Fira Code Regular` and `MonacoB`
- `Medium`: combination of `Fira Code Medium` and `MonacoB Bold`
- `Bold`: combination of `Fira Code SemiBold` and `MonacoB2 Bold`

## How to install

- Clone this repo / download `MonacoFiraNerd/*.ttf`
- Install the font on your OS
- In your editor settings, change your font to `Monaco Fira Nerd`
- Enjoy 👀

## Known issues

Since the Fira Code font is wider than Monaco, there may be some ligatures that are oversized:

- `<!--`

## Related Projects

- [tonsky/FiraCode](https://github.com/tonsky/FiraCode)
- [vjpr/monaco-bold](https://github.com/vjpr/monaco-bold)
- [ryanoasis/nerd-fonts](https://github.com/ryanoasis/nerd-fonts)
- [GianCastle/FiraMonaco](https://github.com/GianCastle/FiraMonaco)
