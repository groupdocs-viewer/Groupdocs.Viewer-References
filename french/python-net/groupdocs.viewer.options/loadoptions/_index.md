---
title: "Classe LoadOptions"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Les options utilisées pour ouvrir un fichier."
type: docs
url: /fr/python-net/groupdocs.viewer.options/loadoptions/
is_root: false
weight: 110
---


## LoadOptions class

Les options utilisées pour ouvrir un fichier.

Le type LoadOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/) | Initialise une instance de la classe [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/). |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/#file_type) | Initialise une nouvelle instance de LoadOptions. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/) | La propriété active la détection d’encodage pour les fichiers [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), et [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/). |
| [encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) | L’encodage utilisé lors de l’ouverture de fichiers texte ou de messages électroniques tels que [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), et [`FileType.msg`](/viewer/python-net/groupdocs.viewer/filetype/msg/). La valeur par défaut est `utf-8`. |
| [file_type](/viewer/python-net/groupdocs.viewer.options/loadoptions/file_type/) | Le type du fichier à ouvrir. |
| [password](/viewer/python-net/groupdocs.viewer.options/loadoptions/password/) | Le mot de passe pour ouvrir un fichier chiffré. |
| [resource_loading_timeout](/viewer/python-net/groupdocs.viewer.options/loadoptions/resource_loading_timeout/) | Le délai d’attente pour charger les ressources externes. |
| [skip_external_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) | La propriété désactive le chargement de toutes les ressources externes telles que les images, sauf celles répertoriées dans [`LoadOptions.whitelisted_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/). |
| [try_repair](/viewer/python-net/groupdocs.viewer.options/loadoptions/try_repair/) | La propriété permet à GroupDocs.Viewer de tenter de réparer la corruption structurelle des documents PDF. La valeur par défaut est False. |
| [whitelisted_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) | La liste des fragments d’URL correspondant aux ressources externes qui doivent être chargées lorsque [`LoadOptions.skip_external_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) est définie sur `True`. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, LoadOptions

load_options = LoadOptions()
load_options.password = "12345"

with Viewer("protected.docx", load_options) as viewer:
    viewer.view(HtmlViewOptions.for_embedded_resources("page_{0}.html"))
```

### Voir aussi
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
