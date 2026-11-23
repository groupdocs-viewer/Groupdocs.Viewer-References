---
title: "Classe IFontInfo"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta un'interfaccia comune per tutti i caratteri che possono essere estratti da tutte le famiglie supportate di formati di documento: PDF, WordProcessing, Spreadsheet e Presentation."
type: docs
url: /it/python-net/groupdocs.viewer.fonts/ifontinfo/
is_root: false
weight: 50
---


## IFontInfo class

Rappresenta un'interfaccia comune per tutti i caratteri che possono essere estratti da tutte le famiglie supportate di formati di documento: PDF, WordProcessing, Spreadsheet e Presentation.

Il tipo IFontInfo espone i seguenti membri:

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css/#output) | Serializza queste informazioni sul carattere come una regola @font-face e le scrive nel writer di testo specificato. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css_text_writer/) |  |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/content/) | Il contenuto binario del carattere come array di byte, se disponibile, o None se non lo è. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/family_name/) | Il nome della famiglia del carattere come stringa. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/format/) | Il formato di questo carattere come enum — TrueType, TrueType Collection, OpenType, Embedded OpenType, o `FontFormat.unknown`. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/style/) | Lo stile del carattere come enum (Regular, Bold, Italic o Bold Italic); alcuni formati di documento possono supportare solo [`FontStyles.regular`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/). |

### Vedi anche
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
