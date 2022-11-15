---
title: Attachment
second_title: .NET API Başvurusu için GroupDocs.Viewer
description: Yeni örneğini başlatırAttachmentgroupdocs.viewer.results/attachment sınıf.
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.results/attachment/attachment/
---
## Attachment(string, string) {#constructor}

Yeni örneğini başlatır[`Attachment`](../../attachment) sınıf.

```csharp
public Attachment(string fileName, string filePath)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fileName | String | Ek dosya adı. |
| filePath | String | Ek göreli yolu örn.klasör/dosya.docxveya dosya bir arşivin kökünde, e-posta iletisinde veya veri dosyasında bulunduğunda dosya adı. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | ne zaman atıldı*fileName* null veya boş. |
| ArgumentException | ne zaman atıldı*filePath* null veya boş. |

### Ayrıca bakınız

* class [Attachment](../../attachment)
* ad alanı [GroupDocs.Viewer.Results](../../attachment)
* toplantı [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, long) {#constructor_2}

Yeni örneğini başlatır[`Attachment`](../../attachment) sınıf.

```csharp
public Attachment(string id, string fileName, string filePath, long size)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| id | String | Ekin benzersiz (tek dosya bağlamında) tanımlayıcısı. |
| fileName | String | Ek dosya adı. |
| filePath | String | Ek göreli yolu örn.klasör/dosya.docxveya dosya bir arşivin kökünde, e-posta iletisinde veya veri dosyasında bulunduğunda dosya adı. |
| size | Int64 | Bayt cinsinden ek dosya boyutu. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | ne zaman atıldı*id* null veya boş. |
| ArgumentException | ne zaman atıldı*fileName* null veya boş. |
| ArgumentException | ne zaman atıldı*filePath* null veya boş. |

### Ayrıca bakınız

* class [Attachment](../../attachment)
* ad alanı [GroupDocs.Viewer.Results](../../attachment)
* toplantı [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, FileType, long) {#constructor_1}

Yeni örneğini başlatır[`Attachment`](../../attachment) sınıf.

```csharp
public Attachment(string id, string fileName, string filePath, FileType fileType, long size)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| id | String | Ekin benzersiz (tek dosya bağlamında) tanımlayıcısı. |
| fileName | String | Ek dosya adı. |
| filePath | String | Ek göreli yolu örn.klasör/dosya.docxveya dosya bir arşivin kökünde, e-posta iletisinde veya veri dosyasında bulunduğunda dosya adı. |
| fileType | FileType | Ek dosya türü. |
| size | Int64 | Bayt cinsinden ek dosya boyutu. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | ne zaman atıldı*id* null veya boş. |
| ArgumentException | ne zaman atıldı*fileName* null veya boş. |
| ArgumentException | ne zaman atıldı*filePath* null veya boş. |
| ArgumentNullException | ne zaman atıldı*fileType* boş. |

### Ayrıca bakınız

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Attachment](../../attachment)
* ad alanı [GroupDocs.Viewer.Results](../../attachment)
* toplantı [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->