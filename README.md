# Call Spell Sounds

Ansagen für **[Call Spell](https://github.com/INDYRULEZ/CallSpell)** — nur Tondateien, kein Code.

Getrennt vom Haupt-Addon, damit die Töne ein Addon-Update des Codes überleben und nur
angefasst werden, wenn wirklich neue Ansagen dazukommen.

## Installation

**Mit WowUp:** *Addons* → *Install from URL* → `https://github.com/INDYRULEZ/CallSpellSounds`

**Von Hand:** [Release](https://github.com/INDYRULEZ/CallSpellSounds/releases/latest) laden,
ZIP entpacken, Ordner `CallSpellSounds` nach `World of Warcraft\_retail_\Interface\AddOns\`.

## Benutzen

In Call Spell in der Spalte **Stimme** den Pfad eintragen:

```
Interface\AddOns\CallSpellSounds\Sounds\assist.ogg
Interface\AddOns\CallSpellSounds\Sounds\rescue.ogg
Interface\AddOns\CallSpellSounds\Sounds\paradox.ogg
```

Leer lassen = die Ansage, die im Haupt-Addon steckt.

## Eigene Töne hier ablegen

Neue Datei in `CallSpellSounds\Sounds\` legen und den Pfad in Call Spell eintragen.
Weil dieser Ordner **als Addon verwaltet** wird, gilt: bei einem Update dieses Addons werden
eigene Dateien darin ersetzt. Für eigene Töne, die dauerhaft bleiben sollen, ist
`Interface\AddOns\CustomSounds\` der bessere Ort — der gehört keinem Addon.

## Inhalt

| Datei | Ansage |
|---|---|
| `assist.ogg` | „Assist me!" |
| `rescue.ogg` | „Rescue!" |
| `paradox.ogg` | „Paradox!" |

Erzeugt mit neuronaler Sprachausgabe (Edge TTS, Stimme `en-US-ChristopherNeural`), danach
gekürzt, komprimiert und auf Lautstärke gebracht. Alle drei unter einer Sekunde.

## Lizenz

Die Tondateien: siehe Hinweis im Haupt-Addon — für eigene Zwecke erzeugt, Weitergabe
nach bestem Wissen, aber ohne Gewähr auf lizenzrechtliche Einwandfreiheit.

Der Rest (dieses README, die `.toc`): MIT.
