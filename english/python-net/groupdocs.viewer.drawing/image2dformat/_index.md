---
title: Image2DFormat class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents most common 2D image formats, supports both raster and vector formats."
type: docs
url: /python-net/groupdocs.viewer.drawing/image2dformat/
is_root: false
weight: 60
---


## Image2DFormat class

Represents most common 2D image formats, supports both raster and vector formats.

The Image2DFormat type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/__init__/) |  |

### Methods
| Method | Description |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals/#other) | Determines whether this instance is equal to the specified [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/) instance. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals/#obj) | Determines whether this instance is equal to the specified object, which is presumed to be another [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/) instance. |
| [equals_image_2d_format](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals_image_2d_format/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/get_hash_code/) | Returns a hash code, which is an immutable number for this specific instance. |
| [parse_from_filename_with_extension](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_filename_with_extension/#filename) | Returns an Image2DFormat value that corresponds to the file extension extracted from the specified filename. |
| [parse_from_mime](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_mime/#mime_code) | Returns an [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/) value that corresponds to the specified MIME code. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/to_string/) | Returns the [`Image2DFormat.name`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/name/) property. |

### Properties
| Property | Description |
| :- | :- |
| [file_extension](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/file_extension/) | The file extension (without leading dot character) of a particular image type in lower case. |
| [is_vector](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/is_vector/) | The format is vector (`True`) or raster (`False`). |
| [mime_code](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/mime_code/) | The MIME code of a particular image type as a string. For the Undefined type returns a string 'unsefined'. |
| [name](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/name/) | The formal name of this image format. |

### Fields
| Field | Description |
| :- | :- |
| [UNDEFINED](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/undefined/) | Undefined image type - special value, which should not normally occur |
| [JPEG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/jpeg/) | JPEG image type |
| [PNG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/png/) | PNG image type |
| [BMP](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/bmp/) | BMP image type |
| [GIF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/gif/) | GIF image type |
| [ICON](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/icon/) | ICON image type |
| [SVG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/svg/) | SVG vector image type |
| [WMF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/wmf/) | WMF (Windows MetaFile) vector image type |
| [EMF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/emf/) | EMF (Enhanced MetaFile) vector image type |
| [TIFF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/tiff/) | TIFF (Tagged Image File Format) raster image type |

### See Also
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
