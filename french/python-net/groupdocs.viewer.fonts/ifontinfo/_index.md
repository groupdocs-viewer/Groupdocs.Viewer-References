---
title: "Classe IFontInfo"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente une interface commune pour toutes les polices qui peuvent être extraites de toutes les familles de formats de documents prises en charge : PDF, WordProcessing, Spreadsheet et Presentation."
type: docs
url: /fr/python-net/groupdocs.viewer.fonts/ifontinfo/
is_root: false
weight: 50
---


## IFontInfo class

Représente une interface commune pour toutes les polices qui peuvent être extraites de toutes les familles de formats de documents prises en charge : PDF, WordProcessing, Spreadsheet et Presentation.

Le type IFontInfo expose les membres suivants :

### Méthodes
| Méthode | Description |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css/#output) | Sérialise ces informations de police en tant que règle @font-face et les écrit dans le rédacteur de texte spécifié. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css_text_writer/) |  |

### Propriétés
| Propriété | Description |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/content/) | Le contenu binaire de la police sous forme de tableau d'octets, s'il est disponible, ou None sinon. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/family_name/) | Le nom de famille de la police sous forme de chaîne. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/format/) | Le format de cette police sous forme d'énumération — TrueType, TrueType Collection, OpenType, Embedded OpenType, ou `FontFormat.unknown`. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/style/) | Le style de la police sous forme d'énumération (Regular, Bold, Italic ou Bold Italic) ; certains formats de document peuvent ne prendre en charge que [`FontStyles.regular`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/). |

### Voir aussi
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
