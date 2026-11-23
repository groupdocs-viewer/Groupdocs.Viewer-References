---
title: "Clase IFontInfo"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa una interfaz común para todas las fuentes que pueden extraerse de todas las familias de formatos de documento compatibles: PDF, WordProcessing, Spreadsheet y Presentation."
type: docs
url: /es/python-net/groupdocs.viewer.fonts/ifontinfo/
is_root: false
weight: 50
---


## IFontInfo class

Representa una interfaz común para todas las fuentes que pueden extraerse de todas las familias de formatos de documento compatibles: PDF, WordProcessing, Spreadsheet y Presentation.

El tipo IFontInfo expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css/#output) | Serializa esta información de fuente como una regla @font-face y la escribe en el escritor de texto especificado. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css_text_writer/) |  |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/content/) | El contenido binario de la fuente como una matriz de bytes, si está disponible, o None si no lo está. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/family_name/) | El nombre de familia de la fuente como una cadena. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/format/) | El formato de esta fuente como un enum — TrueType, TrueType Collection, OpenType, Embedded OpenType, o `FontFormat.unknown`. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/style/) | El estilo de la fuente como un enum (Regular, Bold, Italic o Bold Italic); algunos formatos de documento pueden admitir solo [`FontStyles.regular`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/). |

### Ver también
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
