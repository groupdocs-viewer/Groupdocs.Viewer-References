---
title: "Classe Viewer"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente la classe principale qui contrôle le processus de rendu du document."
type: docs
url: /fr/python-net/groupdocs.viewer/viewer/
is_root: false
weight: 100
---


## Viewer class

Représente la classe principale qui contrôle le processus de rendu du document.

Le type Viewer expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream) | Initialise une nouvelle instance de la classe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options) | Initialise une nouvelle instance de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-settings) | Initialise une nouvelle instance de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options-settings) | Initialise une nouvelle instance de Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream) | Initialise une nouvelle instance de la classe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-leave_open) | Initialise une nouvelle instance de Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options) | Initialise une nouvelle instance de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-leave_open) | Initialise une nouvelle instance de Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings) | Initialise une nouvelle instance de Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings-leave_open) | Initialise une nouvelle instance de Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings) | Initialise une nouvelle instance de Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings-leave_open) | Initialise une nouvelle instance de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path) | Initialise une nouvelle instance de la classe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-settings) | Initialise une nouvelle instance de la classe [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options) | Initialise une nouvelle instance de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options-settings) | Initialise une nouvelle instance de Viewer. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [dispose](/viewer/python-net/groupdocs.viewer/viewer/dispose/) | Libère le flux de fichier et les ressources internes gérées. |
| [get_all_fonts](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) | Renvoie toutes les polices utilisées dans le document chargé, y compris les polices incorporées et les polices système installées sur le système d'exploitation. |
| [get_attachments](/viewer/python-net/groupdocs.viewer/viewer/get_attachments/) | Renvoie les pièces jointes contenues dans le document. |
| [get_file_info](/viewer/python-net/groupdocs.viewer/viewer/get_file_info/) | Renvoie des informations sur le fichier, telles que le type de fichier et un indicateur indiquant si le fichier est chiffré. |
| [get_view_info](/viewer/python-net/groupdocs.viewer/viewer/get_view_info/#options) | Renvoie les informations spécifiques à la vue et au document. |
| [get_view_info_view_info_options](/viewer/python-net/groupdocs.viewer/viewer/get_view_info_view_info_options/) |  |
| [save_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment/#attachment-destination) | Enregistre le fichier joint dans le flux `destination`. |
| [save_attachment_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_attachment/) |  |
| [save_attachment_stream](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_stream/) |  |
| [save_attachment_streams](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_streams/) |  |
| [search](/viewer/python-net/groupdocs.viewer/viewer/search/#options) | Effectue une recherche de texte et met en surbrillance le texte trouvé dans le document chargé selon les options fournies. |
| [search_search_highlight_options](/viewer/python-net/groupdocs.viewer/viewer/search_search_highlight_options/) |  |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options) | Crée une vue de toutes les pages du document. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-page_numbers) | Crée une vue de pages spécifiques du document. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-cancellation_token-page_numbers) | Crée une vue de pages spécifiques du document. |
| [view_view_options](/viewer/python-net/groupdocs.viewer/viewer/view_view_options/) |  |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, PngViewOptions

# Rendu du DOCX en HTML
with Viewer("./sample.docx") as viewer:
    html_opts = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(html_opts)

# Rendu du PDF en PNG
with Viewer("document.pdf") as viewer:
    png_opts = PngViewOptions("page_{0}.png")
    viewer.view(png_opts)
```

### Guides
Guides de tâches utilisant `Viewer` :

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Get Document Information](/viewer/python-net/guides/get-document-info/)
* [Load document from local disk](/viewer/python-net/guides/load-document-from-local-disk/)
* [Load document from stream](/viewer/python-net/guides/load-document-from-stream/)
* [Load document from URL](/viewer/python-net/guides/load-document-from-url/)
* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)
* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)
* [Reorder pages](/viewer/python-net/guides/reorder-pages/)
* [Save attachments](/viewer/python-net/guides/how-to-extract-and-save-attachments/)

### Voir aussi
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
