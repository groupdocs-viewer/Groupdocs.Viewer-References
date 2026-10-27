---
title: "SpreadsheetFontInfo‑klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Omvat metagegevens en binaire gegevens van een lettertype uit een spreadsheet‑document dat is geladen in een Viewer‑instantie."
type: docs
url: /nl/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/
is_root: false
weight: 100
---


## SpreadsheetFontInfo class

Omvat metagegevens en binaire gegevens van een lettertype uit een spreadsheet-document geladen in een [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instantie. Spreadsheet-documenten kunnen geen ingebedde lettertypen hebben, dus een lettertype dat wordt geretourneerd door [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) wordt geïnstalleerd op het besturingssysteem waarop de viewer draait.

Het type SpreadsheetFontInfo exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/__init__/) |  |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/#output) | Serialiseert de lettertype‑info als een @font-face‑at‑rule en schrijft deze naar de opgegeven tekstschrijver. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css_text_writer/) |  |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/charset/) | De tekenset van dit lettertype. |
| [color](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/color/) | De kleur van dit lettertype. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/content/) | De inhoud van dit lettertype als een byte‑array. Als alleen metagegevens over dit lettertype beschikbaar zijn en de binaire inhoud niet beschikbaar is, retourneert de eigenschap None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/family_name/) | De familienaam van het lettertype, zonder stijl, is nooit null of een lege tekenreeks. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/format/) | Het formaat van dit lettertype. |
| [is_strikeout](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_strikeout/) | Het lettertype heeft één doorhaling. |
| [is_underline](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_underline/) | Het lettertype heeft een onderstreping. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/style/) | De stijl van dit lettertype — kan Regular, Bold, Italic of Bold Italic zijn. |

### Zie ook
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
