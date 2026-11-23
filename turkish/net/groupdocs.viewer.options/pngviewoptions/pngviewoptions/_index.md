---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "PngViewOptionsgroupdocs.viewer.options/pngviewoptions sınıfının bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.options/pngviewoptions/pngviewoptions/
---

## PngViewOptions(CreatePageStream) {#constructor_1}

[`PngViewOptions`](../../pngviewoptions) sınıfının bir örneğini başlatır.

```csharp
public PngViewOptions(CreatePageStream createPageStream)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| createPageStream | CreatePageStream | Çıktı sayfa verilerini yazmak için kullanılan bir akışı oluşturan yöntem. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *createPageStream* null olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png) bakın.

### Ayrıca Bakınız

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

[`PngViewOptions`](../../pngviewoptions) sınıfının bir örneğini başlatır.

```csharp
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
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

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png) bakın.

### Ayrıca Bakınız

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(IPageStreamFactory) {#constructor_3}

[`PngViewOptions`](../../pngviewoptions) sınıfının bir örneğini başlatır.

```csharp
public PngViewOptions(IPageStreamFactory pageStreamFactory)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Çıktı sayfa akışını oluşturma ve serbest bırakma yöntemlerini uygulayan fabrika. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pageStreamFactory* null olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png) bakın.

### Ayrıca Bakınız

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions() {#constructor}

[`PngViewOptions`](../../pngviewoptions) sınıfının bir örneğini başlatır.

```csharp
public PngViewOptions()
```

### Açıklamalar

Bu yapıcı, çıktı dosyaları için dosya yolu biçimi olarak "p_{0}.png" kullanan [`PngViewOptions`](../../pngviewoptions) sınıfının bir örneğini başlatır. Çıktı dosyaları uygulamanın geçerli çalışma dizinine yerleştirilir.

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png) bakın.

### Ayrıca Bakınız

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PngViewOptions(string) {#constructor_4}

[`PngViewOptions`](../../pngviewoptions) sınıfının bir örneğini başlatır.

```csharp
public PngViewOptions(string filePathFormat)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| filePathFormat | String | Dosya yolu biçimi, örnek olarak 'page_{0}.png'. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *filePathFormat* null veya boş olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-png) bakın.

### Ayrıca Bakınız

* class [PngViewOptions](../../pngviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
