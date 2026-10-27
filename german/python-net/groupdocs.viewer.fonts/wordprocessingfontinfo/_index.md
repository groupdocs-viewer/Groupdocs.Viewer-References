---
title: "WordProcessingFontInfo Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Kapselt Metainformationen und Binärdaten einer Schriftart aus einem WordProcessing-Dokument, das in einer Viewer-Instanz geladen wurde."
type: docs
url: /de/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/
is_root: false
weight: 110
---


## WordProcessingFontInfo class

Kapselt Metainformationen und Binärdaten einer Schrift aus einem WordProcessing‑Dokument, das in eine [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)‑Instanz geladen wurde.

Unveränderliche Struktur.

Seine Instanzen werden von der öffentlichen API des [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) erzeugt und zurückgegeben und sollten normalerweise nicht vom Benutzer erstellt werden.

Weitere Details finden Sie in der Dokumentation: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

Der Typ WordProcessingFontInfo stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/__init__/) |  |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css/#output) | Serialisiert die Schriftinformationen als @font-face‑At‑Rule und schreibt sie in den angegebenen Textwriter. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/to_string/) | Gibt Debug-Informationen zu diesen Schriftartdaten im folgenden Format zurück: "name style, embedded/system, format". |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [alt_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/alt_family_name/) | Der alternative Familienname der Schriftart. Falls nicht vorhanden, ein leerer String. |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/charset/) | Der Zeichensatz dieser Schriftart. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/content/) | Der Inhalt dieser Schriftart als Byte-Array. Wenn nur Metainformationen über diese Schriftart verfügbar sind und der Binärinhalt nicht verfügbar ist, gibt die Eigenschaft None zurück. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/family_name/) | Der Familienname der Schriftart, ohne Stil; niemals None oder leere Zeichenkette. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/format/) | Das Format dieser Schriftart. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/is_embedded/) | Die Eigenschaft gibt an, ob diese Schriftart im Dokument eingebettet ist, in die [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) Instanz geladen wurde (`True`), oder ob es sich um eine Systemschriftart handelt (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/style/) | Der Stil der Schrift — kann Regular, Bold, Italic oder Bold Italic sein. |

### Siehe auch
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
