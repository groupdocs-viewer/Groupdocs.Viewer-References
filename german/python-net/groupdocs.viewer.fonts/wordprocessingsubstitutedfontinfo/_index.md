---
title: "WordProcessingSubstitutedFontInfo-Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Kapselt Metainformationen und Binärdaten einer Schriftart aus einem WordProcessing‑Dokument, die ursprünglich nicht im geladenen Viewer‑Instanz‑Dokument verwendet wird, sondern als Ersatzschriftart für jene dient, die …"
type: docs
url: /de/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
is_root: false
weight: 120
---


## WordProcessingSubstitutedFontInfo class

Kapselt Metainformationen und Binärdaten einer einzelnen Schrift aus einem WordProcessing‑Dokument, die im geladenen [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)‑Instanz‑Dokument ursprünglich nicht verwendet wird, aber als Ersatzschrift für solche dient, die auf dem Zielrechner nicht gefunden werden können. Ersetzte Schriften existieren nur für die WordProcessing‑Formatfamilie.

Unveränderliche Struktur. Ihre Instanzen werden von der öffentlichen API [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) erzeugt und zurückgegeben und sollten normalerweise nicht vom Benutzer erstellt werden. Weitere Details finden Sie in der Dokumentation: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

Der WordProcessingSubstitutedFontInfo-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/__init__/) |  |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css/#output) | Serialisiert die Schriftinformationen als @font-face‑At‑Rule und schreibt sie in den angegebenen Textwriter. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/to_string/) | Gibt einen Debug‑String zurück, der Schriftinformationen im Format "original-name -> substituted-name style, format" enthält. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content/) | Der Inhalt der ersetzten Schriftart als Byte‑Array. Er ist niemals None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/family_name/) | Der Familienname der ersetzten Schriftart, ohne Stil. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format/) | Das Format dieser ersetzten (nicht originalen) Schriftart. |
| [original_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/original_family_name/) | Der Familienname der Originalschriftart, die auf einem Zielrechner nicht gefunden werden kann, ohne Stil. Ist niemals null oder ein leerer String. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style/) | Der Stil der Originalschriftart — kann Regular, Bold, Italic oder Bold Italic sein. |

### Siehe auch
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
