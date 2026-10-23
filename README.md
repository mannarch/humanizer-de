# Humanizer DE

Ein Skill für Claude Code, der deutsche Texte so überarbeitet, dass sie nicht mehr nach KI klingen. Fakten, Zahlen, Namen, Zitate und Code bleiben dabei unverändert.

Der Skill streicht leere Floskeln, Werbesprache, Behördendeutsch und typische Satzschablonen und ersetzt sie durch konkrete, direkte Sätze. Er ist als Lektorat gedacht, nicht um KI-Detektoren zu täuschen.

## Installation

```bash
git clone https://github.com/mannarch/humanizer-de.git ~/.claude/skills/humanizer-de
```

Danach Claude Code neu starten.

## Verwendung

Text einfügen und zum Beispiel schreiben: „Das klingt nach KI, mach es natürlicher.“ Oder direkt `/humanizer-de` aufrufen.

Optional kann man einen Modus nennen:

- **normal**: natürlich, klar, freundlich (Standard)
- **locker**: wie gesprochen, kurze Sätze, für Social Media und Nachrichten
- **professionell**: sachlich und höflich, für Angebote, Geschäfts-E-Mails, Webseiten
- **minimal**: nur Floskeln und Füllwörter streichen

## Beispiel

**Vorher:**
> Es wird darauf hingewiesen, dass die Durchführung der Reservierung grundsätzlich telefonisch erfolgen muss. Wir bitten um Ihr Verständnis.

**Nachher:**
> Bitte reserviere telefonisch. Online geht das bei uns noch nicht.

## Lizenz

MIT, siehe [LICENSE](LICENSE).
