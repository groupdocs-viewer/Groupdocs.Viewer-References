---
title: "Clase EmailOptions"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Contiene opciones para renderizar mensajes de correo electrónico."
type: docs
url: /es/python-net/groupdocs.viewer.options/emailoptions/
is_root: false
weight: 40
---


## EmailOptions class

Contiene opciones para renderizar mensajes de correo electrónico.

GroupDocs.Viewer admite la clase EmailOptions que le permite especificar diferentes opciones para renderizar mensajes de correo electrónico. Para acceder a estas opciones, use la propiedad EmailOptions en una de las siguientes clases de opciones de vista, según el formato de salida deseado:

- [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
- [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
- [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
- [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)

El tipo EmailOptions expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/emailoptions/__init__/) | Inicializa una instancia de la clase [`EmailOptions`](/viewer/python-net/groupdocs.viewer.options/emailoptions/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [date_time_format](/viewer/python-net/groupdocs.viewer.options/emailoptions/date_time_format/) | El formato de hora (puede incluir zona horaria). Si no se establece, se utiliza el formato del sistema actual. |
| [field_text_map](/viewer/python-net/groupdocs.viewer.options/emailoptions/field_text_map/) | El mapeo entre el mensaje de correo electrónico [`Field`](/viewer/python-net/groupdocs.viewer.options/field/) y la representación de texto del campo. |
| [page_size](/viewer/python-net/groupdocs.viewer.options/emailoptions/page_size/) | El tamaño de la página de salida. |
| [time_zone_offset](/viewer/python-net/groupdocs.viewer.options/emailoptions/time_zone_offset/) | El desplazamiento de zona horaria del mensaje. |

### Ver también
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
