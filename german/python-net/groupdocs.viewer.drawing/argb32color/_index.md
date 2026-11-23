---
title: "Argb32Color Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt eine 32‑Bit‑Farbe im ARGB‑Format dar, mit 8 Bit pro Kanal (Alpha, Rot, Grün, Blau)."
type: docs
url: /de/python-net/groupdocs.viewer.drawing/argb32color/
is_root: false
weight: 10
---


## Argb32Color class

Stellt 32-Bit-Farbe im ARGB-Format dar, mit 8 Bit pro Kanal (Alpha, Rot, Grün, Blau). Unterstützt Transparenz.

Dieser Typ ist für (aber nicht ausschließlich) CSS‑Operationen gedacht. Weitere Informationen: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Der Argb32Color‑Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/argb32color/__init__/) |  |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Prüft, ob diese Farbe gleich der angegebenen [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) ist. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Bestimmt, ob diese Farbe gleich der angegebenen [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) ist. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#obj) | Prüft, ob diese Farbe der angegebenen nicht gecasteten Farbe entspricht. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_rgb_24_color/) |  |
| [from_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_argb/#argb) | Erstellt eine Argb32Color‑Instanz aus einem 32‑Bit‑ARGB‑Wert, kompatibel mit Werten, die von `System.Drawing.Color.ToArgb()` erzeugt werden. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Erstellt eine neue [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑Instanz aus der angegebenen Instanz, jedoch mit einem neu definierten Alpha‑(Opazitäts‑)Wert. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Erstellt eine neue Argb32Color‑Instanz aus einem angegebenen Rgb24Color, jedoch mit einem angegebenen Alpha‑(Opazitäts‑)Wert. |
| [from_other_with_alpha_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_argb_32_color/) |  |
| [from_other_with_alpha_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/#red-green-blue) | Erstellt einen Argb32Color‑Wert aus angegebenen Rot‑, Grün‑ und Blau‑Kanälen, wobei der Alpha‑Kanal vollständig undurchsichtig gesetzt wird. |
| [from_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgba/#red-green-blue-alpha) | Erstellt einen [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑Wert aus angegebenen Rot‑, Grün‑, Blau‑ und Alpha‑Kanalwerten. |
| [from_single_value_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_single_value_rgb/#value) | Erstellt eine vollständig undurchsichtige (A=255) Farbe aus einem einzelnen Byte‑Wert, der auf alle Kanäle angewendet wird. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_brightness/) | Gibt die Helligkeit (Lightness) des Hue‑Saturation‑Lightness (HSL)‑Modells für diese [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑Instanz zurück. |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hash_code/) | Gibt einen Hash‑Code zurück, der die aktuelle Farbe definiert; nicht kompatibel mit `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hue/) | Gibt den Farbtonwert (Hue) des Hue‑Saturation‑Lightness (HSL)‑Modells in Grad für diese [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑Instanz zurück; ist R == G == B, ist der Farbton bedeutungslos und die Methode gibt 0 zurück. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_saturation/) | Gibt die Hue‑Saturation‑Lightness (HSL)-Sättigung dieser [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) Instanz zurück. |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_argb/) | Gibt den ARGB-Wert dieser [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) Instanz zurück, kompatibel mit der Methode `System.Drawing.Color.ToArgb()`. |
| [to_hex_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgb/) | Serialisiert diese [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) Instanz in die hexadezimale Notation `##RRGGBB` als Zeichenkette ohne den Alphakanal. |
| [to_hex_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgba/) | Serialisiert diese [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) Instanz in die hexadezimale Notation `##RRGGBBAA` als Zeichenkette mit Alphakanal. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgb/) | Serialisiert diese [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) Instanz in die CSS‑Funktionsnotation `rgb`, wobei der Alphakanal weggelassen wird. |
| [to_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgba/) | Serialisiert diese [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) Instanz in die CSS‑Funktionsnotation 'rgba'. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_string/) | Serialisiert die Argb32Color‑Instanz in die am besten geeignete CSS‑Funktionsnotation, abhängig von der Transparenz. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [a](/viewer/python-net/groupdocs.viewer.drawing/argb32color/a/) | Die Alpha‑Komponente der Farbe als 8‑Bit‑vorzeichenlose Ganzzahl im Bereich 0..255. |
| [alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/alpha/) | Die Alpha‑Komponente der Farbe als Gleitkommazahl im Bereich 0..1. |
| [b](/viewer/python-net/groupdocs.viewer.drawing/argb32color/b/) | Die Blau‑Komponente der Farbe als 8‑Bit‑vorzeichenlose Ganzzahl im Bereich 0..255. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/argb32color/g/) | Die Grün‑Komponente der Farbe als 8‑Bit‑vorzeichenlose Ganzzahl im Bereich 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) | Die Eigenschaft gibt an, ob diese [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) Instanz standardmäßig (transparent) ist, d.h. alle vier Kanäle auf 0 gesetzt sind; sie entspricht [`Argb32Color.is_empty`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/). |
| [is_empty](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) | Die Eigenschaft gibt an, ob diese [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) Instanz nicht initialisiert ist (alle vier Kanäle auf 0 gesetzt). Sie entspricht der Standard‑ oder Transparentfarbe und stimmt mit [`Argb32Color.is_default`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) überein. |
| [is_fully_opaque](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_opaque/) | Die Eigenschaft gibt an, ob diese [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) Instanz vollständig undurchsichtig ist, ohne Transparenz (ihr Alpha‑Kanal hat den Maximalwert). |
| [is_fully_transparent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_transparent/) | Die Eigenschaft gibt an, ob diese [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) Instanz vollständig transparent ist – ihr Alpha‑Kanal hat den Minimalwert (0), sodass die R‑, G‑ und B‑Kanäle keine sichtbare Wirkung haben. |
| [is_translucent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_translucent/) | Die Eigenschaft gibt an, ob diese [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) Instanz transluzent ist (weder vollständig transparent noch vollständig undurchsichtig). |
| [r](/viewer/python-net/groupdocs.viewer.drawing/argb32color/r/) | Die Rot‑Komponente der Farbe als 8‑Bit‑vorzeichenlose Ganzzahl (0..255). |
| [value](/viewer/python-net/groupdocs.viewer.drawing/argb32color/value/) | Die 32‑Bit‑vorzeichenbehaftete Ganzzahldarstellung der Farbe. |

### Felder
| Feld | Beschreibung |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.drawing/argb32color/empty/) | Gibt eine leere Farbe zurück, die keine Kanalinformationen enthält und vollständig transparent ist. Entspricht ''. Standardwert. |
| [TRANSPARENT](/viewer/python-net/groupdocs.viewer.drawing/argb32color/transparent/) | Vollständig transparente leere Farbe. Gleichwertig zum Standardwert ''. |

### Beispiel

```python
from groupdocs.viewer.drawing import Argb32Color

# Erstelle eine vollständig undurchsichtige gelbe Farbe (RGB 255, 255, 0)
yellow = Argb32Color.from_rgb(255, 255, 0)
```

### Siehe auch
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
