---
title: "Clase FontSettings"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Proporciona métodos para trabajar con orígenes y buscar fuentes TrueType."
type: docs
url: /es/python-net/groupdocs.viewer.fonts/fontsettings/
is_root: false
weight: 30
---


## FontSettings class

Proporciona métodos para trabajar con orígenes y buscar fuentes TrueType.

El tipo FontSettings expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [reset_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/reset_font_sources/) | Restablece las fuentes tipográficas que se habían configurado previamente. |
| [set_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/#font_sources) | Establece las fuentes donde buscar fuentes TrueType al renderizar documentos. |

### Ejemplo

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Establece fuentes tipográficas usando varias formas de argumentos (aplanadas internamente)
FontSettings.set_font_sources(src1, src2)          # varargs
FontSettings.set_font_sources([src1, src2])        # single list
FontSettings.set_font_sources([src1], [src2])      # multiple lists (flattened)
FontSettings.set_font_sources([src1, src2], src2)  # mixed — also flattened

# Borra todas las fuentes tipográficas registradas
FontSettings.reset_font_sources()
```

### Ver también
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
