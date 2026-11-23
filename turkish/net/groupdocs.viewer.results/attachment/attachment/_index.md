---
title: "Attachment"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Attachmentgroupdocs.viewer.results/attachment sınıfının yeni bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.results/attachment/attachment/
---

## Attachment() {#constructor}

[`Attachment`](../../attachment) sınıfının yeni bir örneğini başlatır.

```csharp
public Attachment()
```

### Ayrıca Bakınız

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string) {#constructor_1}

[`Attachment`](../../attachment) sınıfının yeni bir örneğini başlatır.

```csharp
public Attachment(string fileName, string filePath)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| fileName | String | Ek dosya adı. |
| filePath | String | Ek'in göreli yolu, ör. klasör/dosya.docx veya dosya adı; dosya bir arşivin kökünde, e-posta mesajında veya veri dosyasında bulunduğunda. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *fileName* null veya boş olduğunda fırlatılır. |
| ArgumentException | *filePath* null veya boş olduğunda atılır. |

### Ayrıca Bakınız

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, long) {#constructor_3}

[`Attachment`](../../attachment) sınıfının yeni bir örneğini başlatır.

```csharp
public Attachment(string id, string fileName, string filePath, long size)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| id | String | Ek dosyasının (tek dosya bağlamında) benzersiz tanımlayıcısı. |
| fileName | String | Ek dosya adı. |
| filePath | String | Ek'in göreli yolu, ör. klasör/dosya.docx veya dosya adı; dosya bir arşivin kökünde, e-posta mesajında veya veri dosyasında bulunduğunda. |
| boyut | Int64 | Ek dosya boyutu (bayt cinsinden). |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *id* null veya boş olduğunda fırlatılır. |
| ArgumentException | *fileName* null veya boş olduğunda fırlatılır. |
| ArgumentException | *filePath* null veya boş olduğunda atılır. |

### Ayrıca Bakınız

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, FileType, long) {#constructor_2}

[`Attachment`](../../attachment) sınıfının yeni bir örneğini başlatır.

```csharp
public Attachment(string id, string fileName, string filePath, FileType fileType, long size)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| id | String | Ek dosyasının (tek dosya bağlamında) benzersiz tanımlayıcısı. |
| fileName | String | Ek dosya adı. |
| filePath | String | Ek'in göreli yolu, ör. klasör/dosya.docx veya dosya adı; dosya bir arşivin kökünde, e-posta mesajında veya veri dosyasında bulunduğunda. |
| fileType | FileType | Ek dosya türü. |
| boyut | Int64 | Ek dosya boyutu (bayt cinsinden). |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *id* null veya boş olduğunda fırlatılır. |
| ArgumentException | *fileName* null veya boş olduğunda fırlatılır. |
| ArgumentException | *filePath* null veya boş olduğunda atılır. |
| ArgumentNullException | *fileType* null olduğunda fırlatılır. |

### Ayrıca Bakınız

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
