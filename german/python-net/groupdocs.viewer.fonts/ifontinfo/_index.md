---
title: "IFontInfo-Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt eine gemeinsame Schnittstelle für alle Schriften dar, die aus allen unterstützten Familien von Dokumentformaten extrahiert werden können: PDF, WordProcessing, Spreadsheet und Presentation."
type: docs
url: /de/python-net/groupdocs.viewer.fonts/ifontinfo/
is_root: false
weight: 50
---


## IFontInfo class

Stellt eine gemeinsame Schnittstelle für alle Schriften dar, die aus allen unterstützten Familien von Dokumentformaten extrahiert werden können: PDF, WordProcessing, Spreadsheet und Presentation.

Der IFontInfo-Typ stellt die folgenden Mitglieder bereit:

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css/#output) | Serialisiert diese Schriftinformationen als @font-face‑At‑Rule und schreibt sie in den angegebenen Textwriter. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css_text_writer/) |  |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/content/) | Der binäre Inhalt der Schriftart als Byte‑Array, falls verfügbar, oder None, falls nicht. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/family_name/) | Der Familienname der Schriftart als Zeichenkette. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/format/) | Das Format dieser Schriftart als Aufzählung — TrueType, TrueType Collection, OpenType, Embedded OpenType oder `FontFormat.unknown`. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/style/) | Der Stil der Schriftart als Aufzählung (Regular, Bold, Italic oder Bold Italic); einige Dokumentformate unterstützen möglicherweise nur [`FontStyles.regular`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/). |

### Siehe auch
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
