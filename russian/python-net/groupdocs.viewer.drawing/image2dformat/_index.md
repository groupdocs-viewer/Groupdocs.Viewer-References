---
title: "Класс Image2DFormat"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет наиболее распространённые 2‑D форматы изображений, поддерживает как растровые, так и векторные форматы."
type: docs
url: /ru/python-net/groupdocs.viewer.drawing/image2dformat/
is_root: false
weight: 60
---


## Image2DFormat class

Представляет наиболее распространённые 2‑D форматы изображений, поддерживает как растровые, так и векторные форматы.

Тип Image2DFormat раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/__init__/) |  |

### Методы
| Метод | Описание |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals/#other) | Определяет, равен ли данный экземпляр указанному экземпляру [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/). |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals/#obj) | Определяет, равен ли данный экземпляр указанному объекту, который предполагается другим экземпляром [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/). |
| [equals_image_2d_format](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals_image_2d_format/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/get_hash_code/) | Возвращает хеш‑код, который является неизменяемым числом для данного конкретного экземпляра. |
| [parse_from_filename_with_extension](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_filename_with_extension/#filename) | Возвращает значение Image2DFormat, соответствующее расширению файла, извлечённому из указанного имени файла. |
| [parse_from_mime](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/parse_from_mime/#mime_code) | Возвращает значение [`Image2DFormat`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/), соответствующее указанному MIME‑коду. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/to_string/) | Возвращает свойство [`Image2DFormat.name`](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/name/). |

### Свойства
| Свойство | Описание |
| :- | :- |
| [file_extension](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/file_extension/) | Расширение файла (без начальной точки) конкретного типа изображения в нижнем регистре. |
| [is_vector](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/is_vector/) | Формат является векторным (`True`) или растровым (`False`). |
| [mime_code](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/mime_code/) | MIME‑код конкретного типа изображения в виде строки. Для типа Undefined возвращается строка 'unsefined'. |
| [name](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/name/) | Официальное название этого формата изображения. |

### Поля
| Поле | Описание |
| :- | :- |
| [UNDEFINED](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/undefined/) | Неопределённый тип изображения — специальное значение, которое обычно не должно встречаться. |
| [JPEG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/jpeg/) | Тип изображения JPEG |
| [PNG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/png/) | Тип изображения PNG |
| [BMP](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/bmp/) | Тип изображения BMP |
| [GIF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/gif/) | Тип изображения GIF |
| [ICON](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/icon/) | Тип изображения ICON |
| [SVG](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/svg/) | Тип векторного изображения SVG |
| [WMF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/wmf/) | WMF (Windows MetaFile) тип векторного изображения |
| [EMF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/emf/) | EMF (Enhanced MetaFile) тип векторного изображения |
| [TIFF](/viewer/python-net/groupdocs.viewer.drawing/image2dformat/tiff/) | TIFF (Tagged Image File Format) тип растрового изображения |

### См. также
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
