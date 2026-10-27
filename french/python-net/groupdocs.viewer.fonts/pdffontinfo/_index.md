---
title: "Classe PdfFontInfo"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Encapsule les métadonnées et les données binaires d’une police PDF chargée dans une instance de Viewer, qui peut être intégrée au document ou installée sur le système d'exploitation où s’exécute GroupDocs.Viewer."
type: docs
url: /fr/python-net/groupdocs.viewer.fonts/pdffontinfo/
is_root: false
weight: 70
---


## PdfFontInfo class

Encapsule les métadonnées et les données binaires d’une police PDF chargée dans une instance de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/), qui peut être intégrée au document ou installée sur le système d’exploitation où s’exécute GroupDocs.Viewer.

Le type PdfFontInfo expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/__init__/) |  |

### Méthodes
| Méthode | Description |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css/#output) | Sérialise ces informations de police en tant que règle @font-face et les écrit dans le rédacteur de texte spécifié. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css_text_writer/) |  |

### Propriétés
| Propriété | Description |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/content/) | Le contenu de cette police sous forme de tableau d'octets, ou None si seules les métadonnées sont disponibles et que le contenu binaire est indisponible. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/family_name/) | Le nom de famille de la police, sans style ; jamais None ou chaîne vide. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/format/) | Le format de cette police. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_embedded/) | La propriété indique si la police est intégrée dans le document PDF et chargée dans l’instance Viewer (`True`), ou non. |
| [is_installed](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_installed/) | La propriété indique si cette police est présente (installée) dans le système d'exploitation où s’exécute GroupDocs.Viewer. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/style/) | Le style de la police ; peut être Regular, Bold, Italic ou Bold Italic. |

### Voir aussi
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
