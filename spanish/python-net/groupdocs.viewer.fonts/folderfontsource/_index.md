---
title: "Clase FolderFontSource"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa la carpeta que contiene fuentes TrueType."
type: docs
url: /es/python-net/groupdocs.viewer.fonts/folderfontsource/
is_root: false
weight: 10
---


## FolderFontSource class

Representa la carpeta que contiene fuentes TrueType.

El tipo FolderFontSource expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/#folder_path-search_option) | Inicializa una nueva instancia de [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/). |

### Métodos
| Método | Descripción |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#other) | Determina si el FolderFontSource actual es el mismo que el objeto FolderFontSource especificado. |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#obj) | Determina si el FolderFontSource actual es el mismo que el objeto especificado. |
| [equals_folder_font_source](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_folder_font_source/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/get_hash_code/) | Devuelve el código hash del objeto [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) actual. |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/to_string/) | Devuelve una cadena que representa el objeto actual. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [folder_path](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/folder_path/) | La ruta a la carpeta que contiene fuentes TrueType. |
| [search_option](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/search_option/) | La opción de búsqueda que especifica si buscar en la carpeta actual, o en la carpeta actual y todas sus subcarpetas. |

### Ejemplo

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption

# Crea una fuente de fuentes que busque en todas las subcarpetas.
src = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
```

### Ver también
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
