---
title: ForExternalResources
second_title: .NET API Başvurusu için GroupDocs.Viewer
description: Yeni örneğini başlatırHtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions harici kaynaklarla HTMLye dönüştürmek için sınıf.
type: docs
weight: 20
url: /tr/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---
## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Yeni örneğini başlatır[`HtmlViewOptions`](../../htmlviewoptions) harici kaynaklarla HTML'ye dönüştürmek için sınıf.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createPageStream | CreatePageStream | Çıkış sayfası verilerini yazmak için kullanılan akışı başlatan yöntem. |
| createResourceStream | CreateResourceStream | Tarafından oluşturulan akışı serbest bırakan yöntem*createPageStream* yöntem. |
| createResourceUrl | CreateResourceUrl | HTML kaynağı için URL oluşturan yöntem. |

### Geri dönüş değeri

Yeni örneği[`HtmlViewOptions`](../../htmlviewoptions) harici kaynaklarla HTML'ye dönüştürmek için sınıf.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | ne zaman atıldı*createPageStream* boş. |
| ArgumentNullException | ne zaman atıldı*createResourceStream* boş. |
| ArgumentNullException | ne zaman atıldı*createResourceUrl* boş. |

### Ayrıca bakınız

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* ad alanı [GroupDocs.Viewer.Options](../../htmlviewoptions)
* toplantı [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Yeni örneğini başlatır[`HtmlViewOptions`](../../htmlviewoptions) harici kaynaklarla HTML'ye dönüştürmek için sınıf.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createPageStream | CreatePageStream | Çıkış sayfası verilerini yazmak için kullanılan akışı başlatan yöntem. |
| createResourceStream | CreateResourceStream | Çıktı HTML kaynak verilerini yazmak için kullanılan akışı başlatan yöntem. |
| createResourceUrl | CreateResourceUrl | HTML kaynağı için URL oluşturan yöntem. |
| releasePageStream | ReleasePageStream | Şuraya iletilen temsilciye atanan yöntem tarafından oluşturulan akışı serbest bırakan yöntem:*createPageStream* parametre. |
| releaseResourceStream | ReleaseResourceStream | Şuraya iletilen temsilciye atanan yöntem tarafından oluşturulan akışı serbest bırakan yöntem:*createResourceStream* parametre. |

### Geri dönüş değeri

Yeni örneği[`HtmlViewOptions`](../../htmlviewoptions) harici kaynaklarla HTML'ye dönüştürmek için sınıf.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | ne zaman atıldı*createPageStream* boş. |
| ArgumentNullException | ne zaman atıldı*createResourceStream* boş. |
| ArgumentNullException | ne zaman atıldı*createResourceUrl* boş. |
| ArgumentNullException | ne zaman atıldı*releasePageStream* boş. |
| ArgumentNullException | ne zaman atıldı*releaseResourceStream* boş. |

### Ayrıca bakınız

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* ad alanı [GroupDocs.Viewer.Options](../../htmlviewoptions)
* toplantı [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

Yeni örneğini başlatır[`HtmlViewOptions`](../../htmlviewoptions) harici kaynaklarla HTML'ye dönüştürmek için sınıf.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | Çıktı sayfası akışı oluşturmak ve serbest bırakmak için yöntemler uygulayan fabrika. |
| resourceStreamFactory | IResourceStreamFactory | Kaynak URL'si oluşturmak, çıktı HTML kaynak akışını başlatmak ve serbest bırakmak için gerekli yöntemleri uygulayan fabrika. |

### Geri dönüş değeri

Yeni örneği[`HtmlViewOptions`](../../htmlviewoptions) harici kaynaklarla HTML'ye dönüştürmek için sınıf.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | ne zaman atıldı*pageStreamFactory* boş. |
| ArgumentNullException | ne zaman atıldı*resourceStreamFactory* boş. |

### Ayrıca bakınız

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* ad alanı [GroupDocs.Viewer.Options](../../htmlviewoptions)
* toplantı [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Yeni örneğini başlatır[`HtmlViewOptions`](../../htmlviewoptions) sınıf.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Notlar

Bu yapıcı, yeni örneğini başlatır[`HtmlViewOptions`](../../htmlviewoptions) - çıktı HTML dosyaları için dosya yolu formatı olarak "p_{0}.html" ile; - çıktı HTML kaynak dosyaları için dosya yolu formatı olarak "p_{0}_{1}" ile; - " ile HTML kaynakları için URL biçimi olarak p_{0}_{1}"; Çıktı dosyaları, uygulamanın mevcut çalışma dizinine yerleştirilecektir.

### Ayrıca bakınız

* class [HtmlViewOptions](../../htmlviewoptions)
* ad alanı [GroupDocs.Viewer.Options](../../htmlviewoptions)
* toplantı [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Yeni örneğini başlatır[`HtmlViewOptions`](../../htmlviewoptions) sınıf.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePathFormat | String | Dosya yolu biçimi, örneğin 'page_{0}.html'. |
| resourceFilePathFormat | String | Kaynak dosya yolu biçimi, örneğin 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | Kaynak URL biçimi, örneğin 'page_{0}/resource_{1}'. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentException | ne zaman atıldı*filePathFormat* null veya boş. |
| ArgumentException | ne zaman atıldı*resourceFilePathFormat* null veya boş. |
| ArgumentException | ne zaman atıldı*resourceUrlFormat* null veya boş. |

### Ayrıca bakınız

* class [HtmlViewOptions](../../htmlviewoptions)
* ad alanı [GroupDocs.Viewer.Options](../../htmlviewoptions)
* toplantı [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
