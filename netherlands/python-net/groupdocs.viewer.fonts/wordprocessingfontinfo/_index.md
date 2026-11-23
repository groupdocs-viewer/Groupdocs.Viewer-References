---
title: "WordProcessingFontInfo klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Omsluit metagegevens en binaire gegevens van een lettertype uit een WordProcessing-document dat is geladen in een Viewer‑instantie."
type: docs
url: /nl/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/
is_root: false
weight: 110
---


## WordProcessingFontInfo class

Omvat metagegevens en binaire gegevens van een lettertype uit een WordProcessing-document geladen in een [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) instantie.

Onveranderlijke struct.

Zijn instanties worden geproduceerd en geretourneerd door de openbare API van [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) en zouden normaal niet door de gebruiker aangemaakt moeten worden.

Voor details, zie de documentatie: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

Het type WordProcessingFontInfo exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/__init__/) |  |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css/#output) | Serialiseert de lettertype‑info als een @font-face‑at‑rule en schrijft deze naar de opgegeven tekstschrijver. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/to_string/) | Retourneert een debug‑informatie over deze lettertype‑gegevens volgens het volgende sjabloon: "naam stijl, ingebed/systeem, formaat". |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [alt_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/alt_family_name/) | De alternatieve familienaam van het lettertype. Indien afwezig, dan een lege string. |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/charset/) | De tekenset van dit lettertype. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/content/) | De inhoud van dit lettertype als een byte‑array. Als alleen metagegevens over dit lettertype beschikbaar zijn en de binaire inhoud niet beschikbaar is, retourneert de eigenschap None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/family_name/) | De familienaam van het lettertype, zonder stijl; nooit None of een lege string. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/format/) | Het formaat van dit lettertype. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/is_embedded/) | De eigenschap geeft aan of dit lettertype is ingebed in het document, geladen in de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)‑instantie (`True`), of een systeemlettertype is (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/style/) | De stijl van het lettertype — kan Regular, Bold, Italic of Bold Italic zijn. |

### Zie ook
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
