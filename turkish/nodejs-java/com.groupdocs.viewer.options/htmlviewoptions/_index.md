---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Belgeleri HTML formatına renderleme seçeneklerini sağlar."
type: docs
weight: 16
url: /tr/nodejs-java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

Belgeleri HTML formatına renderleme seçeneklerini sağlar.

HtmlViewOptions sınıfı, GroupDocs.Viewer bileşeninde belgelerin HTML formatına dönüştürülmesini kontrol etmek için kullanılabilecek ek ayar ve parametreleri kapsar.

Ayrıntılar için [topic][] ve alt öğelerine bakın.

Örnek kullanım:

```

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.setExcludeFonts(true);
 options.setFontsToExclude(Arrays.asList("font-name"));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```


[topic]: https://docs.groupdocs.com/viewer/java/rendering-to-html/
## Fields

| Field | Açıklama |
| --- | --- |
| [CREATE_PAGE_STREAM](#CREATE-PAGE-STREAM) |  |
| [FILE_PATH_FORMAT](#FILE-PATH-FORMAT) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isRenderResponsive()](#isRenderResponsive--) | Duyarlı renderlamanın etkin olup olmadığını belirler. |
| [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | Duyarlı renderlamanın etkin olup olmadığını ayarlar. |
| [isMinify()](#isMinify--) | HTML içeriği ve HTML kaynaklarının küçültülmesinin etkin olup olmadığını kontrol eder. |
| [setMinify(boolean value)](#setMinify-boolean-) | HTML içeriği ve HTML kaynaklarının küçültülmesinin etkin olup olmadığını ayarlar. |
| [isRenderToSinglePage()](#isRenderToSinglePage--) | Tüm belgeyi tek bir HTML dosyasına renderlamayı etkinleştirir. |
| [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | Tüm belgeyi tek bir HTML dosyasına renderlamayı etkinleştirir. |
| [getImageMaxWidth()](#getImageMaxWidth--) | Çıktı görüntüsünün piksel cinsinden maksimum genişliğini döndürür. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Çıktı görüntüsünün piksel cinsinden maksimum genişliğini ayarlar. |
| [getImageMaxHeight()](#getImageMaxHeight--) | Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini alır. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini ayarlar. |
| [getImageWidth()](#getImageWidth--) | Çıktı görüntüsünün piksel cinsinden genişliğini alır. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | Çıktı görüntüsünün piksel cinsinden genişliğini ayarlar. |
| [getImageHeight()](#getImageHeight--) | Tek bir görüntüyü HTML'ye dönüştürürken çıktının piksel cinsinden yüksekliğini alır. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | Tek bir görüntüyü HTML'ye dönüştürürken çıktının piksel cinsinden yüksekliğini ayarlar. |
| [isForPrinting()](#isForPrinting--) | Çıktı HTML'nin yazdırma için optimize edilip edilmediğini kontrol eder. |
| [setForPrinting(boolean value)](#setForPrinting-boolean-) | Çıktı HTML'nin yazdırma için optimize edilip edilmeyeceğini ayarlar. |
| [isExcludeFonts()](#isExcludeFonts--) | HTML belgesinden yazı tiplerinin dışarıda bırakılıp bırakılmayacağını belirler. |
| [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | HTML belgesinden yazı tiplerinin dışarıda bırakılıp bırakılmayacağını ayarlar. |
| [getFontsToExclude()](#getFontsToExclude--) | HTML belgesinden dışarıda bırakılacak yazı tipi adlarının listesini alır. |
| [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | HTML belgesinden dışarıda bırakılacak yazı tipi adlarının listesini ayarlar. |
| [isRemoveJavaScript()](#isRemoveJavaScript--) | Betik içeren girdi belgeleri işlenirken, ortaya çıkan HTML belgelerindeki bağlantılardan JavaScript kaynak kodunu kaldırmaya izin verir. |
| [setRemoveJavaScript(boolean value)](#setRemoveJavaScript-boolean-) | Betik içeren girdi belgeleri işlenirken, ortaya çıkan HTML belgelerindeki bağlantılardan JavaScript kaynak kodunu kaldırma iznini ayarlar. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Words veya Email belgesinin kaydetme ilerlemesini tahmin etmek için kullanılan geri çağırmayı alır. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Words veya Email belgesinin kaydetme ilerlemesini tahmin etmek için kullanılan geri çağırmayı ayarlar. |
| [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | Yerleşik kaynaklarla HTML'ye işlemek için yeni bir HtmlViewOptions sınıfı örneği başlatır. |
| [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Yerleşik kaynaklarla HTML'ye işlemek için yeni bir HtmlViewOptions sınıfı örneği başlatır. |
| [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Yerleşik kaynaklarla HTML'ye işlemek için yeni bir HtmlViewOptions sınıfı örneği başlatır. |
| [forEmbeddedResources()](#forEmbeddedResources--) | Yeni bir HtmlViewOptions sınıfı örneği başlatır. |
| [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | Yeni bir HtmlViewOptions sınıfı örneği başlatır. |
| [forEmbeddedResources(Path filePathFormat)](#forEmbeddedResources-java.nio.file.Path-) | Yeni bir HtmlViewOptions sınıfı örneği başlatır. |
| [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | Dış kaynaklarla HTML'ye işlemek için yeni bir HtmlViewOptions sınıfı örneği başlatır. |
| [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) | Dış kaynaklarla HTML'ye işlemek için yeni bir HtmlViewOptions sınıfı örneği başlatır. |
| [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | Dış kaynaklarla HTML'ye işlemek için yeni bir HtmlViewOptions sınıfı örneği başlatır. |
| [forExternalResources()](#forExternalResources--) | Yeni bir HtmlViewOptions sınıfı örneği başlatır. |
| [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | Yeni bir HtmlViewOptions sınıfı örneği başlatır. |
### CREATE_PAGE_STREAM {#CREATE-PAGE-STREAM}
```
public static final String CREATE_PAGE_STREAM
```


### FILE_PATH_FORMAT {#FILE-PATH-FORMAT}
```
public static final String FILE_PATH_FORMAT
```


### isRenderResponsive() {#isRenderResponsive--}
```
public final boolean isRenderResponsive()
```


Responsive renderlamanın etkin olup olmadığını belirler. Responsive web sayfaları farklı ekran boyutlarına sahip cihazlarda iyi görüntülenir.

Responsive tasarım, web sayfalarının çeşitli cihazlarda iyi görüntülenmesini amaçlar. Responsive bir düzenle renderlamak için bu özelliği true olarak ayarlayın. Kod örneği için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/

**Returns:**
boolean - responsive renderlama etkinse true, aksi takdirde false.
### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


Responsive renderlamanın etkin olup olmadığını ayarlar. Responsive web sayfaları farklı ekran boyutlarına sahip cihazlarda iyi görüntülenir.

Responsive tasarım, web sayfalarının çeşitli cihazlarda iyi görüntülenmesini amaçlar. Responsive bir düzenle renderlamak için bu özelliği true olarak ayarlayın. Kod örneği için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | responsive renderlamayı etkinleştirmek için true, devre dışı bırakmak için false. |

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


HTML içeriği ve HTML kaynaklarının küçültülmesinin etkin olup olmadığını kontrol eder.

Çıktı içeriğinin (HTML, CSS ve SVG) sıkıştırılması, HTML dosyasını optimize etmenin yollarından biridir. Bunu yapmak için bu özelliği true olarak ayarlayın. Kod örneği için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/minify-html/

**Returns:**
boolean -  true  eğer küçültme etkinleştirilmişse,  false  aksi takdirde.
### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


HTML içeriği ve HTML kaynaklarının küçültülmesinin etkin olup olmadığını ayarlar.

Çıktı içeriğinin (HTML, CSS ve SVG) sıkıştırılması, HTML dosyasını optimize etmenin yollarından biridir. Bunu yapmak için bu özelliği true olarak ayarlayın. Kod örneği için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/minify-html/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | true  küçültmeyi etkinleştirmek için,  false  devre dışı bırakmak için. |

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```


Tüm belgeyi tek bir HTML dosyasına renderlamayı etkinleştirir.

**See the following topics for more information:**

 *  [Render archives as HTML, PDF, and image files][Render archives as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render web documents as PDF, PNG, and JPEG files][Render web documents as PDF_ PNG_ and JPEG files]

**Example:**

```
try (final Viewer viewer = new Viewer("invoice.docx")) {
   HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
   viewOptions.setRenderToSinglePage(true);

   viewer.view(viewOptions);
 }
```


[Render archives as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file
[Render web documents as PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources

**Returns:**
boolean
### setRenderToSinglePage(boolean renderSinglePage) {#setRenderToSinglePage-boolean-}
```
public void setRenderToSinglePage(boolean renderSinglePage)
```


Tüm belgeyi tek bir HTML dosyasına renderlamayı etkinleştirir.

**See the following topics for more information:**

 *  [Render archives as HTML, PDF, and image files][Render archives as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render web documents as PDF, PNG, and JPEG files][Render web documents as PDF_ PNG_ and JPEG files]

**Example:**

```
try (final Viewer viewer = new Viewer("invoice.docx")) {
   HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
   viewOptions.setRenderToSinglePage(true);

   viewer.view(viewOptions);
 }
```


[Render archives as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file
[Render web documents as PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderSinglePage | boolean |  |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Çıktı görüntüsünün piksel cinsinden maksimum genişliğini döndürür.

**Note:** This value is used when converting a single image to HTML. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - çıktı görüntüsünün maksimum genişliği.
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Çıktı görüntüsünün piksel cinsinden maksimum genişliğini ayarlar.

**Note:** This value is used when converting a single image to HTML. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageMaxWidth | int | Çıktı görüntüsünün maksimum genişliği. |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini alır.

**Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - çıktı görüntüsünün maksimum yüksekliği.
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini ayarlar.

**Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image. For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageMaxHeight | int | Çıktı görüntüsünün maksimum yüksekliği. |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Çıktı görüntüsünün piksel cinsinden genişliğini alır.

***Note:** This value is applicable only when converting a single image to HTML.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - çıktı görüntüsünün genişliği.
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Çıktı görüntüsünün piksel cinsinden genişliğini ayarlar.

***Note:** This value is applicable only when converting a single image to HTML.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageWidth | int | Çıktı görüntüsünün genişliği. |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Tek bir görüntüyü HTML'ye dönüştürürken çıktının piksel cinsinden yüksekliğini alır.

Ayrıntılar ve kod örneği için, [belge][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Returns:**
int - çıktı görüntüsünün piksel cinsinden yüksekliği.
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Tek bir görüntüyü HTML'ye dönüştürürken çıktının piksel cinsinden yüksekliğini ayarlar.

Ayrıntılar ve kod örneği için, [belge][].


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageHeight | int | Çıktı görüntüsünün piksel cinsinden yüksekliği. |

### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


Çıktı HTML'nin yazdırma için optimize edilip edilmediğini kontrol eder.

Bu seçeneği etkinleştirerek çıktı HTML sayfalarını vektör SVG formatına dönüştürün. Ayrıntılar ve kod örneği için, [belge][].


[documentation]: https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/

**Returns:**
boolean -  true  eğer çıktı HTML'si yazdırma için optimize edilmesi gerekiyorsa,  false  aksi takdirde.
### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


Çıktı HTML'nin yazdırma için optimize edilip edilmeyeceğini ayarlar.

Bu seçeneği etkinleştirerek çıktı HTML sayfalarını vektör SVG formatına dönüştürün. Ayrıntılar ve kod örneği için, [belge][].


[documentation]: https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | true  çıktı HTML'sini yazdırma için optimize etmek için,  false  aksi takdirde. |

### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


HTML belgesinden yazı tiplerinin dışarıda bırakılıp bırakılmayacağını belirler.

Varsayılan olarak, GroupDocs.Viewer belgedeki kullanılan yazı tiplerini HTML'e gömer. Bunu önlemek için bu özelliği true olarak ayarlayın. Ayrıntılar ve kod örneği için, [belge][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Returns:**
boolean -  true  eğer yazı tipleri dışlanacaksa,  false  aksi takdirde.
### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


HTML belgesinden yazı tiplerinin dışarıda bırakılıp bırakılmayacağını ayarlar.

Varsayılan olarak, GroupDocs.Viewer belgedeki kullanılan yazı tiplerini HTML'e gömer. Bunu önlemek için bu özelliği true olarak ayarlayın. Ayrıntılar ve kod örneği için, [belge][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean | true  yazı tiplerini dışlamak için,  false  aksi takdirde. |

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


HTML belgesinden dışarıda bırakılacak yazı tipi adlarının listesini alır.

Bu seçenek yalnızca sunumlar için desteklenir. HTML belgesine yazı tiplerinin dahil edilmesi, çıktı görünümünün kararlılığını artırır ancak render sonucunun boyutunu büyütür. Bu seçeneği, kararlılık ile çıktı boyutu arasında bir denge bulmak için kullanın. Çoğu sistemde popüler ve yüklü olan yazı tipi adlarını dahil edin.

***Note:** Please note that this property is active only when the  ExcludeFonts  (\#isExcludeFonts().isExcludeFonts()/\#setExcludeFonts(boolean).setExcludeFonts(boolean)) option is disabled.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Returns:**
java.util.List<java.lang.String> - HTML belgesinden dışlanacak yazı tipi adlarının listesi.
### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


HTML belgesinden dışarıda bırakılacak yazı tipi adlarının listesini ayarlar.

Bu seçenek yalnızca sunumlar için desteklenir. HTML belgesine yazı tiplerinin dahil edilmesi, çıktı görünümünün kararlılığını artırır ancak render sonucunun boyutunu büyütür. Bu seçeneği, kararlılık ile çıktı boyutu arasında bir denge bulmak için kullanın. Çoğu sistemde popüler ve yüklü olan yazı tipi adlarını dahil edin.

***Note:** Please note that this property is active only when the  ExcludeFonts  (\#isExcludeFonts().isExcludeFonts()/\#setExcludeFonts(boolean).setExcludeFonts(boolean)) option is disabled.* For details and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/exclude-fonts/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.List<java.lang.String> | HTML belgesinden dışlanacak yazı tipi adlarının listesi. |

### isRemoveJavaScript() {#isRemoveJavaScript--}
```
public final boolean isRemoveJavaScript()
```


Girdi belgeleri işlenirken, betik içeren durumlarda, sonuç HTML belgelerindeki bağlantılardan JavaScript kaynak kodunu kaldırmaya izin verir. Varsayılan olarak etkindir (true).

JavaScript kaldırma hakkında ayrıntılar için, [belge][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html

**Returns:**
boolean
### setRemoveJavaScript(boolean value) {#setRemoveJavaScript-boolean-}
```
public void setRemoveJavaScript(boolean value)
```


Girdi belgeleri işlenirken, betik içeren durumlarda, sonuç HTML belgelerindeki bağlantılardan JavaScript kaynak kodunu kaldırma iznini ayarlar. Varsayılan olarak etkindir (true).

JavaScript kaldırma hakkında ayrıntılar için, [belge][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Words veya Email belgesinin kaydetme ilerlemesini tahmin etmek için kullanılan geri çağırmayı alır.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - belge kaydetme ilerlemesini tahmin etmek için kullanılan geri arama.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Words veya Email belgesinin kaydetme ilerlemesini tahmin etmek için kullanılan geri çağırmayı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Belge kaydetme ilerlemesini tahmin etmek için kullanılan geri arama. |

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


Yerleşik kaynaklarla HTML'ye işlemek için yeni bir HtmlViewOptions sınıfı örneği başlatır.

***Note:** The method takes a  CreatePageStream  parameter, which is a method used to instantiate a stream for writing output page data.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Çıktı sayfa verilerini yazmak için kullanılan akışı başlatan yöntem. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Yerleşik kaynaklarla HTML'ye işlemek için yeni bir HtmlViewOptions sınıfı örneği başlatır.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Çıktı sayfa verilerini yazmak için kullanılan akışı başlatan yöntem. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | createPageStream parametresine atanmış yöntem tarafından oluşturulan akışı serbest bırakan yöntem. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


Yerleşik kaynaklarla HTML'ye işlemek için yeni bir HtmlViewOptions sınıfı örneği başlatır.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Çıktı sayfa akışını oluşturma ve serbest bırakma yöntemlerini uygulayan fabrika. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.
### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


Yeni bir HtmlViewOptions sınıfı örneği başlatır.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


Yeni bir HtmlViewOptions sınıfı örneği başlatır.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePathFormat | java.lang.String | Dosya yolu biçimi, ör. 'page\_\{0\}.html'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forEmbeddedResources(Path filePathFormat) {#forEmbeddedResources-java.nio.file.Path-}
```
public static HtmlViewOptions forEmbeddedResources(Path filePathFormat)
```


Yeni bir HtmlViewOptions sınıfı örneği başlatır.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | Dosya yolu biçimi, ör. 'page\_\{0\}.html'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.
### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


Dış kaynaklarla HTML'ye işlemek için yeni bir HtmlViewOptions sınıfı örneği başlatır.

***Note:** This method should be used when rendering HTML with external resources, such as CSS and JavaScript files.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Çıktı sayfa verilerini yazmak için kullanılan akışı başlatan yöntem. |
| createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | createPageStream yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |
| createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | HTML kaynağı için URL'yi oluşturan yöntem. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```


Dış kaynaklarla HTML'ye işlemek için yeni bir HtmlViewOptions sınıfı örneği başlatır.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Çıktı sayfa verilerini yazmak için kullanılan akışı başlatan yöntem. |
| createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | Çıktı HTML kaynağı verilerini yazmak için kullanılan akışı başlatan yöntem. |
| createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | HTML kaynağı için URL'yi oluşturan yöntem. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | createPageStream yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |
| releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) | createResourceStream yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


Dış kaynaklarla HTML'ye işlemek için yeni bir HtmlViewOptions sınıfı örneği başlatır.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Çıktı sayfa akışını oluşturma ve serbest bırakma yöntemlerini uygulayan fabrika. |
| resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Kaynak URL'lerini oluşturma ve çıktı HTML kaynağı akışını başlatma/serbest bırakma yöntemlerini uygulayan fabrika. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.
### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


Yeni bir HtmlViewOptions sınıfı örneği başlatır.

 *  \- with "p\_\{0\}.html" as file path format for the output HTML files;
 *  \- with "p\_\{0\}\_\{1\}" as file path format for the output HTML-resource files;
 *  \- with "p\_\{0\}\_\{1\}" as URL format for HTML-resources;

Çıktı dosyaları uygulamanın geçerli çalışma dizinine yerleştirilecektir. Kod örneği için [documentation][] belgesine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat) {#forExternalResources-java.lang.String-java.lang.String-java.lang.String-}
```
public static HtmlViewOptions forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)
```


Yeni bir HtmlViewOptions sınıfı örneği başlatır.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePathFormat | java.lang.String | Dosya yolu biçimi, ör. 'page\_\{0\}.html'. |
| resourceFilePathFormat | java.lang.String | Kaynak dosya yolu biçimi, ör. 'page\_\{0\}/resource\_\{1\}'. |
| resourceUrlFormat | java.lang.String | Kaynak URL biçimi, ör. 'page\_\{0\}/resource\_\{1\}'. |

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
