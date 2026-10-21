# Contributing

Thanks for wanting to help with **Jagged Alliance 2 UINT-16** mod for Jagged Alliance 2! It is a free mod made by fans, for fans, and every bug report, idea and fix makes it better.

## Ways to help

| I want to… | Go to |
|---|---|
| 🐞 report a bug | [Reporting a bug](#reporting-a-bug) |
| 💡 suggest a feature | [Suggesting a feature](#suggesting-a-feature) |
| 🧪 test with my saves and mods | [Testing](#testing) |
| 🛠️ change the data or the code | [Code](#code) |

## Reporting a bug

Open an [issue](../../issues) and include:

- the mod version (the name of the release archive) and your game version (the 1.13 build from `JA2_113-Version.txt`, and any other mods you use);
- whether you started the game with `ja2u16.exe` (the mod's own exe) or with the stock `ja2.exe`;
- what you did, what you expected and what happened instead;
- a screenshot, and the save game if the problem is with one (zip it if it is large).

Please search the [open issues](../../issues) first — maybe it is already reported.

> [!IMPORTANT]
> If the mod damaged a save game, say so in the title. Saves made with an older version of the mod may not load in a newer one — start a new game after updating. Attach the broken save to the issue if you can.

## Suggesting a feature

Open an issue that starts with **Idea:** and describe what you want to see in the game and why. Screenshots or mock-ups help a lot.

## Testing

The mod is made for Jagged Alliance 2 v1.13. Reports from other builds and mods are very welcome — tell us in an issue what works and what does not, with the game version and the mod's name.

Always test on a **copy** of your game folder.

## Code

The mod lives in its own folder `Data-UINT16` next to the stock `Data-1.13`, which it does not change, and runs from its own `ja2u16.exe`.

1. Make your change in `Data-UINT16` (or in the game source, if it needs the exe).
2. Test it on a **copy** of your game folder, never on the only one you have, and start a **new game**.
3. Open an issue describing the change and attach a patch or a link to your fork.

Keep the style of the existing texts: short, plain English, in the spirit of the films and games the teams come from.

## License

By contributing you agree that your contribution is released under the project's [CC BY-NC-SA 4.0](LICENSE) license. The mod must stay free — contributions that add payments, ads or paywalls will not be accepted.

## Conduct

Be kind and respectful. See the [Code of Conduct](CODE_OF_CONDUCT.md).
