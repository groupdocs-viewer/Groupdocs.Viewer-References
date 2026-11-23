---
title: "SpreadsheetOptions classe"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Les options pour le rendu des feuilles de calcul."
type: docs
url: /fr/python-net/groupdocs.viewer.options/spreadsheetoptions/
is_root: false
weight: 280
---


## SpreadsheetOptions class

Les options pour le rendu des feuilles de calcul.

Pour plus de détails, consultez les sous‑sections du sujet Render spreadsheet files.

Le type SpreadsheetOptions expose les membres suivants :

### Méthodes
| Méthode | Description |
| :- | :- |
| [for_one_page_per_sheet](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/) | Initialise une instance [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) pour rendre la feuille entière sur une seule page. |
| [for_rendering_by_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/) | Initialise une instance [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) configurée pour diviser les feuilles de calcul en pages selon les sauts de page. |
| [for_rendering_print_area](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/) | Initialise une instance de la classe [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) pour rendre uniquement les zones d’impression. |
| [for_rendering_print_area_and_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area_and_page_breaks/) | Initialise une instance de la classe [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) pour rendre les zones d’impression et les sauts de page. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page) | Initialise une instance SpreadsheetOptions pour rendre une feuille en plusieurs pages. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page-count_columns_per_page) | Initialise une instance SpreadsheetOptions pour rendre une feuille en plusieurs pages. |
| [for_split_sheet_into_pages_int32](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages_int32/) |  |

### Propriétés
| Propriété | Description |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/bottom_margin/) | La marge inférieure d’une page lors de la conversion en PDF. |
| [count_columns_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_columns_per_page/) | Le nombre de colonnes à inclure sur chaque page lors du fractionnement de la feuille de calcul en pages. |
| [count_rows_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_rows_per_page/) | Le nombre de lignes à inclure sur chaque page lors du fractionnement de la feuille de calcul en pages. |
| [detect_separator](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/detect_separator/) | La propriété active la détection d’un séparateur pour les fichiers CSV/TSV. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/horizontal_resolution/) | La résolution horizontale des images générées en points par pouce. Cette option n’est utilisée que lors du rendu de feuilles de calcul au format PNG ou JPEG. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/left_margin/) | La marge gauche d’une page lors de la conversion en PDF. |
| [render_grid_lines](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_grid_lines/) | La propriété active le rendu des lignes de grille. |
| [render_headings](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_headings/) | La propriété active le rendu des en-têtes. |
| [render_hidden_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_columns/) | La propriété active le rendu des colonnes masquées. |
| [render_hidden_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_rows/) | La propriété permet le rendu des lignes cachées. |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/right_margin/) | La marge droite d'une page lors de la conversion en PDF. |
| [skip_empty_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_columns/) | La propriété désactive le rendu des colonnes vides. |
| [skip_empty_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_rows/) | La propriété désactive le rendu des lignes vides. |
| [text_overflow_mode](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/text_overflow_mode/) | Le mode de dépassement de texte pour le rendu des documents de feuille de calcul en HTML. La valeur par défaut est `TextOverflowMode.OverlayIfNextIsEmpty`, qui imite le comportement par défaut de MS Excel. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/top_margin/) | La marge supérieure d'une page lors de la conversion en PDF. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/) | La résolution verticale des images générées en points par pouce. Cette option n'est utilisée que lors du rendu des feuilles de calcul aux formats PNG ou JPEG. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Activer le rendu des lignes de grille dans la feuille de calcul.
    view_options.spreadsheet_options.render_grid_lines = True
    viewer.view(view_options)
```

### Voir aussi
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
