# Vault Race 🏁

🇬🇧 **[English version: README.md](README.md)**

**Ein Link-Rennen durch deine eigenen Notizen.** Vault Race wählt eine Startnotiz und eine Zielnotiz aus deinem Vault. Du kommst nur über Links von der einen zur anderen – möglichst schnell und mit möglichst wenigen Klicks.

Es ist das klassische „Wiki-Rennen“, aber in deinem eigenen Obsidian-Vault. Nebenbei siehst du, wie gut deine Notizen miteinander verbunden sind.

<p align="center">
  <a href="https://buymeacoffee.com/jimmycallsaul"><img src="https://img.shields.io/badge/%E2%98%95%20Buy%20me%20a%20coffee-Vault%20Race%20unterst%C3%BCtzen-FFDD00?style=for-the-badge&labelColor=222222" alt="Buy me a coffee"></a>
</p>

> ☕ **Gefällt dir Vault Race?** Es ist kostenlos und bleibt kostenlos. Wenn es dich zum Schmunzeln gebracht hat, kannst du mir [einen Kaffee spendieren](https://buymeacoffee.com/jimmycallsaul). 💛
> 🐛 **Fehler entdeckt oder eine Idee?** [Melde es auf GitHub](https://github.com/JimmyCallSaul/vault-race/issues) – ich lese alles.

## Was du bekommst

- 🗂️ **Dein eigener Vault als Rennstrecke** – Start und Ziel kommen aus deinen Notizen, deine Links sind die Wege. Das Plugin prüft vorher, ob dein Vault genug verlinkte Notizen hat (mindestens 10).
- ⏱️ **Stoppuhr, Klickzähler und Par** – „Par“ ist die Anzahl Klicks auf dem kürzesten möglichen Weg.
- 📅 **Tagesaufgabe** für die mitgelieferten Strecken – am selben Tag für alle dasselbe Rennen, mit Zähler für Tage in Folge.
- 🟩 **Ergebnis zum Teilen** – ein kurzer Text im Wordle-Stil, der nichts verrät.
- 🧭 **Hilfen auf Wunsch** – Entfernung zum Ziel und ein Blick auf die Zielnotiz.
- 🎉 Töne und Konfetti (beides abschaltbar).
- 🌍 Oberfläche auf **Deutsch und Englisch**, je nach Sprache von Obsidian.

### Mitgelieferte Strecken zum Ausprobieren

Du brauchst keinen großen Vault, um loszulegen. Drei Strecken sind dabei:

| Strecke | Was es ist |
|---|---|
| **Logik** | 41 verlinkte Notizen zu Denkfehlern und gutem Argumentieren, jede mit einem Alltagsbeispiel auf Abruf. |
| **Stadt, Land, Fluss** | 47 Länder, 74 Städte und 28 Flüsse in Europa. Jede Notiz hat einen Steckbrief und einen Auszug aus Wikipedia. |
| **Bibel** | Alle 1189 Kapitel der World English Bible. Spiele nach Personen, Ereignissen, Orten, Tieren, Pflanzen – oder für Könner nach Kapitel und Vers. |

Der Bibeltext ist zurzeit nur auf Englisch enthalten. Die Oberfläche bleibt dabei deutsch.

## So wird gespielt

1. Öffne Vault Race über das Flaggen-Symbol in der Seitenleiste oder mit dem Befehl **„Vault Race: Spiel öffnen“**.
2. Wähle **Dein eigener Vault** oder eine der mitgelieferten Strecken.
3. Klicke dich über Links bis zur Zielnotiz. **Zurück** zählt auch als Klick.
4. Vergleiche deine Klicks mit Par und kopiere dein Ergebnis.

## Installation

Sobald das Plugin in der Community-Liste ist: *Einstellungen → Community-Plugins → Durchsuchen → „Vault Race“ → Installieren → Aktivieren*.

Von Hand: Lade `main.js`, `manifest.json` und `styles.css` aus dem neuesten Release herunter und lege sie in den Ordner `DeinVault/.obsidian/plugins/vault-race/`. Danach das Plugin in den Einstellungen aktivieren.

## Gut zu wissen (Offenlegung)

Gemäß den Entwicklerrichtlinien von Obsidian steht hier alles Wichtige in einfachen Worten:

- **Keine Internetverbindung.** Das Plugin selbst verbindet sich nie mit dem Internet. Es gibt keinen Server, kein Konto, keine Auswertung deines Verhaltens und keine Rangliste.
- **Deine Notizen bleiben in deinem Vault.** Im Modus „Dein eigener Vault“ liest das Plugin Notiznamen und Links über das Verzeichnis von Obsidian und zeigt deine Notizen zum Lesen an. Es verändert, kopiert oder verschickt sie nicht.
- **Was gespeichert wird:** deine Einstellungen und deine Ergebnisse, in der Datei `data.json` des Plugins in deinem Vault. Sonst nichts.
- **Links, die deinen Browser öffnen:** die Quellenlinks unter den Wikipedia-Auszügen, der Link „Buy me a coffee“ und der Link „Fehler oder Idee melden“. Sie öffnen sich nur, wenn du sie anklickst.
- **Spendenhinweis im Plugin:** Die Startseite und die Einstellungen enthalten einen kleinen festen Link „Buy me a coffee“ und einen Feedback-Link. Nach deinem fünften geschafften Rennen zeigt die Ergebnisseite einen Spendenhinweis – genau einmal, danach nie wieder. Es gibt keine Werbung von Dritten, und nichts wird aus dem Internet geladen.
- **Dateigröße:** `main.js` ist rund 5 MB groß, weil der Bibeltext und die Europa-Texte enthalten sind. So funktioniert alles ohne Internet.
- **Handy und Tablet:** Das Plugin ist dafür gebaut, wurde dort aber noch nicht getestet. Rückmeldungen sind willkommen.

## Inhalte und Lizenzen

- **Programmcode:** MIT, siehe [LICENSE](LICENSE).
- **Wikipedia-Auszüge** (Strecke „Stadt, Land, Fluss“): CC BY-SA 4.0, gekürzt und bereinigt. Alle Artikel mit genauer Version stehen in [WIKIPEDIA-SOURCES.md](WIKIPEDIA-SOURCES.md).
- **World English Bible:** gemeinfrei. **Querverweise:** OpenBible.info, CC BY.
- Einzelheiten (auf Englisch): [THIRD-PARTY-CONTENT.md](THIRD-PARTY-CONTENT.md).

Die Europa-Angaben und die Wikipedia-Auszüge haben den Stand Oktober 2026. Die Grenzen folgen den Listen von Wikipedia (Kosovo und Vatikanstadt sind enthalten).

## ☕ Unterstützen

Vault Race ist ein Hobbyprojekt. Wenn es dir gefällt:

- ⭐ Gib dem Repository einen Stern
- 🟩 Teile dein Tagesergebnis
- ☕ **[Spendier mir einen Kaffee](https://buymeacoffee.com/jimmycallsaul)**

Danke! 💛

## Kontakt

Fehler, Fragen oder Vorschläge: bitte [auf GitHub melden](https://github.com/JimmyCallSaul/vault-race/issues).
