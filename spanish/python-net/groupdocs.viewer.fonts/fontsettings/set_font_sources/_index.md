---
title: "método set_font_sources"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Establece las fuentes donde buscar fuentes TrueType al renderizar documentos."
type: docs
url: /es/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/
is_root: false
weight: 1020
---


## set_font_sources {#font_sources}

Establece las fuentes donde buscar fuentes TrueType al renderizar documentos.

El método acepta cualquier combinación de objetos individuales [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/), listas de ellos o una mezcla de ambos; todas las entradas se aplanan en una sola lista antes de aplicarse. Las rutas de cadena se pasan tal cual y no se dividen en caracteres.

```python
def set_font_sources(cls, font_sources):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_sources | `list[IFontSource]` | Las fuentes de fuentes. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `font_sources` es None. |

### Ejemplo

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# varargs
FontSettings.set_font_sources(src1, src2)
# lista única
FontSettings.set_font_sources([src1, src2])
# múltiples listas (aplanadas)
FontSettings.set_font_sources([src1], [src2])
# mixto — también aplanado
FontSettings.set_font_sources([src1, src2], src2)
```

### Ver también
* class [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/)
