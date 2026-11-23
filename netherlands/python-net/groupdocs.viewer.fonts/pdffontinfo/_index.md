---
title: "PdfFontInfo class"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Omvat metadata en binaire gegevens van een PDF‑lettertype dat is geladen in een Viewer‑instance, die mogelijk in het document is ingebed of geïnstalleerd op het besturingssysteem waarop GroupDocs.Viewer draait."
type: docs
url: /nl/python-net/groupdocs.viewer.fonts/pdffontinfo/
is_root: false
weight: 70
---


## PdfFontInfo class

Omvat metadata en binaire gegevens van een PDF-lettertype geladen in een [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instantie, die mogelijk in het document is ingebed of geïnstalleerd op het besturingssysteem waarop GroupDocs.Viewer draait.

Het PdfFontInfo‑type exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/__init__/) |  |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css/#output) | Serialiseert deze lettertype‑info als een @font-face‑at‑rule en schrijft deze naar de opgegeven tekstschrijver. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css_text_writer/) |  |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/content/) | De inhoud van dit lettertype als een byte‑array, of None als alleen metadata beschikbaar is en de binaire inhoud niet beschikbaar is. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/family_name/) | De familienaam van het lettertype, zonder stijl; nooit None of een lege string. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/format/) | Het formaat van dit lettertype. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_embedded/) | De eigenschap geeft aan of het lettertype is ingebed in het PDF‑document en geladen in de Viewer‑instance (`True`), of niet. |
| [is_installed](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_installed/) | De eigenschap geeft aan of dit lettertype aanwezig (geïnstalleerd) is op het besturingssysteem waarop GroupDocs.Viewer draait. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/style/) | De stijl van het lettertype; kan Regular, Bold, Italic of Bold Italic zijn. |

### Zie ook
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
