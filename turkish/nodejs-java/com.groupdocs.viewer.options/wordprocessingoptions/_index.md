---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Kelime işlem belgelerini renderleme seçenekleri sağlar."
type: docs
weight: 38
url: /tr/nodejs-java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

Kelime işlem belgelerini renderleme seçenekleri sağlar.

WordProcessingOptions sınıfı, GroupDocs.Viewer bileşeninde kelime işlem belgelerinin renderlenmesi için seçenekler sunar. Kelime işlem dosyalarının renderleme sürecini ve çıktı formatını kontrol etmek için kullanılabilecek ayarları ve parametreleri kapsar. Ayrıntılar için [documentation][].

Örnek kullanım:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WordProcessingOptions()](#WordProcessingOptions--) | WordProcessingOptions sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPageSize()](#getPageSize--) | HTM ve HTML dosyalarının renderlenmesi için sayfa boyutunu alır. |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | HTM ve HTML dosyalarının renderlenmesi için sayfa boyutunu ayarlar. |
| [isRenderTrackedChanges()](#isRenderTrackedChanges--) | İzlenen değişikliklerin (revizyonların) renderlenmesinin etkin olup olmadığını gösterir. |
| [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | İzlenen değişikliklerin (revizyonların) renderlenmesinin etkin olup olmadığını ayarlar. |
| [getLeftMargin()](#getLeftMargin--) | HTML renderleme için sol sayfa kenar boşluğunu alır. |
| [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | HTML renderleme için sol sayfa kenar boşluğunu ayarlar. |
| [getRightMargin()](#getRightMargin--) | HTML renderleme için sağ sayfa kenar boşluğunu alır. |
| [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | HTML renderleme için sağ sayfa kenar boşluğunu ayarlar. |
| [getTopMargin()](#getTopMargin--) | HTML renderleme için üst sayfa kenar boşluğunu alır. |
| [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | HTML renderasyonu için üst sayfa kenar boşluğunu ayarlar. |
| [getBottomMargin()](#getBottomMargin--) | Alt sayfa kenar boşluğu (yalnızca HTML renderasyonu için) |
| [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | HTML renderasyonu için alt sayfa kenar boşluğunu ayarlar. |
| [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | Bu seçenek, Arapça, İbranice, Hint dilleri, Latin temelli veya Kiril temelli yazı sistemlerini render ederken kerning ve diğer OpenType Features'i etkinleştirir. |
| [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | Bu seçenek, Arapça, İbranice, Hint dilleri, Latin temelli veya Kiril temelli yazı sistemlerini render ederken kerning ve diğer OpenType Features'i etkinleştirir. |
| [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | HTML veya PDF'ye render ederken içindekiler tablosu gezinmesinin devre dışı bırakılıp bırakılmayacağını gösterir. |
| [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | HTML veya PDF'ye render ederken içindekiler tablosu gezinmesinin devre dışı bırakılıp bırakılmayacağını ayarlar. |
| [isUpdateFields()](#isUpdateFields--) | Giriş WordProcessing belgesini HTML, PDF, PNG veya JPEG çıktı formatlarına kaydetmeden önce belirli türdeki alanların güncellenip güncellenmeyeceğini belirleyen bir değeri alır. |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | Giriş WordProcessing belgesini HTML, PDF, PNG veya JPEG çıktı formatlarına kaydetmeden önce belirli türdeki alanların güncellenip güncellenmeyeceğini belirleyen bir değeri ayarlar. |
| [equals(Object o)](#equals-java.lang.Object-) | Seçeneklerin değişip değişmediğini kontrol edin. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


WordProcessingOptions sınıfının yeni bir örneğini başlatır. Kelime işlem belgelerinin render edilmesi için seçenekler içerir. Ayrıntılar için [documentation][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


HTM ve HTML dosyalarının renderlenmesi için sayfa boyutunu alır.

Varsayılan sayfa boyutu kullanıldığında, bazı içerikler sayfa çerçevesine sığmayabilir. İçeriği sığdırmak için A3 gibi daha büyük bir sayfa boyutu ayarlayabilirsiniz; bunu [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3) kullanarak yapabilirsiniz.

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


HTM ve HTML dosyalarının renderlenmesi için sayfa boyutunu ayarlar.

Varsayılan sayfa boyutu kullanıldığında, bazı içerikler sayfa çerçevesine sığmayabilir. İçeriği sığdırmak için A3 gibi daha büyük bir sayfa boyutu ayarlayabilirsiniz; bunu [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3) kullanarak yapabilirsiniz.

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Çıktı sayfasının boyutu. |

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


İzlenen değişikliklerin (revizyonların) renderlenmesinin etkin olup olmadığını gösterir.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Returns:**
boolean -  true  izlenen değişikliklerin render edilmesi etkinse,  false  aksi takdirde.
### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


İzlenen değişikliklerin (revizyonların) renderlenmesinin etkin olup olmadığını ayarlar.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | true  izlenen değişikliklerin render edilmesini etkinleştirmek için,  false  devre dışı bırakmak için. |

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


HTML renderleme için sol sayfa kenar boşluğunu alır.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - sol sayfa kenar boşluğu değeri.
### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


HTML renderleme için sol sayfa kenar boşluğunu ayarlar.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| leftMargin | java.lang.Double | Ayarlanacak sol sayfa kenar boşluğu değeri. |

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


HTML renderleme için sağ sayfa kenar boşluğunu alır.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - sağ sayfa kenar boşluğu değeri.
### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


HTML renderleme için sağ sayfa kenar boşluğunu ayarlar.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rightMargin | java.lang.Double | Ayarlanacak sağ sayfa kenar boşluğu değeri. |

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


HTML renderleme için üst sayfa kenar boşluğunu alır.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - üst sayfa kenar boşluğu.
### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


HTML renderasyonu için üst sayfa kenar boşluğunu ayarlar.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| topMargin | java.lang.Double | Ayarlanacak üst sayfa kenar boşluğu. |

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


Alt sayfa kenar boşluğu (yalnızca HTML renderasyonu için)

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - alt sayfa kenar boşluğu.
### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


HTML renderasyonu için alt sayfa kenar boşluğunu ayarlar.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bottomMargin | java.lang.Double | Ayarlanacak alt sayfa kenar boşluğu. |

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


Bu seçenek, Arapça, İbranice, Hint dilleri, Latin temelli veya Kiril temelli yazı sistemlerini render ederken kerning ve diğer OpenType Features'i etkinleştirir.

**Returns:**
boolean - True  OpenType özellikleri etkinse, false  aksi takdirde.
### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


Bu seçenek, Arapça, İbranice, Hint dilleri, Latin temelli veya Kiril temelli yazı sistemlerini render ederken kerning ve diğer OpenType Features'i etkinleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| enableOpenTypeFeatures | boolean | OpenType özelliklerini etkinleştirmek için true, aksi takdirde false. |

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


HTML veya PDF'ye render ederken içindekiler tablosu gezinmesinin devre dışı bırakılıp bırakılmayacağını gösterir. Bu seçenek true olarak ayarlandığında, HTML render'ı için içindekiler tablosundaki göreceli bağlantılar span etiketleriyle değiştirilecek, işlevsellik kaldırılacak ancak görsel görünüm korunacaktır. PDF render'ı için ise içindekiler tablosu bağlantısız düz metin olarak render edilecektir.

**Returns:**
boolean - İçindekiler tablosu gezinmesi devre dışı bırakılmışsa true; aksi takdirde false.
### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


HTML veya PDF'ye render ederken içindekiler tablosu gezinmesinin devre dışı bırakılıp bırakılmayacağını ayarlar. Bu seçenek true olarak ayarlandığında, HTML render'ı için içindekiler tablosundaki göreceli bağlantılar span etiketleriyle değiştirilecek, işlevsellik kaldırılacak ancak görsel görünüm korunacaktır. PDF render'ı için ise içindekiler tablosu bağlantısız düz metin olarak render edilecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| unlinkTableOfContents | boolean | İçindekiler tablosu gezinmesinin devre dışı bırakılıp bırakılmayacağını gösterir. |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Belirli türdeki alanların, giriş WordProcessing belgesini HTML, PDF, PNG veya JPEG çıktı formatlarına kaydetmeden önce güncellenip güncellenmeyeceğini belirleyen bir değer alır. Bu özelliğin varsayılan değeri true \u2014 alanlar kaydetmeden önce güncellenecektir.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


Belirli türdeki alanların, giriş WordProcessing belgesini HTML, PDF, PNG veya JPEG çıktı formatlarına kaydetmeden önce güncellenip güncellenmeyeceğini belirleyen bir değer ayarlar. Bu özelliğin varsayılan değeri true \u2014 alanlar kaydetmeden önce güncellenecektir.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| updateFields | boolean |  |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Seçeneklerin değişip değişmediğini kontrol edin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| o | java.lang.Object | Eşitlik karşılaştırması yapılacak nesne. |

**Returns:**
boolean -  seçenekler belirtilen nesneye eşitse true, aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu nesne için hash kod değerini hesaplar. Hash kod, nesnenin iç durumuna dayanır ve hash haritaları ve hash kümeleri gibi hash tabanlı veri yapılarında kullanılır.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - bu nesne için hash kod değeri.
