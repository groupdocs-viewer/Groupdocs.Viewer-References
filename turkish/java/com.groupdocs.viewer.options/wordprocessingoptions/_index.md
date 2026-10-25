---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Kelime işlem belgelerini işlemek için seçenekler sağlar."
type: docs
weight: 38
url: /tr/java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

Kelime işlem belgelerini işlemek için seçenekler sağlar.


WordProcessingOptions sınıfı, kelime işlem belgelerinin oluşturulması için seçenekler sağlar
GroupDocs.Viewer bileşeninde. Kullanılabilecek ayarları ve parametreleri kapsar
kelime işlem dosyalarının oluşturma sürecini ve çıktı formatını kontrol etmek için.
Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/net/render-word-documents/) bakın.


Örnek kullanım:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [WordProcessingOptions()](#WordProcessingOptions--) | Yeni bir örnek başlatır |
WordProcessingOptions
sınıf.
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | HTM ve HTML dosyalarının oluşturulması için sayfa boyutunu alır. |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | HTM ve HTML dosyalarının oluşturulması için sayfa boyutunu ayarlar. |
|
|  | [isRenderTrackedChanges()](#isRenderTrackedChanges--) | İzlenen değişikliklerin (revizyonların) oluşturulmasının etkin olup olmadığını gösterir. |
|
|  | [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | İzlenen değişikliklerin (revizyonların) oluşturulmasının etkin olup olmadığını ayarlar. |
|
|  | [getLeftMargin()](#getLeftMargin--) | HTML oluşturulması için sol sayfa kenar boşluğunu alır. |
|
|  | [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | HTML oluşturulması için sol sayfa kenar boşluğunu ayarlar. |
|
|  | [getRightMargin()](#getRightMargin--) | HTML oluşturulması için sağ sayfa kenar boşluğunu alır. |
|
|  | [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | HTML oluşturulması için sağ sayfa kenar boşluğunu ayarlar. |
|
|  | [getTopMargin()](#getTopMargin--) | HTML oluşturulması için üst sayfa kenar boşluğunu alır. |
|
|  | [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | HTML oluşturulması için üst sayfa kenar boşluğunu ayarlar. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Alt sayfa kenar boşluğu (yalnızca HTML oluşturulması için) |
|
|  | [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | HTML oluşturulması için alt sayfa kenar boşluğunu ayarlar. |
|
|  | [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | Bu seçenek, Arapça, İbranice, Hint dilleri, Latin temelli veya Kiril temelli yazı tipleri oluşturulurken kerning ve diğer OpenType özelliklerini etkinleştirir. |
|
|  | [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | Bu seçenek, Arapça, İbranice, Hint dilleri, Latin temelli veya Kiril temelli yazı tipleri oluşturulurken kerning ve diğer OpenType özelliklerini etkinleştirir. |
|
|  | [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | HTML veya PDF oluşturulurken içindekiler tablosu gezinmesinin devre dışı bırakılıp bırakılmayacağını gösterir. |
|
|  | [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | HTML veya PDF'ye render edilirken içindekiler tablosu gezinmesinin devre dışı bırakılıp bırakılmayacağını ayarlar. |
|
|  | [isUpdateFields()](#isUpdateFields--) | Girdi WordProcessing belgesini HTML, PDF, PNG veya JPEG çıktı formatlarına kaydetmeden önce belirli türdeki alanların güncellenip güncellenmeyeceğini belirleyen bir değeri alır. |
|
|  | [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | Girdi WordProcessing belgesini HTML, PDF, PNG veya JPEG çıktı formatlarına kaydetmeden önce belirli türdeki alanların güncellenip güncellenmeyeceğini belirleyen bir değeri ayarlar. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Oluşturulan görüntüler için inç başına nokta cinsinden yatay çözünürlüğü alır. |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | Oluşturulan görüntüler için inç başına nokta cinsinden yatay çözünürlüğü ayarlar. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Oluşturulan görüntüler için inç başına nokta cinsinden dikey çözünürlüğü alır. |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | Oluşturulan görüntüler için inç başına nokta cinsinden dikey çözünürlüğü ayarlar. |
|
|  | [getPageNumberLocation()](#getPageNumberLocation--) | Yüklenen WordProcessing belgesine zorunlu olarak sayfa numaralandırması uygulamaya izin verir. |
|
|  | [setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)](#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-) | Yüklenen WordProcessing belgesine zorunlu olarak sayfa numaralandırması uygulamaya izin verir. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Seçeneklerin değişip değişmediğini kontrol edin. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


Yeni bir örnek başlatır
WordProcessingOptions
sınıf.
Word processing belgelerinin render edilmesi için seçenekler içerir. Ayrıntılar için [belgelere](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes) bakın.


### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


HTM ve HTML dosyalarının oluşturulması için sayfa boyutunu alır.


Varsayılan sayfa boyutu kullanıldığında, bazı içerikler sayfa çerçevesine sığmayabilir.
İçeriği sığdırmak için, [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3) kullanarak A3 gibi daha büyük bir sayfa boyutu ayarlayabilirsiniz.


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.

### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


HTM ve HTML dosyalarının oluşturulması için sayfa boyutunu ayarlar.


Varsayılan sayfa boyutu kullanıldığında, bazı içerikler sayfa çerçevesine sığmayabilir.
İçeriği sığdırmak için, [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3) kullanarak A3 gibi daha büyük bir sayfa boyutu ayarlayabilirsiniz.


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Çıktı sayfasının boyutu. |
|

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


İzlenen değişikliklerin (revizyonların) oluşturulmasının etkin olup olmadığını gösterir.
Ayrıntılar için [belgelere](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes) bakın.


**Returns:**
boolean -  true  izlenen değişikliklerin render edilmesi etkinse,  false  aksi takdirde.

### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


İzlenen değişikliklerin (revizyonların) oluşturulmasının etkin olup olmadığını ayarlar.
Ayrıntılar için [belgelere](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  izlenen değişikliklerin render edilmesini etkinleştirmek için,  false  devre dışı bırakmak için. |
|

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


HTML oluşturulması için sol sayfa kenar boşluğunu alır.
Ayrıntılar için [belgelere](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) bakın.


**Returns:**
java.lang.Double - sol sayfa kenar boşluğu değeri.

### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


HTML oluşturulması için sol sayfa kenar boşluğunu ayarlar.
Ayrıntılar için [belgelere](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | leftMargin | java.lang.Double | Ayarlanacak sol sayfa kenar boşluğu değeri. |
|

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


HTML oluşturulması için sağ sayfa kenar boşluğunu alır.
Ayrıntılar için [belgelere](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) bakın.


**Returns:**
java.lang.Double - sağ sayfa kenar boşluğu değeri.

### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


HTML oluşturulması için sağ sayfa kenar boşluğunu ayarlar.
Ayrıntılar için [belgelere](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | rightMargin | java.lang.Double | Ayarlanacak sağ sayfa kenar boşluğu değeri. |
|

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


HTML oluşturulması için üst sayfa kenar boşluğunu alır.
Ayrıntılar için [belgelere](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) bakın.


**Returns:**
java.lang.Double - üst sayfa kenar boşluğu.

### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


HTML oluşturulması için üst sayfa kenar boşluğunu ayarlar.
Ayrıntılar için [belgelere](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | topMargin | java.lang.Double | Ayarlanacak üst sayfa kenar boşluğu. |
|

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


Alt sayfa kenar boşluğu (yalnızca HTML oluşturulması için)
Ayrıntılar için [belgelere](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) bakın.


**Returns:**
java.lang.Double - alt sayfa kenar boşluğu.

### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


HTML oluşturulması için alt sayfa kenar boşluğunu ayarlar.
Ayrıntılar için [belgelere](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | bottomMargin | java.lang.Double | Ayarlanacak alt sayfa kenar boşluğu. |
|

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


Bu seçenek, Arapça, İbranice, Hint dilleri, Latin temelli veya Kiril temelli yazı tipleri oluşturulurken kerning ve diğer OpenType özelliklerini etkinleştirir.


**Returns:**
boolean - True OpenType özellikleri etkinse, false aksi takdirde.

### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


Bu seçenek, Arapça, İbranice, Hint dilleri, Latin temelli veya Kiril temelli yazı tipleri oluşturulurken kerning ve diğer OpenType özelliklerini etkinleştirir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | enableOpenTypeFeatures | boolean | OpenType özelliklerini etkinleştirmek için true, aksi takdirinde false. |
|

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


HTML veya PDF'ye render edilirken içindekiler tablosu gezinmesinin devre dışı bırakılıp bırakılmayacağını gösterir. Bu seçenek true olarak ayarlandığında, HTML render'ında içindekiler tablosundaki göreceli bağlantılar span etiketleriyle değiştirilir, işlevsellik kaldırılır ancak görsel görünüm korunur. PDF render'ında ise içindekiler tablosu bağlantısız düz metin olarak render edilir.


**Returns:**
boolean - İçindekiler tablosu gezinmesi devre dışı bırakıldıysa true; aksi takdirde false.

### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


HTML veya PDF'ye render edilirken içindekiler tablosu gezinmesinin devre dışı bırakılıp bırakılmayacağını ayarlar. Bu seçenek true olarak ayarlandığında, HTML render'ında içindekiler tablosundaki göreceli bağlantılar span etiketleriyle değiştirilir, işlevsellik kaldırılır ancak görsel görünüm korunur. PDF render'ında ise içindekiler tablosu bağlantısız düz metin olarak render edilir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | unlinkTableOfContents | boolean | İçindekiler tablosu gezinmesinin devre dışı bırakılıp bırakılmayacağını gösterir. |
|

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Giriş WordProcessing belgesini HTML, PDF, PNG veya JPEG çıktı formatlarında kaydetmeden önce belirli tipteki alanların güncellenip güncellenmeyeceğini belirleyen bir değeri alır. Bu özelliğin varsayılan değeri true \\u2014 alanlar kaydetmeden önce güncellenecektir.


Ayrıntılar için [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving) sayfasına bakın.


**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


Giriş WordProcessing belgesini HTML, PDF, PNG veya JPEG çıktı formatlarında kaydetmeden önce belirli tipteki alanların güncellenip güncellenmeyeceğini belirleyen bir değeri ayarlar. Bu özelliğin varsayılan değeri true \\u2014 alanlar kaydetmeden önce güncellenecektir.


Ayrıntılar için [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving) sayfasına bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| updateFields | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


Oluşturulan görüntüler için yatay çözünürlüğü inç başına nokta (dpi) olarak alır. Bu seçenek yalnızca WordProcessing belgeleri PNG veya JPEG formatlarına render edilirken kullanılır.


Varsayılan değer 96 DPI'dir. Minimum olası değer - 72 DPI, maksimum olası değer - 600 DPI.
Kullanıcı tarafından belirtilen değer bu sınırların dışındaysa, minimum veya maksimum olası değer uygulanır.


**Returns:**
int - DPI cinsinden yatay çözünürlük.

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


Oluşturulan görüntüler için yatay çözünürlüğü inç başına nokta (dpi) olarak ayarlar. Bu seçenek yalnızca WordProcessing belgeleri PNG veya JPEG formatlarına render edilirken kullanılır.


Varsayılan değer 96 DPI'dir. Minimum olası değer - 72 DPI, maksimum olası değer - 600 DPI.
Kullanıcı tarafından belirtilen değer bu sınırların dışındaysa, minimum veya maksimum olası değer uygulanır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | horizontalResolution | int | yatay çözünürlük DPI cinsinden. |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


Oluşturulan görüntüler için dikey çözünürlüğü inç başına nokta (dpi) olarak alır. Bu seçenek yalnızca WordProcessing belgeleri PNG veya JPEG formatlarına render edilirken kullanılır.


Varsayılan değer 96 DPI'dir. Minimum olası değer - 72 DPI, maksimum olası değer - 600 DPI.
Kullanıcı tarafından belirtilen değer bu sınırların dışındaysa, minimum veya maksimum olası değer uygulanır.


**Returns:**
int - dikey çözünürlük DPI cinsinden.

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


Oluşturulan görüntüler için dikey çözünürlüğü inç başına nokta (dpi) olarak ayarlar. Bu seçenek yalnızca WordProcessing belgeleri PNG veya JPEG formatlarına render edilirken kullanılır.


Varsayılan değer 96 DPI'dir. Minimum olası değer - 72 DPI, maksimum olası değer - 600 DPI.
Kullanıcı tarafından belirtilen değer bu sınırların dışındaysa, minimum veya maksimum olası değer uygulanır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | verticalResolution | int | dikey çözünürlük DPI cinsinden. |
|

### getPageNumberLocation() {#getPageNumberLocation--}
```
public WordsPageNumberLocation getPageNumberLocation()
```


Yüklenen WordProcessing belgesine zorunlu olarak sayfa numaralandırması uygulamaya izin verir. Varsayılan olarak [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 belge değişmeden kalır.


**Returns:**
[WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) - the page number location.

### setPageNumberLocation(WordsPageNumberLocation pageNumberLocation) {#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-}
```
public void setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)
```


Yüklenen WordProcessing belgesine zorunlu olarak sayfa numaralandırması uygulamaya izin verir. Varsayılan olarak [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 belge değişmeden kalır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pageNumberLocation | [WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) | sayfa numarası konumu. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Seçeneklerin değişip değişmediğini kontrol edin.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | o | java.lang.Object | Eşitlik karşılaştırması için nesne. |
|

**Returns:**
boolean - seçenekler belirtilen nesneye eşitse true, aksi takdirde false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu nesne için karma kod değerini hesaplar. Karma kod, şuna dayanır
nesnenin iç durumu ve karma tabanlı veri yapılarına kullanılır
hash haritaları ve hash kümeleri gibi.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - bu nesne için karma kod değeri.

