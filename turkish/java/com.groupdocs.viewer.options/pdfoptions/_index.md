---
title: "PdfOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "PDF belgelerini işlemek için seçenekler sağlar."
type: docs
weight: 22
url: /tr/java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

PDF belgelerini işlemek için seçenekler sağlar.


PdfOptions sınıfı, kullanılabilecek çeşitli ayarları ve parametreleri kapsar
GroupDocs.Viewer bileşeninde PDF belgelerinin işlenmesini kontrol etmek için.
Detaylar için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/) adresine bakın.


Örnek kullanım:

````

 PdfOptions options = new PdfOptions();
 options.setDisableCharsGrouping(true);
 options.setRenderTextAsImage(true);
 options.setEnableFontHinting(true);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setPdfOptions(options);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | Yeni bir örnek başlatır |
PdfOptions
sınıf.
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isDisableCopyProtection()](#isDisableCopyProtection--) | HTML'ye işlenirken içerik kopyalama korumasını kapatır. |
|
|  | [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | HTML'ye işlenirken içerik kopyalama korumasını kapatır. |
|
|  | [isRenderTextAsImage()](#isRenderTextAsImage--) | Kaynaktaki metnin HTML'de görüntü olarak işlenip işlenmeyeceğini belirler. |
|
|  | [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Kaynaktaki metnin HTML'de görüntü olarak işlenip işlenmeyeceğini ayarlar. |
|
|  | [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Sayfa işlenirken karakter konumlandırması sırasında maksimum hassasiyeti korumak için karakter gruplandırmanın devre dışı bırakılıp bırakılmadığını kontrol eder. |
|
|  | [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Sayfa işlenirken karakter konumlandırması sırasında maksimum hassasiyeti sağlamak için karakter gruplandırmayı devre dışı bırakma seçeneğini ayarlar. |
|
|  | [isEnableLayeredRendering()](#isEnableLayeredRendering--) | HTML'ye işlenirken metin ve grafiklerin orijinal PDF belgesindeki z-sırasını takip edip etmeyeceğini kontrol eder. |
|
|  | [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | HTML'ye işlenirken metin ve grafiklerin orijinal PDF belgesindeki z-sırasına göre işlenmesini etkinleştirir veya devre dışı bırakır. |
|
|  | [isEnableFontHinting()](#isEnableFontHinting--) | Yazı tipi ipucu (hinting) özelliğinin etkin olup olmadığını belirler. |
|
|  | [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Yazı tipi ipucu (hinting) özelliğini etkinleştirir. |
|
|  | [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Kaynak PDF belgesindeki sayfa boyutu ile aynı piksel boyutunda sayfaların işlenmesini etkinleştirir. |
|
|  | [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Kaynak PDF belgesindeki sayfa boyutu ile aynı piksel boyutunda sayfaların işlenmesini etkinleştirir. |
|
|  | [getImageQuality()](#getImageQuality--) | HTML'ye işlenirken görüntü kaynakları için çıktı görüntü kalitesini alır. |
|
|  | [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | HTML'ye işlenirken görüntü kaynakları için çıktı görüntü kalitesini ayarlar. |
|
|  | [isFixedLayout()](#isFixedLayout--) | PDF sabit bir format olduğundan, tüm öğeler sayfada belirli bir konuma sahiptir. |
|
|  | [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF sabit bir format olduğundan, tüm öğeler sayfada belirli bir konuma sahiptir. |
|
|  | [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Bu seçeneği etkinleştirerek, çıktı HTML belgesindeki her resmi SVG etiketi içinde sarmalayabilir ve çıktı kalitesini artırabilirsiniz. |
|
|  | [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Bu seçeneği etkinleştirerek, çıktı HTML belgesindeki her resmi SVG etiketi içinde sarmalayabilir ve çıktı kalitesini artırabilirsiniz. |
|
|  | [isAnalyzeFonts()](#isAnalyzeFonts--) | Metindeki tüm karakterlerin görüntülenebilmesini sağlamak için gerektiğinde yazı tiplerini değiştirir. |
|
|  | [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Metindeki tüm karakterlerin görüntülenebilmesini sağlamak için gerektiğinde yazı tiplerini değiştirir. |
|
|  | [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Mevcut XPS/OXPS belgesindeki tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırak. |
|
|  | [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Mevcut XPS/OXPS belgesindeki tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırakmak amacıyla bayrağı ayarlayın. |
|
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Yeni bir örnek başlatır
PdfOptions
sınıf.


### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


HTML'ye işlenirken içerik kopyalama korumasını kapatır.


Metin ve görsellerin HTML'ye kopyalanmasına karşı koruma içeren PDF dosyaları işlenirken, GroupDocs.Viewer HTML BODY etiketine bir 'inert' HTML özniteliği ekler.
Bu seçeneğin varsayılan değeri
false
.


Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection) bakın.


**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


HTML'ye işlenirken içerik kopyalama korumasını kapatır.


Metin ve görsellerin HTML'ye kopyalanmasına karşı koruma içeren PDF dosyaları işlenirken, GroupDocs.Viewer HTML BODY etiketine bir 'inert' HTML özniteliği ekler.
Bu seçeneğin varsayılan değeri
false
.


Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Kaynaktaki metnin HTML'de görüntü olarak işlenip işlenmeyeceğini belirler.


Bu seçenek şu şekilde ayarlandığında
true
, metin çıktı HTML'sinde bir görüntü olarak işlenir.
Metnin seçilemez olmasını sağlamak veya karakter render'ını düzeltmek ve HTML'nin PDF gibi görünmesini sağlamak için bu seçeneği etkinleştirin.
Bu seçenek HTML'ye render edilirken desteklenir.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  eğer metin HTML'de bir görüntü olarak işleniyorsa,  false  aksi takdirde.

### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Kaynaktaki metnin HTML'de görüntü olarak işlenip işlenmeyeceğini ayarlar.


Bu seçenek şu şekilde ayarlandığında
true
, metin çıktı HTML'sinde bir görüntü olarak işlenir.
Metnin seçilemez olmasını sağlamak veya karakter render'ını düzeltmek ve HTML'nin PDF gibi görünmesini sağlamak için bu seçeneği etkinleştirin.
Bu seçenek HTML'ye render edilirken desteklenir.


***Note:** The default value is 
false
.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | renderTextAsImage | boolean | true  metni HTML'de bir görüntü olarak işlemek için,  false  aksi takdirde. |
|

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Sayfa işlenirken karakter konumlandırması sırasında maksimum hassasiyeti korumak için karakter gruplandırmanın devre dışı bırakılıp bırakılmadığını kontrol eder.
Bu seçenek etkinleştirildiğinde, karakterler herhangi bir gruplama olmadan işlenir ve bu da en yüksek hassasiyeti sağlar.


***Note:** By default, character grouping is enabled.*
PDF dosyaları dönüştürülürken, GroupDocs.Viewer bireysel karakterleri daha iyi render performansı için kelimelere gruplar. Belgeniz hiyeroglifler veya özel semboller içeriyorsa, daha kesin bir düzen sağlamak için karakter gruplamasını engellemek isteyebilirsiniz. Varsayılan değer false'tur.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping) bakın.


**Returns:**
boolean -  true  eğer karakter gruplaması devre dışı bırakıldıysa,  false  aksi takdirde.

### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Sayfa işlenirken karakter konumlandırması sırasında maksimum hassasiyeti sağlamak için karakter gruplandırmayı devre dışı bırakma seçeneğini ayarlar.
Bu seçenek değeri şu şekilde ayarlayarak etkinleştirildiğinde
true
, karakter gruplaması devre dışı bırakılır ve bu da en yüksek hassasiyeti sağlar.


***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.*
PDF dosyaları dönüştürülürken, GroupDocs.Viewer bireysel karakterleri daha iyi render performansı için kelimelere gruplar. Belgeniz hiyeroglifler veya özel semboller içeriyorsa, daha kesin bir düzen sağlamak için karakter gruplamasını engellemek isteyebilirsiniz. Varsayılan değer false'tur.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  karakter gruplamayı devre dışı bırakmak için,  false  etkinleştirmek için. |
|

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


HTML'ye işlenirken metin ve grafiklerin orijinal PDF belgesindeki z-sırasını takip edip etmeyeceğini kontrol eder.
Bu seçenek etkinleştirildiğinde döndürerek
true
, metin ve grafikler orijinal PDF belgesindeki z-sırasına göre işlenir.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
Varsayılan olarak, GroupDocs.Veiewer metin ve grafikleri HTML'de tek bir katman olarak işler. Bu seçenek, nesneleri kaynak dosyadaki aynı sırayla düzenlemenizi sağlar. Varsayılan değer false.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering) bakın.


**Returns:**
boolean -  true  katmanlı renderleme etkinse,  false  aksi takdirde.

### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


HTML'ye işlenirken metin ve grafiklerin orijinal PDF belgesindeki z-sırasına göre işlenmesini etkinleştirir veya devre dışı bırakır.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
Varsayılan olarak, GroupDocs.Veiewer metin ve grafikleri HTML'de tek bir katman olarak işler. Bu seçenek, nesneleri kaynak dosyadaki aynı sırayla düzenlemenizi sağlar. Varsayılan değer false.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  katmanlı renderlemeyi etkinleştirmek için,  false  devre dışı bırakmak için. |
|

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Yazı tipi ipucu etkin olup olmadığını belirler. Font ipucu, bir kontur yazı tipinin görüntülenmesini ayarlar.
Bu seçenek yalnızca kaynak belgede kullanıldığında TrueType (TTF) yazı tipleri için desteklenir.


***Note:** This option is supported when rendering into PNG or JPG formats.*
Font ipucu, bir kontur yazı tipinin nasıl görüntüleneceğini ayarlar. Yalnızca kaynak belgede kullanılan TTF yazı tipleri için geçerlidir. Bu seçenek PNG veya JPG formatlarına renderleme için kullanılabilir. Varsayılan değer false.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting) bakın.


**Returns:**
boolean -  true  font ipucu etkinse,  false  aksi takdirde.

### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Font ipucunu etkinleştirir. Font ipucu, bir kontur yazı tipinin görüntülenmesini ayarlar ve yalnızca kaynak belgede kullanıldığında TrueType (TTF) yazı tipleri için desteklenir.


***Note:** This option is supported when rendering into PNG or JPG formats.*
Font ipucu, bir kontur yazı tipinin nasıl görüntüleneceğini ayarlar. Yalnızca kaynak belgede kullanılan TTF yazı tipleri için geçerlidir. Bu seçenek PNG veya JPG formatlarına renderleme için kullanılabilir. Varsayılan değer false.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  font ipucunu etkinleştirmek için,  false  devre dışı bırakmak için. |
|

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Kaynak PDF belgesindeki sayfa boyutu ile aynı piksel boyutunda sayfaların işlenmesini etkinleştirir.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
Varsayılan olarak, GroupDocs.Viewer daha iyi renderleme kalitesi için çıktı görüntüsü sayfa boyutunu hesaplar. Bu seçeneği etkinleştirerek çıktı sayfalarının, kaynak PDF belgesinin sayfa boyutu (piksel olarak) ile aynı olmasını sağlayabilirsiniz. Varsayılan değer false.
Bu seçenek PNG veya JPG formatlarına renderleme için kullanılabilir.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages) bakın.


**Returns:**
boolean -  true  seçenek etkinse,  false  aksi takdirde.

### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Kaynak PDF belgesindeki sayfa boyutu ile aynı piksel boyutunda sayfaların işlenmesini etkinleştirir.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
Varsayılan olarak, GroupDocs.Viewer daha iyi renderleme kalitesi için çıktı görüntüsü sayfa boyutunu hesaplar. Bu seçeneği etkinleştirerek çıktı sayfalarının, kaynak PDF belgesinin sayfa boyutu (piksel olarak) ile aynı olmasını sağlayabilirsiniz. Varsayılan değer false.
Bu seçenek PNG veya JPG formatlarına renderleme için kullanılabilir.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | renderOriginalPageSize | boolean | true  orijinal sayfa boyutuyla renderlemeyi etkinleştirmek için,  false  aksi takdirde. |
|

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


HTML'ye renderleme sırasında görüntü kaynakları için çıktı görüntü kalitesini alır. Varsayılan değer Düşük.


Bu seçenek true olarak ayarlandığında, GroupDocs.Viewer HTML çıktısında metni bir görüntü olarak renderler. Bu, metnin seçilemez olmasını sağlar ve karakter renderlemesini iyileştirir, HTML'de PDF benzeri bir görünüm elde eder. Varsayılan değer false.
Bu seçenek HTML'ye renderleme için kullanılabilir.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image) bakın.


**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.

### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


HTML'ye renderleme sırasında görüntü kaynakları için çıktı görüntü kalitesini ayarlar. Varsayılan değer Düşük.


Bu seçenek true olarak ayarlandığında, GroupDocs.Viewer HTML çıktısında metni bir görüntü olarak renderler. Bu, metnin seçilemez olmasını sağlar ve karakter renderlemesini iyileştirir, HTML'de PDF benzeri bir görünüm elde eder. Varsayılan değer false.
Bu seçenek HTML'ye renderleme için kullanılabilir.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | HTML'ye render edildiğinde görüntü kaynakları için çıktı görüntü kalitesi. |
|

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF sabit bir format olduğundan, tüm öğeler sayfada belirli bir konuma sahiptir.
Çıktı HTML'nin kaynak PDF ile aynı görünmesini sağlamak için belgeler varsayılan olarak sabit düzenle HTML'ye render edilir.
Sabit düzenle render edildiğinde çıktı HTML sabit boyuta sahiptir, böylece öğeler pencere boyutundan bağımsız olarak aynı yerde kalır.
Akışkan düzenle HTML'ye render etmek için bu özelliği false olarak ayarlayın.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
PDF ve EPUB belgeleri, kaynak belgenin görünümünü korumak için başlangıçta sabit düzenle HTML'ye render edilir. Bu sabit düzen, tüm HTML öğelerinin belirli bir boyuta sahip bir kapsayıcı içinde kesin konumlara sahip olduğu anlamına gelir. Tarayıcı penceresinin yeniden boyutlandırılması, belgede öğelerin konum ve boyutunu etkilemez.
Bu seçenek yalnızca HTML'ye render edilirken kullanılabilir. Varsayılan değer true'dur. Akışkan düzenle render etmek için bu özelliği false olarak ayarlayın.


Örnek kullanım:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Returns:**
boolean - sabit düzen ise true

### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF sabit bir format olduğundan, tüm öğeler sayfada belirli bir konuma sahiptir.
Çıktı HTML'nin kaynak PDF ile aynı görünmesini sağlamak için belgeler varsayılan olarak sabit düzenle HTML'ye render edilir.
Sabit düzenle render edildiğinde çıktı HTML sabit boyuta sahiptir, böylece öğeler pencere boyutundan bağımsız olarak aynı yerde kalır.
Akışkan düzenle HTML'ye render etmek için bu özelliği false olarak ayarlayın.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
PDF ve EPUB belgeleri, kaynak belgenin görünümünü korumak için başlangıçta sabit düzenle HTML'ye render edilir. Bu sabit düzen, tüm HTML öğelerinin belirli bir boyuta sahip bir kapsayıcı içinde kesin konumlara sahip olduğu anlamına gelir. Tarayıcı penceresinin yeniden boyutlandırılması, belgede öğelerin konum ve boyutunu etkilemez.
Bu seçenek yalnızca HTML'ye render edilirken kullanılabilir. Varsayılan değer true'dur. Akışkan düzenle render etmek için bu özelliği false olarak ayarlayın.


Örnek kullanım:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fixedLayout | boolean | sabit düzen ise true |
|

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Bu seçeneği etkinleştirerek, çıktı HTML belgesindeki her resmi SVG etiketi içinde sarmalayabilir ve çıktı kalitesini artırabilirsiniz.


Bu seçenek, [PDF ve Sayfa Düzeni dosya formatları](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) HTML'ye gömülü ve harici kaynaklarla render edilirken desteklenir.


Varsayılan olarak, PDF ve Sayfa Düzeni dosyalarına render edildiğinde, tüm görüntüler tek bir PNG görüntüsü olarak render edilir. Render edilen PNG görüntüsü, çıktı HTML belgesinin arka planı olarak kullanılır.


Daha fazla bilgi:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Returns:**
boolean -  görüntüler SVG içinde sarılıysa true, aksi takdirde false.

### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Bu seçeneği etkinleştirerek, çıktı HTML belgesindeki her resmi SVG etiketi içinde sarmalayabilir ve çıktı kalitesini artırabilirsiniz.


Bu seçenek, [PDF ve Sayfa Düzeni dosya formatları](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) HTML'ye gömülü ve harici kaynaklarla render edilirken desteklenir.


Varsayılan olarak, PDF ve Sayfa Düzeni dosyalarına render edildiğinde, tüm görüntüler tek bir PNG görüntüsü olarak render edilir. Render edilen PNG görüntüsü, çıktı HTML belgesinin arka planı olarak kullanılır.


Daha fazla bilgi:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | wrapImagesInSvg | boolean | görüntüler SVG içinde sarılacaksa true, aksi takdirde false. |
|

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


Metindeki tüm karakterlerin görüntülenebilmesini sağlamak için gerektiğinde yazı tiplerini değiştirir.


**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


Metindeki tüm karakterlerin görüntülenebilmesini sağlamak için gerektiğinde yazı tiplerini değiştirir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | analyzeFonts | boolean | yazı tipleri gösterilecekse true, aksi takdirde false. |
|

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Mevcut XPS/OXPS belgesindeki tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırak.


Bu yazı tipinin lisansı bu işlemleri yasaklıyorsa, yazı tipleriyle ilgili birçok işlem gerçekleştirilemez.
Örneğin, lisans kuralları bu yazı tipinin gömülmesini engelliyorsa, bazı yazı tipleri PDF belgesine gömülemez.
Bu bayrağı kullanırken dikkatli olun. Ayarlandığında, bu bayrağı ayarlayan kişinin tüm sorumluluğu üstlendiği anlamına gelir
kendi üzerlerinde olası lisans/yasal ihlaller için. Bu yüzden riski kendileri üstlenirler. Kullanması şiddetle tavsiye edilir
bu bayrağı yalnızca telif hakkı yasasını ihlal etmediğinizden tamamen emin olduğunuzda kullanın. Varsayılan olarak false.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files) bakın.


Örnek kullanım:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


Mevcut XPS/OXPS belgesindeki tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırakmak amacıyla bayrağı ayarlayın.


Bu yazı tipinin lisansı bu işlemleri yasaklıyorsa, yazı tipleriyle ilgili birçok işlem gerçekleştirilemez.
Örneğin, lisans kuralları bu yazı tipinin gömülmesini engelliyorsa, bazı yazı tipleri PDF belgesine gömülemez.
Bu bayrağı kullanırken dikkatli olun. Ayarlandığında, bu bayrağı ayarlayan kişinin tüm sorumluluğu üstlendiği anlamına gelir
kendi üzerlerinde olası lisans/yasal ihlaller için. Bu yüzden riski kendileri üstlenirler. Kullanması şiddetle tavsiye edilir
bu bayrağı yalnızca telif hakkı yasasını ihlal etmediğinizden tamamen emin olduğunuzda kullanın. Varsayılan olarak false.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files) bakın.


Örnek kullanım:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

