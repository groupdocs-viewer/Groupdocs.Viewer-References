---
title: "Rgb24Color-Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt 24-Bit-RGB-Farbe mit 8 Bit pro Kanal (Rot, Grün, Blau) ohne Transparenz dar."
type: docs
url: /de/python-net/groupdocs.viewer.drawing/rgb24color/
is_root: false
weight: 80
---


## Rgb24Color class

Stellt 24-Bit-RGB-Farbe mit 8 Bit pro Kanal (Rot, Grün, Blau) ohne Transparenz dar.

Dieser Typ ist für (aber nicht ausschließlich) CSS‑Operationen gedacht. Weitere Informationen: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Der Rgb24Color-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/__init__/) |  |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Bestimmt, ob diese Farbe gleich der angegebenen [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) ist. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Überprüft diese Farbe mit der angegebenen [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) Farbe auf Gleichheit. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#obj) | Überprüft diese Farbe gegen die angegebene nicht gecastete Farbe. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/from_rgb/#red-green-blue) | Erstellt einen [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) Wert aus den angegebenen Rot-, Grün- und Blaukanalwerten. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_brightness/) | Gibt die Helligkeit (Lightness) des Hue‑Saturation‑Lightness (HSL)-Modells für diese [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) Instanz zurück. |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hash_code/) | Gibt einen Hashcode zurück, der die aktuelle Farbe definiert. Nicht kompatibel mit `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hue/) | Gibt die Farbtonkomponente der Farbe im HSL-Farbraum zurück, ausgedrückt in Grad. Ist die Farbe ein Graustufenwert (R == G == B), ist der Farbton undefiniert und die Methode gibt 0 zurück. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_saturation/) | Die Hue‑Saturation‑Lightness (HSL)-Sättigung für diese [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) Instanz. |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_argb/) | Gibt den ARGB-Wert dieser [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) Instanz zurück, kompatibel mit `System.Drawing.Color`. |
| [to_hex](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/) | Gibt diese Farbe in hexadezimaler String-Darstellung zurück. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_rgb/) | Serialisiert diese [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) Instanz in die 'rgb'-CSS-Funktionsnotation. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_string/) | Serialisiert diese [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) Instanz in das Format 'rgb(r, g, b)'. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [b](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/b/) | Die blaue Komponente der Farbe als 8‑Bit‑vorzeichenlose Ganzzahl [0..255]. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/g/) | Die Grün‑Komponente der Farbe als 8‑Bit‑vorzeichenlose Ganzzahl im Bereich 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/is_default/) | Die Eigenschaft gibt an, ob diese [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) Instanz der Standardwert (Schwarz) ist – alle drei Kanäle sind auf 0 gesetzt. |
| [r](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/r/) | Die Rot‑Komponente der Farbe als 8‑Bit‑vorzeichenlose Ganzzahl (0..255). |

### Siehe auch
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
