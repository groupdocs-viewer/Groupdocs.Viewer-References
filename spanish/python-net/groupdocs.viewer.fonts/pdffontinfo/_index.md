---
title: "Clase PdfFontInfo"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Encapsula los metadatos y los datos binarios de una fuente PDF cargada en una instancia de Viewer, que puede estar incrustada en el documento o instalada en el sistema operativo donde se ejecuta GroupDocs.Viewer."
type: docs
url: /es/python-net/groupdocs.viewer.fonts/pdffontinfo/
is_root: false
weight: 70
---


## PdfFontInfo class

Encapsula los metadatos y los datos binarios de una fuente PDF cargada en una instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/), que puede estar incrustada en el documento o instalada en el sistema operativo donde se ejecuta GroupDocs.Viewer.

El tipo PdfFontInfo expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/__init__/) |  |

### Métodos
| Método | Descripción |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css/#output) | Serializa esta información de fuente como una regla @font-face y la escribe en el escritor de texto especificado. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css_text_writer/) |  |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/content/) | El contenido de esta fuente como una matriz de bytes, o None si solo están disponibles los metadatos y el contenido binario no está disponible. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/family_name/) | El nombre de familia de la fuente, sin estilo; nunca None ni cadena vacía. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/format/) | El formato de esta fuente. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_embedded/) | La propiedad indica si la fuente está incrustada dentro del documento PDF y cargada en la instancia de Viewer (`True`), o no. |
| [is_installed](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_installed/) | La propiedad indica si esta fuente está presente (instalada) en el sistema operativo donde se está ejecutando GroupDocs.Viewer. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/style/) | El estilo de la fuente; puede ser Regular, Bold, Italic o Bold Italic. |

### Ver también
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
