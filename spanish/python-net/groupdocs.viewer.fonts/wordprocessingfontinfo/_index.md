---
title: "Clase WordProcessingFontInfo"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Encapsula metainformación y datos binarios de una fuente de un documento WordProcessing cargado en una instancia de Viewer."
type: docs
url: /es/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/
is_root: false
weight: 110
---


## WordProcessingFontInfo class

Encapsula la información de metadatos y los datos binarios de una fuente de un documento WordProcessing cargado en una instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Estructura inmutable.

Sus instancias son producidas y devueltas por la API pública de [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) y normalmente no deberían ser creadas por el usuario.

Para más detalles, consulte la documentación: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

El tipo WordProcessingFontInfo expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/__init__/) |  |

### Métodos
| Método | Descripción |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css/#output) | Serializa la información de la fuente como una regla @font-face y la escribe en el escritor de texto especificado. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/to_string/) | Devuelve información de depuración sobre estos datos de fuente con la siguiente plantilla: "nombre estilo, incrustada/sistema, formato". |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [alt_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/alt_family_name/) | El nombre de familia alternativo de la fuente. Si falta, será una cadena vacía. |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/charset/) | El conjunto de caracteres de esta fuente. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/content/) | El contenido de esta fuente como una matriz de bytes. Si solo está disponible la metainformación de esta fuente y el contenido binario no está disponible, la propiedad devuelve None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/family_name/) | El nombre de familia de la fuente, sin estilo; nunca None ni cadena vacía. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/format/) | El formato de esta fuente. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/is_embedded/) | La propiedad indica si esta fuente está incrustada dentro del documento, cargada en la instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) (`True`), o es una fuente del sistema (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/style/) | El estilo de la fuente — puede ser Regular, Bold, Italic o Bold Italic. |

### Ver también
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
