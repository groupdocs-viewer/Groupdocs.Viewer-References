---
title: "Clase PresentationFontInfo"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa metainformación y datos binarios de una fuente de un documento Presentation cargado en una instancia de Viewer."
type: docs
url: /es/python-net/groupdocs.viewer.fonts/presentationfontinfo/
is_root: false
weight: 80
---


## PresentationFontInfo class

Representa la información de metadatos y los datos binarios de una fuente de un documento Presentation cargado en una instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). La fuente se utiliza en el contenido del documento y puede estar incrustada en el documento o instalada en el sistema operativo donde se ejecuta el visor.

El tipo PresentationFontInfo expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/__init__/) |  |

### Métodos
| Método | Descripción |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css/#output) | Serializa esta información de fuente como una regla @font-face y la escribe en el escritor de texto especificado. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css_text_writer/) |  |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/content/) | El contenido de esta fuente como una matriz de bytes. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/family_name/) | El nombre de familia de la fuente, sin estilo; nunca None ni cadena vacía. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/format/) | El formato de esta fuente. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/) | La propiedad indica si la fuente está incrustada dentro del documento y cargada en la instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) (`True`), o si es una fuente del sistema (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/style/) | El estilo de la fuente — puede ser Regular, Bold, Italic o Bold Italic. |

### Ver también
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
