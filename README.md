# Nyx — Updates

Veröffentlichte Fassungen von **Nyx**, dem Desktop-Maskottchen für macOS: eine
Pixel-Katze, die auf dem Dock lebt und auf ihre Umgebung reagiert.

Hier liegen ausschließlich die fertigen Archive und der Appcast, den die App
abfragt. Der Quellcode wird nicht veröffentlicht — die Sprites stammen aus einem
gekauften Pack, dessen Bedingungen die Weitergabe des Materials untersagen.

## Was hier liegt

| Datei | Zweck |
|---|---|
| `appcast.xml` | Die Liste der Fassungen. Nyx fragt sie täglich ab. |
| `Nyx-*.zip` | Die Archive selbst, jedes einzeln signiert. |

## Installieren

Neuere Fassungen meldet Nyx von selbst — vorausgesetzt, die automatische Suche
ist eingeschaltet (Rechtsklick auf die Katze → Updates). Wer lieber von Hand
lädt, nimmt das jüngste Archiv aus [Releases](../../releases), entpackt es und
legt `Nyx.app` in den Ordner „Programme".

## Prüfsummen

Jedes Archiv im Appcast trägt eine EdDSA-Signatur. Nyx installiert nur, was
damit übereinstimmt; ein verändertes Archiv wird abgelehnt.
