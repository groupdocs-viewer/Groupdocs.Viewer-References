---
title: Image2DFormat class
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.drawing/image2dformat/
is_root: false
weight: 20
---

## Image2DFormat class

Represents most common 2D image formats, supports both raster and vector formats



The Image2DFormat type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/__init__/#) | Constructs a new instance of Image2DFormat |


### Properties
| Property | Description |
| :- | :- |
| [undefined](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/undefined) | Undefined image type - special value, which should not normally occur |
| [jpeg](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/jpeg) | JPEG image type |
| [png](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/png) | PNG image type |
| [bmp](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/bmp) | BMP image type |
| [gif](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/gif) | GIF image type |
| [icon](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/icon) | ICON image type |
| [svg](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/svg) | SVG vector image type |
| [wmf](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/wmf) | WMF (Windows MetaFile) vector image type |
| [emf](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/emf) | EMF (Enhanced MetaFile) vector image type |
| [tiff](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/tiff) | TIFF (Tagged Image File Format) raster image type |
| [name](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/name) | Returns a formal name of this image format. Never reurns NULL. If instance is not corrupted, never throws an exception. |
| [is_vector](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/is_vector) | Indicates whether this particular format is vector (`true`) or raster (`false`) |
| [file_extension](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/file_extension) | File extension (without leading dot character) of a particular image type in lower case. For the [`Image2DFormat.undefined`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat#undefined) value returns a string 'undefined'. |
| [mime_code](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/mime_code) | MIME code of a particular image type as a string. For the Undefined type returns a string 'unsefined'. |


### Methods
| Method | Description |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals/#groupdocs.viewer.drawing.Image2DFormat) | Determines whether this instance is equal with specified "[`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat)" instance |
| [parse_from_filename_with_extension](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_filename_with_extension/#System.String) | Returns ImageFormat value, which is equivalent of filename extension, which is extracted from specified filename |
| [parse_from_mime](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_mime/#System.String) | Returns [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat) value, which is equivalent of specified MIME code |



### See Also
* module [`groupdocs.viewer.drawing`](..)
* class [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat)
