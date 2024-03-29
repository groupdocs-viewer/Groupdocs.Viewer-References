---
title: LoadOptions
second_title: .NET API Başvurusu için GroupDocs.Viewer
description: Dosyayı açmak için kullanılan seçenekleri sağlar.
type: docs
weight: 370
url: /tr/net/groupdocs.viewer.options/loadoptions/
---
## LoadOptions class

Dosyayı açmak için kullanılan seçenekleri sağlar.

```csharp
public class LoadOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Yeni örneğini başlatır[`LoadOptions`](../loadoptions) sınıf. |
| [LoadOptions](loadoptions#constructor_1)(FileType) | Yeni örneğini başlatır[`LoadOptions`](../loadoptions) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [DetectEncoding](../../groupdocs.viewer.options/loadoptions/detectencoding) { get; set; } | Bu seçenek etkinleştirir[`TXT`](../../groupdocs.viewer/filetype/txt) ,[`TSV`](../../groupdocs.viewer/filetype/tsv) , Ve[`CSV`](../../groupdocs.viewer/filetype/csv)dosyalar kodlama algılama. Kodlamanın varsayılan olarak algılanamaması durumunda[`Encoding`](./encoding) kullanılır. |
| [Encoding](../../groupdocs.viewer.options/loadoptions/encoding) { get; set; } | Metin tabanlı dosyaları veya gibi e-posta mesajlarını açarken kullanılan kodlama[`CSV`](../../groupdocs.viewer/filetype/csv) , [`TXT`](../../groupdocs.viewer/filetype/txt) , ve[`MSG`](../../groupdocs.viewer/filetype/msg) . Varsayılan değer:UTF8 . |
| [FileType](../../groupdocs.viewer.options/loadoptions/filetype) { get; set; } | Açılacak dosyanın türü. |
| [Password](../../groupdocs.viewer.options/loadoptions/password) { get; set; } | Şifrelenmiş dosyayı açmak için kullanılan parola. |
| [ResourceLoadingTimeout](../../groupdocs.viewer.options/loadoptions/resourceloadingtimeout) { get; set; } | Harici kaynaklar, örneğin grafik yükleme zaman aşımı. Varsayılan değer 30 saniyedir. Bu seçenek, harici kaynaklar içeren Kelime İşleme belgeleri için desteklenir. |

### Ayrıca bakınız

* ad alanı [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* toplantı [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
