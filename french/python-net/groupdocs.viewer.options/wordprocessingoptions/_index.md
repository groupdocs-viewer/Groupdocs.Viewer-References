---
title: "Classe WordProcessingOptions"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Contient les options de rendu des documents Word."
type: docs
url: /fr/python-net/groupdocs.viewer.options/wordprocessingoptions/
is_root: false
weight: 380
---


## WordProcessingOptions class

Contient les options de rendu des documents Word.

Pour plus de détails, consultez la documentation à l'adresse https://docs.groupdocs.com/viewer/net/render-word-documents/.

Le type WordProcessingOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/) | Initialise les options pour le rendu des documents de traitement de texte. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [clone](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/clone/) | Crée et renvoie une copie profonde complète de ces options. |
| [equals](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals/#options) | Détermine si l'instance spécifiée [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/) est égale à cette instance. |
| [equals_word_processing_options](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals_word_processing_options/) |  |

### Propriétés
| Propriété | Description |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/bottom_margin/) | La marge inférieure d'une page. |
| [enable_open_type_features](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/enable_open_type_features/) | L'option active le crénage et d'autres fonctionnalités OpenType lors du rendu des scripts arabes, hébreux, indiens basés sur le latin ou cyrilliques. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/) | La résolution horizontale des images générées en points par pouce. Cette option est utilisée uniquement lors du rendu des documents WordProcessing au format PNG ou JPEG. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/left_margin/) | La marge gauche d'une page. |
| [page_number_location](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_number_location/) | L'emplacement de la numérotation des pages pour le document WordProcessing chargé, qui peut appliquer la numérotation de manière forcée ; par défaut, il est `WordsPageNumberLocation.not_apply`, laissant le document intact. |
| [page_size](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/) | La taille de la page de sortie. |
| [render_tracked_changes](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/render_tracked_changes/) | La propriété active le rendu des modifications suivies (révisions). |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/right_margin/) | La marge droite d'une page. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/top_margin/) | La marge supérieure d'une page en points. |
| [unlink_table_of_contents](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/unlink_table_of_contents/) | L'option désactive la navigation depuis la table des matières lorsqu'elle est définie sur True pour le rendu HTML ou PDF. |
| [update_fields](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/update_fields/) | La propriété détermine si les champs de certains types sont mis à jour avant d'enregistrer le document WordProcessing aux formats HTML, PDF, PNG ou JPEG. La valeur par défaut est True, ce qui signifie que les champs sont mis à jour. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/) | La résolution verticale des images générées en points par pouce, utilisée uniquement lors du rendu des documents WordProcessing aux formats PNG ou JPEG. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("with_tracked_changes.docx") as viewer:
    view_options = PdfViewOptions("output/word_with_tracked_changes.pdf")
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### Voir aussi
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
