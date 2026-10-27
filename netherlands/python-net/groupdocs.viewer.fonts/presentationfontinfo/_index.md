---
title: "PresentationFontInfo klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt metagegevens en binaire gegevens van een lettertype uit een Presentatiedocument voor dat is geladen in een Viewer‑instantie."
type: docs
url: /nl/python-net/groupdocs.viewer.fonts/presentationfontinfo/
is_root: false
weight: 80
---


## PresentationFontInfo class

Stelt metagegevens en binaire gegevens van een lettertype uit een Presentation-document voor, geladen in een [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instantie. Het lettertype wordt gebruikt in de documentinhoud en kan ingebed zijn in het document of geïnstalleerd op het besturingssysteem waarop de viewer draait.

Het type PresentationFontInfo exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/__init__/) |  |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css/#output) | Serialiseert deze lettertype‑info als een @font-face‑at‑rule en schrijft deze naar de opgegeven tekstschrijver. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css_text_writer/) |  |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/content/) | De inhoud van dit lettertype als een byte‑array. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/family_name/) | De familienaam van het lettertype, zonder stijl; nooit None of een lege string. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/format/) | Het formaat van dit lettertype. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/) | De eigenschap geeft aan of het lettertype is ingebed in het document en is geladen in de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instantie (`True`), of een systeemlettertype is (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/style/) | De stijl van het lettertype — kan Regular, Bold, Italic of Bold Italic zijn. |

### Zie ook
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
