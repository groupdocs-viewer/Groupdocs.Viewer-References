---
title: "ForEmbeddedResources"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Gömülü kaynaklarla HTML'ye render etmek için HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions sınıfının bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/groupdocs.viewer.options/htmlviewoptions/forembeddedresources/
---

## ForEmbeddedResources(CreatePageStream) {#forembeddedresources_1}

Gömülü kaynaklarla HTML'ye render etmek için [`HtmlViewOptions`](../../htmlviewoptions) sınıfının bir örneğini başlatır.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| createPageStream | CreatePageStream | Çıktı sayfa verilerini yazmak için kullanılan akışı oluşturan yöntem. |

### Dönüş Değeri

Gömülü kaynaklarla HTML'ye render etmek için [`HtmlViewOptions`](../../htmlviewoptions) sınıfının yeni bir örneği.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *createPageStream* null olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources) bakın.

### Ayrıca Bakınız

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(CreatePageStream, ReleasePageStream) {#forembeddedresources_2}

Gömülü kaynaklarla HTML'ye render etmek için [`HtmlViewOptions`](../../htmlviewoptions) sınıfının bir örneğini başlatır.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| createPageStream | CreatePageStream | Çıktı sayfa verilerini yazmak için kullanılan akışı oluşturan yöntem. |
| releasePageStream | ReleasePageStream | *createPageStream* parametresine geçirilen delegeye atanan yöntem tarafından oluşturulan akışı serbest bırakan yöntem. |

### Dönüş Değeri

Gömülü kaynaklarla HTML'ye render etmek için [`HtmlViewOptions`](../../htmlviewoptions) sınıfının yeni bir örneği.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *createPageStream* null olduğunda fırlatılır. |
| ArgumentNullException | *releasePageStream* null olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources) bakın.

### Ayrıca Bakınız

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(IPageStreamFactory) {#forembeddedresources_3}

Gömülü kaynaklarla HTML'ye render etmek için [`HtmlViewOptions`](../../htmlviewoptions) sınıfının bir örneğini başlatır.

```csharp
public static HtmlViewOptions ForEmbeddedResources(IPageStreamFactory pageStreamFactory)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Çıktı sayfa akışını oluşturma ve serbest bırakma yöntemlerini uygulayan fabrika. |

### Dönüş Değeri

Gömülü kaynaklarla HTML'ye render etmek için [`HtmlViewOptions`](../../htmlviewoptions) sınıfının yeni bir örneği.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pageStreamFactory* null olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources) bakın.

### Ayrıca Bakınız

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources() {#forembeddedresources}

[`HtmlViewOptions`](../../htmlviewoptions) sınıfının bir örneğini başlatır.

```csharp
public static HtmlViewOptions ForEmbeddedResources()
```

### Açıklamalar

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources) bakın.

### Ayrıca Bakınız

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(string) {#forembeddedresources_4}

[`HtmlViewOptions`](../../htmlviewoptions) sınıfının bir örneğini başlatır.

```csharp
public static HtmlViewOptions ForEmbeddedResources(string filePathFormat)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| filePathFormat | String | Dosya yolu biçimi, örn. 'page_{0}.html'. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *filePathFormat* null veya boş olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belgelere](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources) bakın.

### Ayrıca Bakınız

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
