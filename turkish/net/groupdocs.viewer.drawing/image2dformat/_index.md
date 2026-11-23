---
title: "Image2DFormat"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "En yaygın 2D görüntü formatlarını temsil eder; hem raster hem de vektör formatlarını destekler."
type: docs
weight: 960
url: /tr/net/groupdocs.viewer.drawing/image2dformat/
---

## Image2DFormat structure

En yaygın 2D görüntü formatlarını temsil eder, hem raster hem vektör formatlarını destekler.

```csharp
public struct Image2DFormat : IEquatable<Image2DFormat>
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [Bmp](../../groupdocs.viewer.drawing/image2dformat/bmp) { get; } | BMP görüntü türü |
| static [Emf](../../groupdocs.viewer.drawing/image2dformat/emf) { get; } | EMF (Enhanced MetaFile) vektör görüntü türü |
| static [Gif](../../groupdocs.viewer.drawing/image2dformat/gif) { get; } | GIF görüntü türü |
| static [Icon](../../groupdocs.viewer.drawing/image2dformat/icon) { get; } | ICON görüntü türü |
| static [Jpeg](../../groupdocs.viewer.drawing/image2dformat/jpeg) { get; } | JPEG görüntü türü |
| static [Png](../../groupdocs.viewer.drawing/image2dformat/png) { get; } | PNG görüntü türü |
| static [Svg](../../groupdocs.viewer.drawing/image2dformat/svg) { get; } | SVG vektör görüntü türü |
| static [Tiff](../../groupdocs.viewer.drawing/image2dformat/tiff) { get; } | TIFF (Tagged Image File Format) raster görüntü türü |
| static [Undefined](../../groupdocs.viewer.drawing/image2dformat/undefined) { get; } | Tanımsız görüntü türü - normalde ortaya çıkmaması gereken özel bir değer |
| static [Wmf](../../groupdocs.viewer.drawing/image2dformat/wmf) { get; } | WMF (Windows MetaFile) vektör görüntü türü |
| [FileExtension](../../groupdocs.viewer.drawing/image2dformat/fileextension) { get; } | Belirli bir görüntü türünün küçük harfli dosya uzantısı (başındaki nokta karakteri olmadan). [`Undefined`](./undefined) değeri için 'undefined' dizesi döndürür. |
| [IsVector](../../groupdocs.viewer.drawing/image2dformat/isvector) { get; } | Bu belirli formatın vektör (`true`) mı yoksa raster (`false`) mı olduğunu gösterir |
| [MimeCode](../../groupdocs.viewer.drawing/image2dformat/mimecode) { get; } | Belirli bir görüntü türünün MIME kodu bir dize olarak. Tanımsız (Undefined) türü için 'unsefined' dizesi döndürür. |
| [Name](../../groupdocs.viewer.drawing/image2dformat/name) { get; } | Bu görüntü formatının resmi adını döndürür. Asla NULL döndürmez. Örnek bozulmamışsa, hiçbir zaman istisna fırlatmaz. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.viewer.drawing/image2dformat/parsefromfilenamewithextension)(string) | Belirtilen dosya adından çıkarılan dosya uzantısına eşdeğer olan ImageFormat değerini döndürür |
| static [ParseFromMime](../../groupdocs.viewer.drawing/image2dformat/parsefrommime)(string) | Belirtilen MIME koduna eşdeğer olan [`Image2DFormat`](../image2dformat) değerini döndürür |
| [Equals](../../groupdocs.viewer.drawing/image2dformat/equals#equals)(Image2DFormat) | Bu örneğin belirtilen "[`Image2DFormat`](../image2dformat)" örneğiyle eşit olup olmadığını belirler |
| override [Equals](../../groupdocs.viewer.drawing/image2dformat/equals#equals_1)(object) | Bu örneğin belirtilen tip dönüşümü yapılmamış nesneyle, muhtemelen başka bir "[`Image2DFormat`](../image2dformat)" örneğiyle eşit olup olmadığını belirler |
| override [GetHashCode](../../groupdocs.viewer.drawing/image2dformat/gethashcode)() | Bu belirli örnek için değişmez bir sayı olan hash kodunu döndürür |
| override [ToString](../../groupdocs.viewer.drawing/image2dformat/tostring)() | Bir [`Name`](./name) özelliğini döndürür |
| [operator ==](../../groupdocs.viewer.drawing/image2dformat/op_equality) | İki belirli [`Image2DFormat`](../image2dformat) örneğinin eşit olup olmadığını tanımlar |
| [operator !=](../../groupdocs.viewer.drawing/image2dformat/op_inequality) | İki belirli [`Image2DFormat`](../image2dformat) örneğinin eşit olmama durumunu tanımlar |

### Ayrıca Bakınız

* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
