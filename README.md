# Welcome to the Raku Localization Project

The Raku Localization Project provides natural language localizations of the [Raku Programming Language](https://raku.org).

## Supported localizations

- [Dutch](https://raku.land/zef:l10n/L10N::NL)
- [French](https://raku.land/zef:l10n/L10N::FR)
- [German](https://raku.land/zef:l10n/L10N::DE)
- [Hungarian](https://raku.land/zef:l10n/L10N::HU)
- [Italian](https://raku.land/zef:l10n/L10N::IT)
- [Japanese](https://raku.land/zef:l10n/L10N::JA)
- [Portuguese](https://raku.land/zef:l10n/L10N::PT)
- [Welsh](https://raku.land/zef:l10n/L10N::CY)

## Blog posts

- [Creating a new programming language - Draig](https://dev.to/finanalyst/creating-a-new-programming-language-draig-503p)
- [Ryuu - a Japanese dragon](https://dev.to/finanalyst/ryuu-a-japanese-dragon-2e7m)

## Want to add a localization?

- Install the [L10N](https://raku.land/zef:l10n/L10N) distribution
- Change into a directory in which you want your localization repository to live
- Run the command: new-localization XX Xerxes  (where XX is the ISO 639-1 code for the language, and Xerxes is the name of the language in English)
- Change into the newly created directory
- Start editing the XX.l10n file
- When done, run the "update-localization" command
- Install the repository locally with: zef install . --force
- Start testing your localized code with "xerku" (instead of "raku"), where the first three letters are of the language that you specified)
