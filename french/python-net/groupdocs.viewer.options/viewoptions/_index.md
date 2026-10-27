---
title: "Classe ViewOptions"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Les options de rendu."
type: docs
url: /fr/python-net/groupdocs.viewer.options/viewoptions/
is_root: false
weight: 340
---


## ViewOptions class

Les options de rendu.

Le type ViewOptions expose les membres suivants :

### Méthodes
| Méthode | Description |
| :- | :- |
| [rotate_page](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page/#page_number-rotation) | Applique la rotation horaire à une page. |
| [rotate_page_int32](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page_int32/) |  |

### Propriétés
| Propriété | Description |
| :- | :- |
| [page_rotations](/viewer/python-net/groupdocs.viewer.options/viewoptions/page_rotations/) | La rotation de la page. |
| [watermark](/viewer/python-net/groupdocs.viewer.options/viewoptions/watermark/) | Le filigrane texte à appliquer à chaque page. |
| [archive_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/archive_options/) | Les options de vue des fichiers d'archive. (héritées de [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [cad_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/cad_options/) | Les options de vue du dessin CAO. (hérité de [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [default_font_name](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/default_font_name/) | La police par défaut pour un document utilisée lors du rendu lorsqu'une police requise est manquante. (hérité de [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [email_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/email_options/) | Les options de vue des messages électroniques. (hérité de [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [mail_storage_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/mail_storage_options/) | Les options de vue des fichiers de données de stockage de courrier. (hérité de [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [outlook_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/outlook_options/) | Les options de vue des fichiers de données Microsoft Outlook. (hérité de [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [pdf_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/pdf_options/) | Les options de vue du document PDF. (hérité de [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [presentation_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/presentation_options/) | Les options de vue des fichiers de présentation. (hérité de [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [project_management_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/project_management_options/) | Les options de vue des fichiers de gestion de projet. (hérité de [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [remove_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/) | La propriété désactive le rendu des commentaires lorsqu'elle est définie sur True. Par défaut, elle est False, donc tous les commentaires sont affichés. (hérité de [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_comments/) | La propriété active ou désactive le rendu des commentaires. (hérité de [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_hidden_pages](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_hidden_pages/) | La propriété active le rendu des pages cachées. (hérité de [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_notes](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/) | La propriété active le rendu des notes et annotations pour certains formats. (hérité de [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [spreadsheet_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/spreadsheet_options/) | Les options de vue des fichiers de feuille de calcul. (hérité de [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [text_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/text_options/) | Les options de texte pour le rendu des fichiers texte. (hérité de [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [visio_rendering_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/visio_rendering_options/) | Les options de vue des fichiers Visio. (hérité de [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [web_document_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/web_document_options/) | Les options de vue des fichiers Web. (hérité de [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [word_processing_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/word_processing_options/) | Les options de vue des fichiers de traitement de texte. (hérité de [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("sample.pptx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.render_notes = True
    viewer.view(view_options)
```

### Voir aussi
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
