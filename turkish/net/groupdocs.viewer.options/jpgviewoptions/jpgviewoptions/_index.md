---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "JpgViewOptionsgroupdocs.viewer.options/jpgviewoptions sınıfının bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.options/jpgviewoptions/jpgviewoptions/
---

## JpgViewOptions(CreatePageStream) {#constructor_1}

[`JpgViewOptions`](../../jpgviewoptions) sınıfının bir örneğini başlatır.

```csharp
public JpgViewOptions(CreatePageStream createPageStream)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| createPageStream | CreatePageStream | Çıktı sayfa verilerini yazmak için kullanılan bir akışı oluşturan yöntem. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *createPageStream* null olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg) bakın.

### Ayrıca Bakınız

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

[`JpgViewOptions`](../../jpgviewoptions) sınıfının bir örneğini başlatır.

```csharp
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| createPageStream | CreatePageStream | Çıktı sayfa verilerini yazmak için kullanılan bir akışı oluşturan yöntem. |
| releasePageStream | ReleasePageStream | *createPageStream* parametresine geçirilen delegeye atanan yöntem tarafından oluşturulan akışı serbest bırakan yöntem. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *createPageStream* null olduğunda fırlatılır. |
| ArgumentNullException | *releasePageStream* null olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg) bakın.

### Ayrıca Bakınız

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(IPageStreamFactory) {#constructor_3}

[`JpgViewOptions`](../../jpgviewoptions) sınıfının bir örneğini başlatır.

```csharp
public JpgViewOptions(IPageStreamFactory pageStreamFactory)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Çıktı sayfa akışını oluşturma ve serbest bırakma yöntemlerini uygulayan fabrika. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pageStreamFactory* null olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg) bakın.

### Ayrıca Bakınız

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions() {#constructor}

[`JpgViewOptions`](../../jpgviewoptions) sınıfının bir örneğini başlatır.

```csharp
public JpgViewOptions()
```

### Açıklamalar

Bu yapıcı, çıktı dosyaları için dosya yolu biçimi olarak \"p_{0}.jpg\" kullanan bir [`JpgViewOptions`](../../jpgviewoptions) örneğini başlatır. Çıktı dosyaları uygulamanın geçerli çalışma dizinine yerleştirilir.

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg) bakın.

### Ayrıca Bakınız

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(string) {#constructor_4}

[`JpgViewOptions`](../../jpgviewoptions) sınıfının bir örneğini başlatır.

```csharp
public JpgViewOptions(string filePathFormat)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| filePathFormat | String | Dosya yolu biçimi örn. 'page_{0}.jpg'. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *filePathFormat* null veya boş olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg) bakın.

### Ayrıca Bakınız

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
