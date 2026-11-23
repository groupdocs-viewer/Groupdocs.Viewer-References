---
title: "PresentationFontInfo Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt Metainformationen und Binärdaten einer Schrift aus einem Präsentationsdokument dar, das in einer Viewer-Instanz geladen wurde."
type: docs
url: /de/python-net/groupdocs.viewer.fonts/presentationfontinfo/
is_root: false
weight: 80
---


## PresentationFontInfo class

Stellt Metainformationen und Binärdaten einer Schrift aus einem Presentation‑Dokument dar, das in eine [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)‑Instanz geladen wurde. Die Schrift wird im Dokumentinhalt verwendet und kann im Dokument eingebettet oder im Betriebssystem installiert sein, in dem der Viewer ausgeführt wird.

Der PresentationFontInfo-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/__init__/) |  |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css/#output) | Serialisiert diese Schriftinformationen als @font-face‑At‑Rule und schreibt sie in den angegebenen Textwriter. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css_text_writer/) |  |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/content/) | Der Inhalt dieser Schrift als Byte-Array. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/family_name/) | Der Familienname der Schriftart, ohne Stil; niemals None oder leere Zeichenkette. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/format/) | Das Format dieser Schriftart. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/) | Die Eigenschaft gibt an, ob die Schrift im Dokument eingebettet und in die [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) Instanz (`True`) geladen ist, oder ob es sich um eine Systemschrift handelt (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/style/) | Der Stil der Schrift — kann Regular, Bold, Italic oder Bold Italic sein. |

### Siehe auch
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
