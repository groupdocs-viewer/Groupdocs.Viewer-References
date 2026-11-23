---
title: "Image2DFormat"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Представляет наиболее распространённые 2‑D форматы изображений, поддерживает как растровые, так и векторные форматы."
type: docs
weight: 960
url: /ru/net/groupdocs.viewer.drawing/image2dformat/
---

## Image2DFormat structure

Представляет наиболее распространённые 2D форматы изображений, поддерживает как растровые, так и векторные форматы

```csharp
public struct Image2DFormat : IEquatable<Image2DFormat>
```

## Свойства

| Имя | Описание |
| --- | --- |
| static [Bmp](../../groupdocs.viewer.drawing/image2dformat/bmp) { get; } | Тип изображения BMP |
| static [Emf](../../groupdocs.viewer.drawing/image2dformat/emf) { get; } | Тип векторного изображения EMF (Enhanced MetaFile) |
| static [Gif](../../groupdocs.viewer.drawing/image2dformat/gif) { get; } | Тип изображения GIF |
| static [Icon](../../groupdocs.viewer.drawing/image2dformat/icon) { get; } | Тип изображения ICON |
| static [Jpeg](../../groupdocs.viewer.drawing/image2dformat/jpeg) { get; } | Тип изображения JPEG |
| static [Png](../../groupdocs.viewer.drawing/image2dformat/png) { get; } | Тип изображения PNG |
| static [Svg](../../groupdocs.viewer.drawing/image2dformat/svg) { get; } | Тип векторного изображения SVG |
| static [Tiff](../../groupdocs.viewer.drawing/image2dformat/tiff) { get; } | Тип растрового изображения TIFF (Tagged Image File Format) |
| static [Undefined](../../groupdocs.viewer.drawing/image2dformat/undefined) { get; } | Неопределённый тип изображения — специальное значение, которое обычно не должно возникать |
| static [Wmf](../../groupdocs.viewer.drawing/image2dformat/wmf) { get; } | Тип векторного изображения WMF (Windows MetaFile) |
| [FileExtension](../../groupdocs.viewer.drawing/image2dformat/fileextension) { get; } | Расширение файла (без начальной точки) конкретного типа изображения в нижнем регистре. Для значения [`Undefined`](./undefined) возвращает строку 'undefined'. |
| [IsVector](../../groupdocs.viewer.drawing/image2dformat/isvector) { get; } | Указывает, является ли данный формат векторным (`true`) или растровым (`false`) |
| [MimeCode](../../groupdocs.viewer.drawing/image2dformat/mimecode) { get; } | MIME‑код конкретного типа изображения в виде строки. Для типа Undefined возвращает строку 'unsefined'. |
| [Name](../../groupdocs.viewer.drawing/image2dformat/name) { get; } | Возвращает официальное название этого формата изображения. Никогда не возвращает NULL. Если экземпляр не повреждён, исключение не выбрасывается. |

## Методы

| Имя | Описание |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.viewer.drawing/image2dformat/parsefromfilenamewithextension)(string) | Возвращает значение ImageFormat, которое эквивалентно расширению имени файла, извлечённому из указанного имени файла |
| static [ParseFromMime](../../groupdocs.viewer.drawing/image2dformat/parsefrommime)(string) | Возвращает значение [`Image2DFormat`](../image2dformat), которое эквивалентно указанному MIME‑коду |
| [Equals](../../groupdocs.viewer.drawing/image2dformat/equals#equals)(Image2DFormat) | Определяет, равен ли данный экземпляр указанному экземпляру "[`Image2DFormat`](../image2dformat)" |
| override [Equals](../../groupdocs.viewer.drawing/image2dformat/equals#equals_1)(object) | Определяет, равен ли данный экземпляр указанному неконвертированному объекту, который предположительно является другим экземпляром "[`Image2DFormat`](../image2dformat)" |
| override [GetHashCode](../../groupdocs.viewer.drawing/image2dformat/gethashcode)() | Возвращает хеш‑код, который является неизменяемым числом для данного конкретного экземпляра |
| override [ToString](../../groupdocs.viewer.drawing/image2dformat/tostring)() | Возвращает свойство [`Name`](./name) |
| [operator ==](../../groupdocs.viewer.drawing/image2dformat/op_equality) | Определяет, равны ли два конкретных экземпляра [`Image2DFormat`](../image2dformat) |
| [operator !=](../../groupdocs.viewer.drawing/image2dformat/op_inequality) | Определяет, не равны ли два конкретных экземпляра [`Image2DFormat`](../image2dformat) |

### См. также

* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
