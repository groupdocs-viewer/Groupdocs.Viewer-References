---
title: "Classe PresentationFontInfo"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente les métadonnées et les données binaires d'une police provenant d'un document Presentation chargé dans une instance de Viewer."
type: docs
url: /fr/python-net/groupdocs.viewer.fonts/presentationfontinfo/
is_root: false
weight: 80
---


## PresentationFontInfo class

Représente les métadonnées et les données binaires d’une police provenant d’un document Presentation chargé dans une instance de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). La police est utilisée dans le contenu du document et peut être intégrée au document ou installée sur le système d’exploitation où le visualiseur s’exécute.

Le type PresentationFontInfo expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/__init__/) |  |

### Méthodes
| Méthode | Description |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css/#output) | Sérialise ces informations de police en tant que règle @font-face et les écrit dans le rédacteur de texte spécifié. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css_text_writer/) |  |

### Propriétés
| Propriété | Description |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/content/) | Le contenu de cette police sous forme de tableau d'octets. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/family_name/) | Le nom de famille de la police, sans style ; jamais None ou chaîne vide. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/format/) | Le format de cette police. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/) | La propriété indique si la police est incorporée dans le document et chargée dans l'instance [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) (`True`), ou s'il s'agit d'une police système (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/style/) | Le style de la police — peut être Regular, Bold, Italic ou Bold Italic. |

### Voir aussi
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
