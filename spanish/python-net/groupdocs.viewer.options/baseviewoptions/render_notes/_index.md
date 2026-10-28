---
title: "propiedad render_notes"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La propiedad habilita la renderización de notas y anotaciones para algunos formatos."
type: docs
url: /es/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/
is_root: false
weight: 2130
---


## render_notes property

La propiedad habilita la renderización de notas y anotaciones para algunos formatos.

Algunos formatos, como presentaciones o archivos de Microsoft Project, pueden contener notas. Además, los archivos PDF pueden tener anotaciones emergentes (sugerencias en globo) que están ocultas por defecto y solo son visibles en un visor PDF al pasar el cursor del ratón sobre ellas. Por defecto, GroupDocs.Viewer no renderiza esas notas y anotaciones (`False`). Para hacerlo, establezca esta propiedad a `True`.

Para un ejemplo de código, consulte la documentación.

### Definition:
```python
@property
def render_notes(self):
    ...
@render_notes.setter
def render_notes(self, value):
    ...
```

### Ver también
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
