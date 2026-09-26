# Welcome to the Raku Localization Project

The Raku Localization Project provides natural language localizations of the [Raku Programming Language](https://raku.org).

## Supported localizations

- [Bulgarian](https://raku.land/zef:antononcube/L10N::BG)
- [Dutch](https://raku.land/zef:l10n/L10N::NL)
- [Esbelando, Esperanto](https://raku.land/zef:l10n/L10N::EO)
- [French](https://raku.land/zef:l10n/L10N::FR)
- [German](https://raku.land/zef:l10n/L10N::DE)
- [Hungarian](https://raku.land/zef:l10n/L10N::HU)
- [Italian](https://raku.land/zef:l10n/L10N::IT)
- [Japanese](https://raku.land/zef:l10n/L10N::JA)
- [Latvian](https://raku.land/zef:ash/L10N::LV)
- [Portuguese](https://raku.land/zef:l10n/L10N::PT)
- [Russian](https://raku.land/zef:ash/L10N::RU)
- [Spanish](https://raku.land/zef:l10n/L10N::ES)
- [TaoYuan, Chinese](https://raku.land/zef:l10n/L10N::ZH)
- [Ukrainian](https://raku.land/zef:ash/L10N::UK)
- [Welsh](https://raku.land/zef:l10n/L10N::CY)

## Blog posts

- [Creating a new programming language - Draig](https://dev.to/finanalyst/creating-a-new-programming-language-draig-503p)
- [Ryuu - a Japanese dragon](https://dev.to/finanalyst/ryuu-a-japanese-dragon-2e7m)
- [Raku: la lingua dove posso parlare italiano](https://andrewshitov.com/2026/09/15/raku-la-lingua-dove-posso-parlare-italiano/)

## Want to add a localization?

- Install the [L10N](https://raku.land/zef:l10n/L10N) and [App::Mi6](https://raku.land/zef:skaji/App::Mi6) distributions
- Change into a directory in which you want your localization repository to live
- Run the command: new-localization XX Xerxes  (where XX is the ISO 639-1 code for the language, and Xerxes is the name of the language in English)
- Change into the newly created directory
- Start editing the XX.l10n file (where XX is the ISO 639-1 code for the language)
- When done, run the "update-localization" command
- Install the repository locally with: zef install . --force
- Start testing your localized code with "xerku" (instead of "raku"), where the first three letters are of the language that you specified)
- Update to github or other online service as appropriate

## Want to update a localization?

- Run the "update-keys" command.  This will add any new translation keys.
- Edit the XX.l10n file as appropriate (where XX is the ISO 639-1 code for the language)
When done, run the "update-localization" command
- Install the repository locally with: zef install . --force
- Start testing your localized code with "xerku" (instead of "raku"), where the first three letters are of the language that you specified)
- Update to github or other online service as appropriate
