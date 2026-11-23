---
title: "Clase WordProcessingSubstitutedFontInfo"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Encapsula la metainformación y los datos binarios de una fuente de un documento WordProcessing, que originalmente no se usa en el documento cargado en la instancia de Viewer, pero sirve como fuente de sustitución para aquellas que…"
type: docs
url: /es/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
is_root: false
weight: 120
---


## WordProcessingSubstitutedFontInfo class

Encapsula la información de metadatos y los datos binarios de una fuente de un documento WordProcessing, que originalmente no se utiliza en el documento de la instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) cargada, pero sirve como fuente de sustitución para aquellas que no pueden encontrarse en la máquina de destino. Las fuentes sustitutas existen solo para la familia de formatos WordProcessing.

Estructura inmutable. Sus instancias son producidas y devueltas por la API pública de [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) y normalmente no deberían ser creadas por el usuario. Para más detalles, consulte la documentación: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

El tipo WordProcessingSubstitutedFontInfo expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/__init__/) |  |

### Métodos
| Método | Descripción |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css/#output) | Serializa la información de la fuente como una regla @font-face y la escribe en el escritor de texto especificado. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/to_string/) | Devuelve una cadena de depuración que contiene información de la fuente en el formato "original-name -> substituted-name style, format". |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content/) | El contenido de la fuente sustituida como una matriz de bytes. Nunca es None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/family_name/) | El nombre de familia de la fuente sustituida, sin estilo. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format/) | El formato de esta fuente sustituida (no original). |
| [original_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/original_family_name/) | El nombre de familia de la fuente original, que no se puede encontrar en una máquina objetivo, sin estilo. Nunca es nulo ni cadena vacía. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style/) | El estilo de la fuente original — puede ser Regular, Bold, Italic o Bold Italic. |

### Ver también
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
