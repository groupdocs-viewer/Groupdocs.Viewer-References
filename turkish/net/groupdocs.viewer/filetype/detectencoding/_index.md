---
title: "DetectEncoding"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Metin TXTgroupdocs.viewer/filetype/txt TSVgroupdocs.viewer/filetype/tsv ve CSVgroupdocs.viewer/filetype/csv dosyalarının kodlamasını yol üzerinden tespit etmeye çalışır."
type: docs
weight: 2060
url: /tr/net/groupdocs.viewer/filetype/detectencoding/
---

## DetectEncoding(string) {#detectencoding_1}

Metin [`TXT`](../txt), [`TSV`](../tsv) ve [`CSV`](../csv) dosyalarının kodlamasını yol üzerinden tespit etmeye çalışır.

```csharp
public static Encoding DetectEncoding(string filePath)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| filePath | String | Dosya adı veya dosya yolu. |

### Dönüş Değeri

Bir dosyanın kodlamasını tespit edemediğinde kodlama veya null.

### Örnekler

Bu örnek, metin dosyası kodlamasını nasıl tespit edeceğini gösterir.

```csharp
Encoding encoding = FileType.DetectEncoding("message.txt");
```

### Ayrıca Bakınız

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## DetectEncoding(Stream) {#detectencoding}

Metin [`TXT`](../txt), [`TSV`](../tsv) ve [`CSV`](../csv) dosyasının kodlamasını akış üzerinden tespit etmeye çalışır.

```csharp
public static Encoding DetectEncoding(Stream stream)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| akış | Akış | Dosya akışı. |

### Dönüş Değeri

Bir dosyanın kodlamasını tespit edemediğinde kodlama veya null.

### Örnekler

Bu örnek, metin dosyası kodlamasını nasıl tespit edeceğini gösterir.

```csharp
Stream stream = File.OpenRead("message.txt");
Encoding encoding = FileType.DetectEncoding(stream);
```

### Ayrıca Bakınız

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
