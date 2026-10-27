---
title: "IFontInfo klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt een gemeenschappelijke interface voor alle lettertypen voor die kunnen worden geëxtraheerd uit alle ondersteunde families van documentformaten: PDF, WordProcessing, Spreadsheet en Presentation."
type: docs
url: /nl/python-net/groupdocs.viewer.fonts/ifontinfo/
is_root: false
weight: 50
---


## IFontInfo class

Stelt een gemeenschappelijke interface voor alle lettertypen voor die kunnen worden geëxtraheerd uit alle ondersteunde families van documentformaten: PDF, WordProcessing, Spreadsheet en Presentation.

Het type IFontInfo geeft de volgende leden weer:

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css/#output) | Serialiseert deze lettertype‑info als een @font-face‑at‑rule en schrijft deze naar de opgegeven tekstschrijver. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css_text_writer/) |  |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/content/) | De binaire inhoud van het lettertype als een byte‑array, indien beschikbaar, of None indien niet. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/family_name/) | De familienaam van het lettertype als een string. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/format/) | Het formaat van dit lettertype als een enum — TrueType, TrueType Collection, OpenType, Embedded OpenType, of `FontFormat.unknown`. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/style/) | De stijl van het lettertype als een enum (Regular, Bold, Italic, of Bold Italic); sommige documentformaten ondersteunen mogelijk alleen [`FontStyles.regular`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/). |

### Zie ook
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
