---
title: Image2DFormat
second_title: GroupDocs.Viewer for Python via .NET API Reference
description: 
type: docs
weight: 20
url: /python-net/groupdocs.viewer.drawing/image2dformat/
---

## Image2DFormat class

Represents most common 2D image formats, supports both raster and vector formats

The Image2DFormat type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Image2DFormat()|Initializes a new instance of the Image2DFormat class|
## Properties
| Name | Description |
| :- | :- |
|undefined|Undefined image type - special value, which should not normally occur|
|jpeg|JPEG image type|
|png|PNG image type|
|bmp|BMP image type|
|gif|GIF image type|
|icon|ICON image type|
|svg|SVG vector image type|
|wmf|WMF (Windows MetaFile) vector image type|
|emf|EMF (Enhanced MetaFile) vector image type|
|tiff|TIFF (Tagged Image File Format) raster image type|
|name|Returns a formal name of this image format. Never reurns NULL. If instance is not corrupted, never throws an exception.|
|is_vector|Indicates whether this particular format is vector (|
|file_extension|File extension (without leading dot character) of a particular image type in lower case. For the [undefined](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/) value returns a string 'undefined'.|
|mime_code|MIME code of a particular image type as a string. For the Undefined type returns a string 'unsefined'.|
## Methods
| Name | Description |
| :- | :- |
|equals(other)|Determines whether this instance is equal with specified "[Image2DFormat](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/)" instance|
|parse_from_filename_with_extension(filename)|Returns ImageFormat value, which is equivalent of filename extension, which is extracted from specified filename|
|parse_from_mime(mime_code)|Returns [Image2DFormat](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/) value, which is equivalent of specified MIME code|

### See Also

* namespace [groupdocs.viewer.drawing](/viewer/python-net/groupdocs.viewer.drawing/)
* assembly [GroupDocs.Viewer](/viewer/python-net/)

