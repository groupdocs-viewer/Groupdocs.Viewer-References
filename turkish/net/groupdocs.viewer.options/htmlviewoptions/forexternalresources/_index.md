---
title: "ForExternalResources"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Harici kaynaklarla HTML'ye renderlemek için HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions sınıfının bir örneğini başlatır."
type: docs
weight: 20
url: /tr/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Harici kaynaklarla HTML'ye renderlemek için [`HtmlViewOptions`](../../htmlviewoptions) sınıfının bir örneğini başlatır.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| createPageStream | CreatePageStream | Çıktı sayfa verilerini yazmak için kullanılan akışı oluşturan yöntem. |
| createResourceStream | CreateResourceStream | *createPageStream* yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |
| createResourceUrl | CreateResourceUrl | HTML kaynağı için URL oluşturan yöntem. |

### Dönüş Değeri

Dış kaynaklarla HTML'ye render etmek için [`HtmlViewOptions`](../../htmlviewoptions) sınıfının yeni bir örneği.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *createPageStream* null olduğunda fırlatılır. |
| ArgumentNullException | *createResourceStream* null olduğunda fırlatılır. |
| ArgumentNullException | *createResourceUrl* null olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belgelendirme](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources) adresine bakın.

### Ayrıca Bakınız

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Harici kaynaklarla HTML'ye renderlemek için [`HtmlViewOptions`](../../htmlviewoptions) sınıfının bir örneğini başlatır.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| createPageStream | CreatePageStream | Çıktı sayfa verilerini yazmak için kullanılan akışı oluşturan yöntem. |
| createResourceStream | CreateResourceStream | Çıktı HTML kaynağı verilerini yazmak için kullanılan akışı başlatan yöntem. |
| createResourceUrl | CreateResourceUrl | HTML kaynağı için URL oluşturan yöntem. |
| releasePageStream | ReleasePageStream | *createPageStream* parametresine geçirilen delegeye atanan yöntem tarafından oluşturulan akışı serbest bırakan yöntem. |
| releaseResourceStream | ReleaseResourceStream | *createResourceStream* parametresine geçirilen delegeye atanan yöntem tarafından oluşturulan akışı serbest bırakan yöntem. |

### Dönüş Değeri

Dış kaynaklarla HTML'ye render etmek için [`HtmlViewOptions`](../../htmlviewoptions) sınıfının yeni bir örneği.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *createPageStream* null olduğunda fırlatılır. |
| ArgumentNullException | *createResourceStream* null olduğunda fırlatılır. |
| ArgumentNullException | *createResourceUrl* null olduğunda fırlatılır. |
| ArgumentNullException | *releasePageStream* null olduğunda fırlatılır. |
| ArgumentNullException | *releaseResourceStream* null olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belgelendirme](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources) adresine bakın.

### Ayrıca Bakınız

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

Harici kaynaklarla HTML'ye renderlemek için [`HtmlViewOptions`](../../htmlviewoptions) sınıfının bir örneğini başlatır.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Çıktı sayfa akışını oluşturma ve serbest bırakma yöntemlerini uygulayan fabrika. |
| resourceStreamFactory | IResourceStreamFactory | Kaynak URL'si oluşturma, çıktı HTML kaynağı akışını örnekleme ve serbest bırakma için gereken yöntemleri uygulayan fabrika. |

### Dönüş Değeri

Dış kaynaklarla HTML'ye render etmek için [`HtmlViewOptions`](../../htmlviewoptions) sınıfının yeni bir örneği.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *pageStreamFactory* null olduğunda fırlatılır. |
| ArgumentNullException | *resourceStreamFactory* null olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belgelendirme](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources) adresine bakın.

### Ayrıca Bakınız

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

[`HtmlViewOptions`](../../htmlviewoptions) sınıfının bir örneğini başlatır.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Açıklamalar

Bu yapıcı, [`HtmlViewOptions`](../../htmlviewoptions) sınıfının bir örneğini başlatır.

* with "p_{0}.html" as file path format for the output HTML files
* with "p_{0}_{1}" as file path format for the output HTML-resource files
* with "p_{0}_{1}" as URL format for HTML-resources

Çıktı dosyaları uygulamanın geçerli çalışma dizinine yerleştirilecektir.

Kod örneği için, [belgelendirme](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources) adresine bakın.

### Ayrıca Bakınız

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

[`HtmlViewOptions`](../../htmlviewoptions) sınıfının bir örneğini başlatır.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| filePathFormat | String | Dosya yolu biçimi, örn. 'page_{0}.html'. |
| resourceFilePathFormat | String | Kaynak dosya yolu biçimi, örnek olarak 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | Kaynak URL biçimi, örnek olarak 'page_{0}/resource_{1}'. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | *filePathFormat* null veya boş olduğunda fırlatılır. |
| ArgumentException | *resourceFilePathFormat* null veya boş olduğunda fırlatılır. |
| ArgumentException | *resourceUrlFormat* null veya boş olduğunda fırlatılır. |

### Açıklamalar

Kod örneği için, [belgelendirme](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources) adresine bakın.

### Ayrıca Bakınız

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
