---
title: "Clase Image2DFormat"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa los formatos de imagen 2D más comunes, soporta tanto formatos raster como vectoriales."
type: docs
url: /es/python-net/groupdocs.viewer.drawing/image2dformat/
is_root: false
weight: 60
---


## Image2DFormat class

Representa los formatos de imagen 2D más comunes, soporta tanto formatos raster como vectoriales.

El tipo Image2DFormat expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/__init__/) |  |

### Métodos
| Método | Descripción |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals/#other) | Determina si esta instancia es igual a la instancia especificada de [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/). |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals/#obj) | Determina si esta instancia es igual al objeto especificado, que se presume es otra instancia de [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/). |
| [equals_image_2d_format](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals_image_2d_format/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/get_hash_code/) | Devuelve un código hash, que es un número inmutable para esta instancia específica. |
| [parse_from_filename_with_extension](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_filename_with_extension/#filename) | Devuelve un valor Image2DFormat que corresponde a la extensión de archivo extraída del nombre de archivo especificado. |
| [parse_from_mime](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_mime/#mime_code) | Devuelve un valor [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/) que corresponde al código MIME especificado. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/to_string/) | Devuelve la propiedad [`Image2DFormat.name`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/name/). |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [file_extension](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/file_extension/) | La extensión de archivo (sin el carácter de punto inicial) de un tipo de imagen particular en minúsculas. |
| [is_vector](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/is_vector/) | El formato es vector (`True`) o raster (`False`). |
| [mime_code](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/mime_code/) | El código MIME de un tipo de imagen particular como cadena. Para el tipo Undefined devuelve la cadena 'unsefined'. |
| [name](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/name/) | El nombre formal de este formato de imagen. |

### Campos
| Campo | Descripción |
| :- | :- |
| [UNDEFINED](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/undefined/) | Tipo de imagen Undefined - valor especial, que normalmente no debería ocurrir |
| [JPEG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/jpeg/) | Tipo de imagen JPEG |
| [PNG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/png/) | Tipo de imagen PNG |
| [BMP](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/bmp/) | Tipo de imagen BMP |
| [GIF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/gif/) | Tipo de imagen GIF |
| [ICON](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/icon/) | Tipo de imagen ICON |
| [SVG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/svg/) | Tipo de imagen vectorial SVG |
| [WMF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/wmf/) | Tipo de imagen vectorial WMF (Windows MetaFile) |
| [EMF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/emf/) | Tipo de imagen vectorial EMF (Enhanced MetaFile) |
| [TIFF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/tiff/) | Tipo de imagen raster TIFF (Tagged Image File Format) |

### Ver también
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
