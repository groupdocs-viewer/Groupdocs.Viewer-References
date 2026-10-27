---
title: "SpreadsheetFontInfo Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Kapselt Metainformationen und Binärdaten einer Schrift aus einem Tabellenkalkulationsdokument, das in einer Viewer-Instanz geladen wurde."
type: docs
url: /de/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/
is_root: false
weight: 100
---


## SpreadsheetFontInfo class

Kapselt Metainformationen und Binärdaten einer Schrift aus einem Tabellenkalkulations‑Dokument, das in eine [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)‑Instanz geladen wurde. Tabellenkalkulations‑Dokumente können keine eingebetteten Schriften enthalten, daher wird eine von [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) zurückgegebene Schrift im Betriebssystem installiert, in dem der Viewer ausgeführt wird.

Der SpreadsheetFontInfo-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/__init__/) |  |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/#output) | Serialisiert die Schriftinformationen als @font-face‑At‑Rule und schreibt sie in den angegebenen Textwriter. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css_text_writer/) |  |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/charset/) | Der Zeichensatz dieser Schriftart. |
| [color](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/color/) | Die Farbe dieser Schrift. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/content/) | Der Inhalt dieser Schrift als Byte-Array. Wenn nur Metainformationen über diese Schrift verfügbar sind und ihr Binärinhalt nicht verfügbar ist, gibt die Eigenschaft None zurück. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/family_name/) | Der Familienname der Schrift, ohne Stil, ist niemals null oder ein leerer String. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/format/) | Das Format dieser Schriftart. |
| [is_strikeout](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_strikeout/) | Die Schrift hat einen einzelnen Durchstrich. |
| [is_underline](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_underline/) | Die Schrift hat eine Unterstreichung. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/style/) | Der Stil dieser Schrift — kann Regular, Bold, Italic oder Bold Italic sein. |

### Siehe auch
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
