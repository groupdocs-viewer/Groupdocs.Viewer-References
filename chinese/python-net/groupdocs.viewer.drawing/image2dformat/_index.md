---
title: "Image2DFormat 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示最常见的 2D 图像格式，支持光栅和矢量格式。"
type: docs
url: /zh/python-net/groupdocs.viewer.drawing/image2dformat/
is_root: false
weight: 60
---


## Image2DFormat class

表示最常见的 2D 图像格式，支持光栅和矢量格式。

Image2DFormat 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/__init__/) |  |

### 方法
| 方法 | 描述 |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals/#other) | 确定此实例是否等于指定的 [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/) 实例。 |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals/#obj) | 确定此实例是否等于指定的对象，该对象被假定为另一个 [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/) 实例。 |
| [equals_image_2d_format](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals_image_2d_format/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/get_hash_code/) | 返回哈希码，这是此特定实例的不可变数字。 |
| [parse_from_filename_with_extension](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_filename_with_extension/#filename) | 返回一个 Image2DFormat 值，该值对应于从指定文件名提取的文件扩展名。 |
| [parse_from_mime](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_mime/#mime_code) | 返回一个 [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/) 值，该值对应于指定的 MIME 代码。 |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/to_string/) | 返回 [`Image2DFormat.name`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/name/) 属性。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [file_extension](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/file_extension/) | 特定图像类型的文件扩展名（不含前导点字符），使用小写形式。 |
| [is_vector](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/is_vector/) | 该格式是矢量 (`True`) 或光栅 (`False`)。 |
| [mime_code](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/mime_code/) | 特定图像类型的 MIME 代码，以字符串形式表示。对于 Undefined 类型返回字符串 'unsefined'。 |
| [name](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/name/) | 此图像格式的正式名称。 |

### 字段
| 字段 | 描述 |
| :- | :- |
| [UNDEFINED](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/undefined/) | 未定义的图像类型 - 特殊值，通常不应出现 |
| [JPEG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/jpeg/) | JPEG 图像类型 |
| [PNG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/png/) | PNG 图像类型 |
| [BMP](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/bmp/) | BMP 图像类型 |
| [GIF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/gif/) | GIF 图像类型 |
| [ICON](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/icon/) | ICON 图像类型 |
| [SVG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/svg/) | SVG 矢量图像类型 |
| [WMF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/wmf/) | WMF (Windows MetaFile) 矢量图像类型 |
| [EMF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/emf/) | EMF (Enhanced MetaFile) 矢量图像类型 |
| [TIFF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/tiff/) | TIFF (Tagged Image File Format) 栅格图像类型 |

### 另见
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
