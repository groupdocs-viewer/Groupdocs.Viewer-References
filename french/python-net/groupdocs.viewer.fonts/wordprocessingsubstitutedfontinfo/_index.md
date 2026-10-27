---
title: "Classe WordProcessingSubstitutedFontInfo"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Encapsule les métadonnées et les données binaires d’une police d’un document WordProcessing, qui à l’origine n’est pas utilisée dans le document chargé par l’instance Viewer, mais sert de police de substitution pour celles qui…"
type: docs
url: /fr/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
is_root: false
weight: 120
---


## WordProcessingSubstitutedFontInfo class

Encapsule les métadonnées et les données binaires d’une police provenant d’un document WordProcessing, qui n’est initialement pas utilisée dans le document chargé par l’instance [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/), mais sert de police de substitution pour celles qui ne peuvent pas être trouvées sur la machine cible. Les polices de substitution existent uniquement pour la famille de formats WordProcessing.

Structure immuable. Ses instances sont produites et renvoyées par l’API publique [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) et ne devraient normalement pas être créées par l’utilisateur. Pour plus de détails, consultez la documentation : https://docs.groupdocs.com/viewer/net/getting-used-fonts/

Le type WordProcessingSubstitutedFontInfo expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/__init__/) |  |

### Méthodes
| Méthode | Description |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css/#output) | Sérialise les informations de police en tant que règle @font-face et les écrit dans le rédacteur de texte spécifié. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/to_string/) | Renvoie une chaîne de débogage contenant les informations de police au format "original-name -> substituted-name style, format". |

### Propriétés
| Propriété | Description |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content/) | Le contenu de la police substituée sous forme de tableau d'octets. Il n’est jamais None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/family_name/) | Le nom de famille de la police substituée, sans style. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format/) | Le format de cette police substituée (pas originale). |
| [original_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/original_family_name/) | Le nom de famille de la police originale, qui ne peut pas être trouvée sur la machine cible, sans style. N’est jamais nul ou chaîne vide. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style/) | Le style de la police originale — peut être Regular, Bold, Italic ou Bold Italic. |

### Voir aussi
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
