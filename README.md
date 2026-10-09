# Vault Race 🏁

🇩🇪 **[Deutsche Fassung: README.de.md](README.de.md)**

**A link race through your own notes.** Vault Race picks a start note and a target note from your vault. Get from one to the other using links only – as fast as you can and with as few clicks as possible.

It is the classic “wiki race”, but played in your own Obsidian vault. And it quietly shows you how well your notes are connected.

<p align="center">
  <a href="https://buymeacoffee.com/jimmycallsaul"><img src="https://img.shields.io/badge/%E2%98%95%20Buy%20me%20a%20coffee-support%20Vault%20Race-FFDD00?style=for-the-badge&labelColor=222222" alt="Buy me a coffee"></a>
</p>

> ☕ **Enjoying Vault Race?** It is free and will stay free. If it made you smile, you can [buy me a coffee](https://buymeacoffee.com/jimmycallsaul). 💛
> 🐛 **Found a bug or have an idea?** [Open an issue](https://github.com/JimmyCallSaul/vault-race/issues) – I read every one.

## What you get

- 🗂️ **Your own vault as the race track** – start and target come from your notes, your links are the routes. The plugin first checks whether your vault has enough linked notes (at least 10).
- ⏱️ **Timer, click counter and par** – “par” is the number of clicks on the shortest possible path.
- 📅 **Daily challenge** for the built-in tracks – the same race for everyone on the same day, with streak counter.
- 🟩 **Result to share** – a short Wordle-style text without spoilers.
- 🧭 **Optional hints** – distance to the target, and a look at the target note.
- 🎉 Sounds and confetti (both can be switched off).
- 🌍 Interface in **English and German**, following Obsidian's language.

### Built-in tracks to try

You do not need a big vault to start. Three tracks are included:

| Track | What it is |
|---|---|
| **Logic** | 41 linked notes about fallacies and good arguing, each with an everyday example on demand. |
| **Cities, countries, rivers** | 47 countries, 74 cities and 28 rivers of Europe. Each note has key facts and an excerpt from Wikipedia. |
| **The Bible** | All 1,189 chapters of the World English Bible. Play by people, events, places, animals, plants – or hardcore by chapter. |

## How to play

1. Open Vault Race from the ribbon icon or with the command **“Vault Race: Open game”**.
2. Choose **Your own vault** or one of the built-in tracks.
3. Click links until you reach the target. **Back** counts as a click, too.
4. Compare your clicks with par and copy your result.

## Installation

Once the plugin is in the community list: *Settings → Community plugins → Browse → “Vault Race” → Install → Enable*.

Manually: download `main.js`, `manifest.json` and `styles.css` from the latest release and put them into `YourVault/.obsidian/plugins/vault-race/`. Then enable the plugin in the settings.

## Good to know (disclosures)

Following the Obsidian developer policies, here is everything relevant in plain words:

- **No network use.** The plugin itself never connects to the internet. There is no server, no account, no telemetry, no leaderboard.
- **Your notes stay in your vault.** In the own-vault mode the plugin reads note names and links through Obsidian's own index and shows your notes for reading. It does not change, copy or send them.
- **What is saved:** your settings and your daily results, in the plugin's own `data.json` inside your vault. Nothing else.
- **Reading your vault:** to build the race, the plugin lists the Markdown notes of your vault and their links (this is what Obsidian's review reports as “vault enumeration”). Other file types are ignored.
- **Clipboard:** the plugin only writes to the clipboard, and only when you click “Copy result”. It never reads it.
- **Links that open your browser:** the source links below the Wikipedia excerpts, the “Buy me a coffee” link and the “Report a bug” link. They only open when you click them.
- **Support note inside the plugin:** the start screen and the settings contain a small static “Buy me a coffee” link and a feedback link. After your 5th finished race, the result screen shows one support note – exactly once, never again. There are no ads from third parties and nothing is loaded from the internet.
- **File size:** `main.js` is about 5 MB because the Bible text and the Europe texts are bundled, so that everything works offline.
- **Mobile:** the plugin is built to work on mobile, but it has not been tested there yet. Feedback is welcome.

## Content and licences

- **Code:** MIT, see [LICENSE](LICENSE).
- **Wikipedia excerpts** (Europe track): CC BY-SA 4.0, shortened and cleaned up. All articles and versions are listed in [WIKIPEDIA-SOURCES.md](WIKIPEDIA-SOURCES.md).
- **World English Bible:** public domain. **Cross-references:** OpenBible.info, CC BY.
- Details: [THIRD-PARTY-CONTENT.md](THIRD-PARTY-CONTENT.md).

The Europe facts and the Wikipedia excerpts reflect October 2026. Borders follow Wikipedia's lists (Kosovo and Vatican City are included).

## ☕ Support

Vault Race is a hobby project. If you like it:

- ⭐ Star the repository
- 🟩 Share your daily result
- ☕ **[Buy me a coffee](https://buymeacoffee.com/jimmycallsaul)**

Thank you! 💛

## Contact

Bugs, questions or suggestions: please [open an issue on GitHub](https://github.com/JimmyCallSaul/vault-race/issues).
