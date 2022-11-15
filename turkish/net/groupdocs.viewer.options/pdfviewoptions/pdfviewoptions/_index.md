---
title: PdfViewOptions
second_title: .NET API Başvurusu için GroupDocs.Viewer
description: Yeni örneğini başlatırPdfViewOptionsgroupdocs.viewer.options/pdfviewoptions sınıf.
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.options/pdfviewoptions/pdfviewoptions/
---
## PdfViewOptions(CreateFileStream) {#constructor_1}

Yeni örneğini başlatır[`PdfViewOptions`](../../pdfviewoptions) sınıf.

```csharp
public PdfViewOptions(CreateFileStream createFileStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createFileStream | CreateFileStream | Çıktı dosyası verilerini yazmak için kullanılan akışı başlatan yöntem. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | ne zaman atıldı*createFileStream* boş. |

### Ayrıca bakınız

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* ad alanı [GroupDocs.Viewer.Options](../../pdfviewoptions)
* toplantı [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(CreateFileStream, ReleaseFileStream) {#constructor_2}

Yeni örneğini başlatır[`PdfViewOptions`](../../pdfviewoptions) sınıf.

```csharp
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createFileStream | CreateFileStream | Çıktı dosyası verilerini yazmak için kullanılan akışı başlatan yöntem. |
| releaseFileStream | ReleaseFileStream | Şuraya iletilen temsilciye atanan yöntem tarafından oluşturulan akışı serbest bırakan yöntem:*createFileStream* parametre. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | ne zaman atıldı*createFileStream* boş. |
| ArgumentNullException | ne zaman atıldı*releaseFileStream* boş. |

### Ayrıca bakınız

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* delegate [ReleaseFileStream](../../../groupdocs.viewer.interfaces/releasefilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* ad alanı [GroupDocs.Viewer.Options](../../pdfviewoptions)
* toplantı [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(IFileStreamFactory) {#constructor_3}

Yeni örneğini başlatır[`PdfViewOptions`](../../pdfviewoptions) sınıf.

```csharp
public PdfViewOptions(IFileStreamFactory fileStreamFactory)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fileStreamFactory | IFileStreamFactory | Çıktı dosyası akışı oluşturmak ve serbest bırakmak için yöntemler uygulayan fabrika. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | ne zaman atıldı*fileStreamFactory* boş. |

### Ayrıca bakınız

* interface [IFileStreamFactory](../../../groupdocs.viewer.interfaces/ifilestreamfactory)
* class [PdfViewOptions](../../pdfviewoptions)
* ad alanı [GroupDocs.Viewer.Options](../../pdfviewoptions)
* toplantı [GroupDocs.Viewer](../../../)

---

## PdfViewOptions() {#constructor}

Yeni örneğini başlatır[`PdfViewOptions`](../../pdfviewoptions) sınıf.

```csharp
public PdfViewOptions()
```

### Notlar

Bu yapıcı, yeni örneğini başlatır[`PdfViewOptions`](../../pdfviewoptions) , çıktı dosyası için dosya yolu formatı olarak "output.pdf" ile birlikte. Çıktı dosyası, uygulamanın mevcut çalışma dizinine yerleştirilecektir.

### Ayrıca bakınız

* class [PdfViewOptions](../../pdfviewoptions)
* ad alanı [GroupDocs.Viewer.Options](../../pdfviewoptions)
* toplantı [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(string) {#constructor_4}

Yeni örneğini başlatır[`PdfViewOptions`](../../pdfviewoptions) sınıf.

```csharp
public PdfViewOptions(string outputFilePath)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputFilePath | String | Çıktı PDF dosyasının yolu. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | ne zaman atıldı*outputFilePath* null veya boş. |

### Ayrıca bakınız

* class [PdfViewOptions](../../pdfviewoptions)
* ad alanı [GroupDocs.Viewer.Options](../../pdfviewoptions)
* toplantı [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->