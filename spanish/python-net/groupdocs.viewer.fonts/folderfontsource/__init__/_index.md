---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una nueva instancia de FolderFontSource."
type: docs
url: /es/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/
is_root: false
weight: 10
---


## __init__ {#folder_path-search_option}

Inicializa una nueva instancia de [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/).

```python
def __init__(self, folder_path, search_option):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| folder_path | `str` | Ruta a la carpeta que contiene fuentes TrueType. |
| search_option | `SearchOption` | Especifica si buscar solo en la carpeta actual o en la carpeta actual y todas sus sub‑carpetas. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `folder_path` es None. |
| `FileNotFoundError` | Si la ruta especificada en `folder_path` no se puede localizar. |

### Ejemplo

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption, FontSettings

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Registrar las fuentes para renderizar
FontSettings.set_font_sources(src1, src2)

# Al terminar, restablecer para evitar fugas de fuentes
FontSettings.reset_font_sources()
```

### Ver también
* class [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)
