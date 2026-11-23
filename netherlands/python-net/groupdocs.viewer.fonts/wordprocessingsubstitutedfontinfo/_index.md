---
title: "WordProcessingSubstitutedFontInfo class"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Omvat metagegevens en binaire gegevens van één lettertype uit een WordProcessing‑document, dat oorspronkelijk niet wordt gebruikt in het geladen Viewer‑instance‑document, maar dient als vervangend lettertype voor die…"
type: docs
url: /nl/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
is_root: false
weight: 120
---


## WordProcessingSubstitutedFontInfo class

Omvat metagegevens en binaire gegevens van één lettertype uit een WordProcessing-document, dat oorspronkelijk niet wordt gebruikt in het geladen [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instantiedocument, maar dient als vervangend lettertype voor diegenen die niet op de doelmachine kunnen worden gevonden. Vervangende lettertypen bestaan alleen voor de WordProcessing-formaatfamilie.

Immutable struct. Zijn instanties worden geproduceerd en geretourneerd door de openbare API van [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) en zouden normaal niet door de gebruiker moeten worden aangemaakt. Zie voor details de documentatie: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

Het WordProcessingSubstitutedFontInfo‑type exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/__init__/) |  |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css/#output) | Serialiseert de lettertype‑info als een @font-face‑at‑rule en schrijft deze naar de opgegeven tekstschrijver. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/to_string/) | Retourneert een debug‑string met lettertype‑informatie in het formaat "original-name -> substituted-name style, format". |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content/) | De inhoud van het vervangende lettertype als een byte‑array. Het is nooit None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/family_name/) | De familienaam van het vervangende lettertype, zonder stijl. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format/) | Het formaat van dit vervangende (niet‑originele) lettertype. |
| [original_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/original_family_name/) | De familienaam van het originele lettertype, dat niet kan worden gevonden op een doelmachine, zonder stijl. Nooit null of een lege string. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style/) | De stijl van het originele lettertype — kan Regular, Bold, Italic of Bold Italic zijn. |

### Zie ook
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
