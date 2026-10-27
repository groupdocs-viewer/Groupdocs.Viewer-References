---
title: "groupdocs.viewer.fonts"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Konfiguration für das Laden und Ersetzen von Schriftarten."
type: docs
url: /de/python-net/groupdocs.viewer.fonts/
is_root: false
weight: 40
---


Konfiguration für das Laden und Ersetzen von Schriftarten.

### Klassen
| Klasse | Beschreibung |
| :- | :- |
| [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) | Stellt den Ordner dar, der TrueType-Schriftarten enthält. |
| [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/) | Stellt Methoden bereit, um mit Quellen nach TrueType-Schriftarten zu suchen. |
| [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) | Stellt 4 mögliche Schriftstile der Schrift dar, die im Dokument verwendet werden: Regular, Bold, Italic oder Bold Italic. |
| [`IFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/) | Stellt eine gemeinsame Schnittstelle für alle Schriften dar, die aus allen unterstützten Familien von Dokumentformaten extrahiert werden können: PDF, WordProcessing, Spreadsheet und Presentation. |
| [`PdfFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/) | Kapselt Metadaten und Binärdaten einer PDF‑Schrift, die in eine [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)‑Instanz geladen wurde und die im Dokument eingebettet oder im Betriebssystem installiert sein kann, in dem GroupDocs.Viewer ausgeführt wird. |
| [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/) | Stellt Metainformationen und Binärdaten einer Schrift aus einem Presentation‑Dokument dar, das in eine [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)‑Instanz geladen wurde. Die Schrift wird im Dokumentinhalt verwendet und kann im Dokument eingebettet oder im Betriebssystem installiert sein, in dem der Viewer ausgeführt wird. |
| [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/) | Kapselt Metainformationen und Binärdaten einer Schrift aus einem Tabellenkalkulations‑Dokument, das in eine [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)‑Instanz geladen wurde. Tabellenkalkulations‑Dokumente können keine eingebetteten Schriften enthalten, daher wird eine von [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) zurückgegebene Schrift im Betriebssystem installiert, in dem der Viewer ausgeführt wird. |
| [`WordProcessingFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/) | Kapselt Metainformationen und Binärdaten einer Schrift aus einem WordProcessing‑Dokument, das in eine [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)‑Instanz geladen wurde. |
| [`WordProcessingSubstitutedFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/) | Kapselt Metainformationen und Binärdaten einer einzelnen Schrift aus einem WordProcessing‑Dokument, die im geladenen [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)‑Instanz‑Dokument ursprünglich nicht verwendet wird, aber als Ersatzschrift für solche dient, die auf dem Zielrechner nicht gefunden werden können. Ersetzte Schriften existieren nur für die WordProcessing‑Formatfamilie. |

### Aufzählungen
| Enum | Beschreibung |
| :- | :- |
| [`FontFormat`](/viewer/python-net/groupdocs.viewer.fonts/fontformat/) |  |
| [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) | Stellt eine Marker‑Schnittstelle für Schriftquellen dar. |
| [`SearchOption`](/viewer/python-net/groupdocs.viewer.fonts/searchoption/) |  |
