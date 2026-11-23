---
title: "PdfFontInfo-Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Kapselt Metadaten und Binärdaten einer PDF‑Schriftart, die in eine Viewer‑Instanz geladen wurde und entweder im Dokument eingebettet oder im Betriebssystem, in dem GroupDocs.Viewer läuft, installiert sein kann."
type: docs
url: /de/python-net/groupdocs.viewer.fonts/pdffontinfo/
is_root: false
weight: 70
---


## PdfFontInfo class

Kapselt Metadaten und Binärdaten einer PDF‑Schrift, die in eine [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)‑Instanz geladen wurde und die im Dokument eingebettet oder im Betriebssystem installiert sein kann, in dem GroupDocs.Viewer ausgeführt wird.

Der PdfFontInfo-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/__init__/) |  |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css/#output) | Serialisiert diese Schriftinformationen als @font-face‑At‑Rule und schreibt sie in den angegebenen Textwriter. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css_text_writer/) |  |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/content/) | Der Inhalt dieser Schriftart als Byte‑Array, oder None, falls nur Metadaten verfügbar sind und der binäre Inhalt nicht verfügbar ist. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/family_name/) | Der Familienname der Schriftart, ohne Stil; niemals None oder leere Zeichenkette. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/format/) | Das Format dieser Schriftart. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_embedded/) | Die Eigenschaft gibt an, ob die Schriftart im PDF‑Dokument eingebettet und in die Viewer‑Instanz geladen ist (`True`), oder nicht. |
| [is_installed](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_installed/) | Die Eigenschaft gibt an, ob diese Schriftart im Betriebssystem, in dem GroupDocs.Viewer läuft, vorhanden (installiert) ist. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/style/) | Der Stil der Schriftart; kann Regular, Bold, Italic oder Bold Italic sein. |

### Siehe auch
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
