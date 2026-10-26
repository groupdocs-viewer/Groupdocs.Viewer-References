---
title: "FontStyles"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Belge içinde kullanılan yazının 4 olası stilini temsil eder: Regular, Bold, Italic veya Bold Italic"
type: docs
weight: 810
url: /tr/net/groupdocs.viewer.fonts/fontstyles/
---

## FontStyles structure

Belgede kullanılan yazı tipinin 4 olası stilini temsil eder: Regular, Bold, Italic, or Bold Italic

```csharp
public struct FontStyles : IEquatable<FontStyles>
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [FontStyles](fontstyles)(bool, bool) | Belirtilen kalın ve italik bayraklarından bir [`FontStyles`](../fontstyles) örneği oluşturur |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [IsBold](../../groupdocs.viewer.fonts/fontstyles/isbold) { get; } | Bu [`FontStyles`](../fontstyles) örneğinin **bold** bayrağının etkin (`true`) veya devre dışı (`false`) olduğunu gösterir |
| [IsItalic](../../groupdocs.viewer.fonts/fontstyles/isitalic) { get; } | Bu [`FontStyles`](../fontstyles) örneğinin **italic** bayrağının etkin (`true`) veya devre dışı (`false`) olduğunu gösterir |
| [Name](../../groupdocs.viewer.fonts/fontstyles/name) { get; } | Bu yazı tipi stilinin adı |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Equals](../../groupdocs.viewer.fonts/fontstyles/equals#equals)(FontStyles) | Bu [`FontStyles`](../fontstyles) örneğinin belirtilenle eşit olup olmadığını gösterir |
| override [Equals](../../groupdocs.viewer.fonts/fontstyles/equals#equals_1)(object) | Bu [`FontStyles`](../fontstyles) örneğinin belirtilen dönüştürülmemiş değerle eşit olup olmadığını gösterir |
| override [GetHashCode](../../groupdocs.viewer.fonts/fontstyles/gethashcode)() | Bu örneğin bir hash kodunu döndürür |
| override [ToString](../../groupdocs.viewer.fonts/fontstyles/tostring)() | Bu yazı tipi stilinin adını döndürür, [`Name`](./name) ile aynı |
| static [TryParse](../../groupdocs.viewer.fonts/fontstyles/tryparse)(string, out FontStyles) | Belirtilen ham dizeyi bir yazı tipi stil adı olarak ayrıştırmayı dener |
| [operator +](../../groupdocs.viewer.fonts/fontstyles/op_addition) | İki belirtilen yazı tipi stilini birleştirir (merge) ve bayrakların birleştirildiği (birleşim) yeni bir sonuç yazı tipi stili üretir |
| [operator ==](../../groupdocs.viewer.fonts/fontstyles/op_equality) | İki [`FontStyles`](../fontstyles) değerinin eşit olup olmadığını denetler |
| [explicit operator](../../groupdocs.viewer.fonts/fontstyles/op_explicit) | Belirtilen [`FontStyles`](../fontstyles) örneğini eşdeğer oktete (8-bit bitfield) [0..3] ondalık aralığında dönüştürür |
| [operator !=](../../groupdocs.viewer.fonts/fontstyles/op_inequality) | İki [`FontStyles`](../fontstyles) değerinin eşit olmadığını denetler |
| [operator -](../../groupdocs.viewer.fonts/fontstyles/op_subtraction) | İkinci (subtrahend) belirtilen yazı tipi stilini birinci (minuend) belirtilen yazı tipi stilinden çıkarır ve yalnızca ikinci işlenen içinde bulunmayan birinci işlenenin bayraklarını içeren yeni bir sonuç yazı tipi stili üretir (fark) |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| static readonly [Bold](../../groupdocs.viewer.fonts/fontstyles/bold) | Bold yazı tipi stili (sadece kalın, italik olmadan) |
| static readonly [BoldItalic](../../groupdocs.viewer.fonts/fontstyles/bolditalic) | BoldItalic yazı tipi stili (kalın ve italik birlikte) |
| static readonly [Italic](../../groupdocs.viewer.fonts/fontstyles/italic) | Italic yazı tipi stili (sadece italik, kalın olmadan) |
| static readonly [Regular](../../groupdocs.viewer.fonts/fontstyles/regular) | Regular yazı tipi stili, varsayılan değer (kalın ve italik yok) |

### Açıklamalar

Kullanışlı API ve birleştirme işlemlerine sahip değiştirilemez struct

### Ayrıca Bakınız

* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
