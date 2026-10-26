---
title: "LoadOptions"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Dosyayı açmak için kullanılan seçenekleri içerir. Ayrıntılar için bu sayfaya https//docs.groupdocs.com/viewer/net/loading/ ve alt sayfalara bakın."
type: docs
weight: 360
url: /tr/net/groupdocs.viewer.options/loadoptions/
---

## LoadOptions class

Dosyayı açmak için kullanılan seçenekleri içerir. Ayrıntılar için bu [sayfaya](https://docs.groupdocs.com/viewer/net/loading/) ve alt bölümlerine bakın.

```csharp
public class LoadOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | [`LoadOptions`](../loadoptions) sınıfının bir örneğini başlatır. |
| [LoadOptions](loadoptions#constructor_1)(FileType) | [`LoadOptions`](../loadoptions) sınıfının bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [DetectEncoding](../../groupdocs.viewer.options/loadoptions/detectencoding) { get; set; } | [`TXT`](../../groupdocs.viewer/filetype/txt), [`CSV`](../../groupdocs.viewer/filetype/csv) ve [`TSV`](../../groupdocs.viewer/filetype/tsv) dosyaları için kodlama algılamayı etkinleştirir. |
| [Encoding](../../groupdocs.viewer.options/loadoptions/encoding) { get; set; } | [`CSV`](../../groupdocs.viewer/filetype/csv), [`TXT`](../../groupdocs.viewer/filetype/txt) ve [`MSG`](../../groupdocs.viewer/filetype/msg) gibi metin tabanlı dosyaları veya e-posta mesajlarını açarken kullanılan kodlamayı ayarlar. Varsayılan değer UTF8. |
| [FileType](../../groupdocs.viewer.options/loadoptions/filetype) { get; set; } | Açılacak dosyanın türünü ayarlar. |
| [Password](../../groupdocs.viewer.options/loadoptions/password) { get; set; } | Şifreli dosyayı açmak için şifreyi ayarlar. |
| [ResourceLoadingTimeout](../../groupdocs.viewer.options/loadoptions/resourceloadingtimeout) { get; set; } | Harici kaynakları yüklemek için zaman aşımını ayarlar. |
| [SkipExternalResources](../../groupdocs.viewer.options/loadoptions/skipexternalresources) { get; set; } | [`WhitelistedResources`](./whitelistedresources) dışındaki tüm harici kaynakların (örneğin görüntüler) yüklenmesini devre dışı bırakır. |
| [TryRepair](../../groupdocs.viewer.options/loadoptions/tryrepair) { get; set; } | Etkinleştirildiğinde GroupDocs.Viewer, PDF belgelerindeki yapısal bozulmaları onarmaya çalışır. Varsayılan değer `false`. |
| [WhitelistedResources](../../groupdocs.viewer.options/loadoptions/whitelistedresources) { get; set; } | [`SkipExternalResources`](./skipexternalresources) `true` olarak ayarlandığında yüklenmesi gereken harici kaynaklara karşılık gelen URL parçacıklarının listesi. |

### Ayrıca Bakınız

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
