---
title: "Classe WordProcessingFontInfo"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Encapsule les métadonnées et les données binaires d'une police provenant d'un document WordProcessing chargé dans une instance de Viewer."
type: docs
url: /fr/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/
is_root: false
weight: 110
---


## WordProcessingFontInfo class

Encapsule les métadonnées et les données binaires d’une police provenant d’un document WordProcessing chargé dans une instance de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Structure immuable.

Ses instances sont produites et renvoyées par l'API publique [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) et ne devraient normalement pas être créées par l'utilisateur.

Pour plus de détails, consultez la documentation : https://docs.groupdocs.com/viewer/net/getting-used-fonts/

Le type WordProcessingFontInfo expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/__init__/) |  |

### Méthodes
| Méthode | Description |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css/#output) | Sérialise les informations de police en tant que règle @font-face et les écrit dans le rédacteur de texte spécifié. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/to_string/) | Renvoie une information de débogage sur ces données de police selon le modèle suivant : "nom style, intégré/système, format". |

### Propriétés
| Propriété | Description |
| :- | :- |
| [alt_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/alt_family_name/) | Le nom de famille alternatif de la police. S'il est absent, la chaîne est vide. |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/charset/) | Le jeu de caractères de cette police. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/content/) | Le contenu de cette police sous forme de tableau d'octets. Si seules les métadonnées de cette police sont disponibles et que le contenu binaire est indisponible, la propriété renvoie None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/family_name/) | Le nom de famille de la police, sans style ; jamais None ou chaîne vide. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/format/) | Le format de cette police. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/is_embedded/) | La propriété indique si cette police est intégrée dans le document, chargée dans l'instance [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) (`True`), ou s'il s'agit d'une police système (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/style/) | Le style de la police — peut être Regular, Bold, Italic ou Bold Italic. |

### Voir aussi
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
