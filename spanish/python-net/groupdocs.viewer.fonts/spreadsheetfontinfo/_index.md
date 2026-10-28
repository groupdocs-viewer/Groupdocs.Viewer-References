---
title: "Clase SpreadsheetFontInfo"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Encapsula metainformación y datos binarios de una fuente de un documento de hoja de cálculo cargado en una instancia de Viewer."
type: docs
url: /es/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/
is_root: false
weight: 100
---


## SpreadsheetFontInfo class

Encapsula la información de metadatos y los datos binarios de una fuente de un documento de hoja de cálculo cargado en una instancia de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). Los documentos de hoja de cálculo no pueden contener fuentes incrustadas, por lo que una fuente devuelta por [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) se instala en el sistema operativo donde se ejecuta el visor.

El tipo SpreadsheetFontInfo expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/__init__/) |  |

### Métodos
| Método | Descripción |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/#output) | Serializa la información de la fuente como una regla @font-face y la escribe en el escritor de texto especificado. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css_text_writer/) |  |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/charset/) | El conjunto de caracteres de esta fuente. |
| [color](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/color/) | El color de esta fuente. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/content/) | El contenido de esta fuente como una matriz de bytes. Si solo está disponible la metainformación sobre esta fuente y su contenido binario no está disponible, la propiedad devuelve None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/family_name/) | El nombre de familia de la fuente, sin estilo, nunca es nulo ni una cadena vacía. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/format/) | El formato de esta fuente. |
| [is_strikeout](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_strikeout/) | La fuente tiene un solo tachado. |
| [is_underline](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_underline/) | La fuente tiene subrayado. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/style/) | El estilo de esta fuente — puede ser Regular, Bold, Italic o Bold Italic. |

### Ver también
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
