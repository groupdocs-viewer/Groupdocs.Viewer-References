---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "PdfViewOptionsgroupdocs.viewer.options/pdfviewoptions sınıfının bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.options/pdfviewoptions/pdfviewoptions/
---

## PdfViewOptions(CreateFileStream) {#constructor_1}

[`PdfViewOptions`](../../pdfviewoptions) sınıfının bir örneğini başlatır.

```csharp
public PdfViewOptions(CreateFileStream createFileStream)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| createFileStream | CreateFileStream | Çıktı dosyası verilerini yazmak için kullanılan stream'i örnekleyen yöntem. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *createFileStream* null olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belge](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) sayfasına bakın.

### Ayrıca Bakınız

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(CreateFileStream, ReleaseFileStream) {#constructor_2}

[`PdfViewOptions`](../../pdfviewoptions) sınıfının bir örneğini başlatır.

```csharp
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| createFileStream | CreateFileStream | Çıktı dosyası verilerini yazmak için kullanılan stream'i örnekleyen yöntem. |
| releaseFileStream | ReleaseFileStream | *createFileStream* parametresine geçirilen delegeye atanan yöntem tarafından oluşturulan stream'i serbest bırakan yöntem. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *createFileStream* null olduğunda fırlatılır. |
| ArgumentNullException | *releaseFileStream* null olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belge](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) sayfasına bakın.

### Ayrıca Bakınız

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* delegate [ReleaseFileStream](../../../groupdocs.viewer.interfaces/releasefilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(IFileStreamFactory) {#constructor_3}

[`PdfViewOptions`](../../pdfviewoptions) sınıfının bir örneğini başlatır.

```csharp
public PdfViewOptions(IFileStreamFactory fileStreamFactory)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| fileStreamFactory | IFileStreamFactory | Çıktı dosya akışını oluşturma ve serbest bırakma yöntemlerini uygulayan fabrika. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *fileStreamFactory* null olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belge](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) sayfasına bakın.

### Ayrıca Bakınız

* interface [IFileStreamFactory](../../../groupdocs.viewer.interfaces/ifilestreamfactory)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions() {#constructor}

[`PdfViewOptions`](../../pdfviewoptions) sınıfının bir örneğini başlatır.

```csharp
public PdfViewOptions()
```

### Açıklamalar

Bu yapıcı, çıktı dosyası için dosya yolu formatı olarak "output.pdf" ile [`PdfViewOptions`](../../pdfviewoptions) bir örnek başlatır. Çıktı dosyası, uygulamanın geçerli çalışma dizinine yerleştirilecektir.

Kod örneği için, [belge](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) sayfasına bakın.

### Ayrıca Bakınız

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(string) {#constructor_4}

[`PdfViewOptions`](../../pdfviewoptions) sınıfının bir örneğini başlatır.

```csharp
public PdfViewOptions(string outputFilePath)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| outputFilePath | String | Çıktı PDF dosyasının yolu. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *outputFilePath* null ya da boş olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belge](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) sayfasına bakın.

### Ayrıca Bakınız

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
