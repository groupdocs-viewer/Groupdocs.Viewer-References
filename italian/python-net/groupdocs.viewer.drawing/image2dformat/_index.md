---
title: "Classe Image2DFormat"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta i formati di immagine 2D più comuni, supporta sia formati raster che vettoriali."
type: docs
url: /it/python-net/groupdocs.viewer.drawing/image2dformat/
is_root: false
weight: 60
---


## Image2DFormat class

Rappresenta i formati di immagine 2D più comuni, supporta sia formati raster che vettoriali.

Il tipo Image2DFormat espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/__init__/) |  |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals/#other) | Determina se questa istanza è uguale all'istanza specificata [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/). |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals/#obj) | Determina se questa istanza è uguale all'oggetto specificato, che si presume sia un'altra istanza [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/). |
| [equals_image_2d_format](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals_image_2d_format/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/get_hash_code/) | Restituisce un codice hash, che è un numero immutabile per questa specifica istanza. |
| [parse_from_filename_with_extension](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_filename_with_extension/#filename) | Restituisce un valore Image2DFormat che corrisponde all'estensione del file estratta dal nome file specificato. |
| [parse_from_mime](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_mime/#mime_code) | Restituisce un valore [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/) che corrisponde al codice MIME specificato. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/to_string/) | Restituisce la proprietà [`Image2DFormat.name`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/name/). |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [file_extension](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/file_extension/) | L'estensione del file (senza il carattere punto iniziale) di un particolare tipo di immagine in minuscolo. |
| [is_vector](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/is_vector/) | Il formato è vettoriale (`True`) o raster (`False`). |
| [mime_code](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/mime_code/) | Il codice MIME di un particolare tipo di immagine come stringa. Per il tipo Undefined restituisce la stringa 'unsefined'. |
| [name](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/name/) | Il nome formale di questo formato immagine. |

### Campi
| Campo | Descrizione |
| :- | :- |
| [UNDEFINED](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/undefined/) | Tipo di immagine Undefined - valore speciale, che normalmente non dovrebbe verificarsi |
| [JPEG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/jpeg/) | Tipo di immagine JPEG |
| [PNG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/png/) | Tipo di immagine PNG |
| [BMP](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/bmp/) | Tipo di immagine BMP |
| [GIF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/gif/) | Tipo di immagine GIF |
| [ICON](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/icon/) | Tipo di immagine ICON |
| [SVG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/svg/) | Tipo di immagine vettoriale SVG |
| [WMF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/wmf/) | WMF (Windows MetaFile) tipo di immagine vettoriale |
| [EMF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/emf/) | EMF (Enhanced MetaFile) tipo di immagine vettoriale |
| [TIFF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/tiff/) | TIFF (Tagged Image File Format) tipo di immagine raster |

### Vedi anche
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
