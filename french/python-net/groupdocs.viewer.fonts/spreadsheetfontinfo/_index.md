---
title: "Classe SpreadsheetFontInfo"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Encapsule les métadonnées et les données binaires d'une police provenant d'un document feuille de calcul chargé dans une instance de Viewer."
type: docs
url: /fr/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/
is_root: false
weight: 100
---


## SpreadsheetFontInfo class

Encapsule les métadonnées et les données binaires d’une police provenant d’un document de feuille de calcul chargé dans une instance de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). Les documents de feuille de calcul ne peuvent pas contenir de polices intégrées, ainsi une police renvoyée par [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) est installée sur le système d’exploitation où le visualiseur s’exécute.

Le type SpreadsheetFontInfo expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/__init__/) |  |

### Méthodes
| Méthode | Description |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/#output) | Sérialise les informations de police en tant que règle @font-face et les écrit dans le rédacteur de texte spécifié. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css_text_writer/) |  |

### Propriétés
| Propriété | Description |
| :- | :- |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/charset/) | Le jeu de caractères de cette police. |
| [color](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/color/) | La couleur de cette police. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/content/) | Le contenu de cette police sous forme de tableau d'octets. Si seules les métadonnées de cette police sont disponibles et que son contenu binaire est indisponible, la propriété renvoie None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/family_name/) | Le nom de famille de la police, sans style, n'est jamais nul ni une chaîne vide. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/format/) | Le format de cette police. |
| [is_strikeout](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_strikeout/) | La police possède un seul texte barré. |
| [is_underline](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_underline/) | La police possède un soulignement. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/style/) | Le style de cette police — peut être Regular, Bold, Italic ou Bold Italic. |

### Voir aussi
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
