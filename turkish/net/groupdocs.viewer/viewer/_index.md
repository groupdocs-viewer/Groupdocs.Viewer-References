---
title: "Viewer"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Belge renderleme sürecini kontrol eden ana sınıfı temsil eder."
type: docs
weight: 50
url: /tr/net/groupdocs.viewer/viewer/
---

## Viewer class

Belge renderleme sürecini kontrol eden ana sınıfı temsil eder.

```csharp
public class Viewer : IDisposable
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Viewer](viewer#constructor)(Func&lt;Stream&gt;) | Yeni bir [`Viewer`](../viewer) sınıfı örneğini başlatır. |
| [Viewer](viewer#constructor_4)(Stream) | Yeni bir [`Viewer`](../viewer) sınıfı örneğini başlatır. |
| [Viewer](viewer#constructor_12)(string) | Yeni bir [`Viewer`](../viewer) sınıfı örneğini başlatır. |
| [Viewer](viewer#constructor_2)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Yeni bir [`Viewer`](../viewer) sınıfı örneğini başlatır. |
| [Viewer](viewer#constructor_1)(Func&lt;Stream&gt;, ViewerSettings) | Yeni bir [`Viewer`](../viewer) sınıfı örneğini başlatır. |
| [Viewer](viewer#constructor_5)(Stream, bool) | Yeni bir [`Viewer`](../viewer) sınıfı örneğini başlatır. |
| [Viewer](viewer#constructor_6)(Stream, LoadOptions) | Yeni bir [`Viewer`](../viewer) sınıfı örneğini başlatır. |
| [Viewer](viewer#constructor_10)(Stream, ViewerSettings) | Yeni bir [`Viewer`](../viewer) sınıfı örneğini başlatır. |
| [Viewer](viewer#constructor_13)(string, LoadOptions) | Yeni bir [`Viewer`](../viewer) sınıfı örneğini başlatır. |
| [Viewer](viewer#constructor_15)(string, ViewerSettings) | Yeni bir [`Viewer`](../viewer) sınıfı örneğini başlatır. |
| [Viewer](viewer#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) | Yeni bir [`Viewer`](../viewer) sınıfı örneğini başlatır. |
| [Viewer](viewer#constructor_7)(Stream, LoadOptions, bool) | Yeni bir [`Viewer`](../viewer) sınıfı örneğini başlatır. |
| [Viewer](viewer#constructor_8)(Stream, LoadOptions, ViewerSettings) | Yeni bir [`Viewer`](../viewer) sınıfı örneğini başlatır. |
| [Viewer](viewer#constructor_11)(Stream, ViewerSettings, bool) | Yeni bir [`Viewer`](../viewer) sınıfı örneğini başlatır. |
| [Viewer](viewer#constructor_14)(string, LoadOptions, ViewerSettings) | Yeni bir [`Viewer`](../viewer) sınıfı örneğini başlatır. |
| [Viewer](viewer#constructor_9)(Stream, LoadOptions, ViewerSettings, bool) | Yeni bir [`Viewer`](../viewer) sınıfı örneğini başlatır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Dispose](../../groupdocs.viewer/viewer/dispose)() | Dosya akışını ve yönetilen iç kaynakları serbest bırakır. |
| [GetAllFonts](../../groupdocs.viewer/viewer/getallfonts)() | Yüklenen belgelerde kullanılan tüm yazı tiplerini döndürür; belge içinde gömülü olanları ve işletim sisteminde yüklü olup belgede kullanılan sistem yazı tiplerini içerir. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments)() | Belge tarafından içerilen ekleri döndürür. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments_1)(CancellationToken) | Belge tarafından içerilen ekleri döndürür. |
| [GetFileInfo](../../groupdocs.viewer/viewer/getfileinfo)() | Dosya türü ve dosyanın şifreli olup olmadığını gösteren bayrak gibi dosya hakkında bilgileri döndürür. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo)(ViewInfoOptions) | Görünüm ve belgeye özgü bilgileri döndürür. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo_1)(ViewInfoOptions, CancellationToken) | Görünüm ve belgeye özgü bilgileri döndürür. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment)(Attachment, Stream) | Ek dosyasını *destination* akışına kaydeder. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment_1)(Attachment, Stream, CancellationToken) | Ek dosyasını *destination* akışına kaydeder. |
| [Search](../../groupdocs.viewer/viewer/search)(SearchHighlightOptions) | Yüklenen seçeneklere göre yüklü belgede bir metin araması yapar ve bulunursa vurgular. |
| [View](../../groupdocs.viewer/viewer/view#view)(ViewOptions) | Belgenin tüm sayfalarının görünümünü oluşturur. |
| [View](../../groupdocs.viewer/viewer/view#view_2)(ViewOptions, CancellationToken) | Belgenin tüm sayfalarının görünümünü oluşturur. |
| [View](../../groupdocs.viewer/viewer/view#view_1)(ViewOptions, params int[]) | Belgenin belirli sayfalarının görünümünü oluşturur. |
| [View](../../groupdocs.viewer/viewer/view#view_3)(ViewOptions, CancellationToken, params int[]) | Belgenin belirli sayfalarının görünümünü oluşturur. |

### Ayrıca Bakınız

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
