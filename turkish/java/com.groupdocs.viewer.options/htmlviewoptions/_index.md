---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Belgeleri HTML formatına işlemek için seçenekler sunar."
type: docs
weight: 16
url: /tr/java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

Belgeleri HTML formatına işlemek için seçenekler sunar.


HtmlViewOptions sınıfı ek ayarları ve parametreleri kapsar
belge render'ını HTML formatına GroupDocs.Viewer bileşeninde kontrol etmek için kullanılabilir.


Ayrıntılar için, [topic](../https://docs.groupdocs.com/viewer/java/rendering-to-html/) ve alt öğelerine bakın.


Örnek kullanım:

````

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.setExcludeFonts(true);
 options.setFontsToExclude(Arrays.asList("font-name"));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CREATE_PAGE_STREAM](#CREATE-PAGE-STREAM) |  |
| [FILE_PATH_FORMAT](#FILE-PATH-FORMAT) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isRenderResponsive()](#isRenderResponsive--) | Duyarlı render'ının etkin olup olmadığını belirler. |
|
|  | [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | Duyarlı render'ın etkin olup olmadığını ayarlar. |
|
|  | [isMinify()](#isMinify--) | HTML içeriği ve HTML kaynaklarının küçültülmesinin etkin olup olmadığını denetler. |
|
|  | [setMinify(boolean value)](#setMinify-boolean-) | HTML içeriği ve HTML kaynaklarının küçültülmesinin etkin olup olmadığını ayarlar. |
|
|  | [isRenderToSinglePage()](#isRenderToSinglePage--) | Tüm belgeyi tek bir HTML dosyasına render etmeyi etkinleştirir. |
|
|  | [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | Tüm belgeyi tek bir HTML dosyasına render etmeyi etkinleştirir. |
|
|  | [getImageMaxWidth()](#getImageMaxWidth--) | Çıktı görüntüsünün piksel cinsinden maksimum genişliğini döndürür. |
|
|  | [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Çıktı görüntüsünün piksel cinsinden maksimum genişliğini ayarlar. |
|
|  | [getImageMaxHeight()](#getImageMaxHeight--) | Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini alır. |
|
|  | [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini ayarlar. |
|
|  | [getImageWidth()](#getImageWidth--) | Çıktı görüntüsünün piksel cinsinden genişliğini alır. |
|
|  | [setImageWidth(int imageWidth)](#setImageWidth-int-) | Çıktı görüntüsünün piksel cinsinden genişliğini ayarlar. |
|
|  | [getImageHeight()](#getImageHeight--) | Tek bir görüntüyü HTML'ye dönüştürürken çıktı görüntüsünün piksel cinsinden yüksekliğini alır. |
|
|  | [setImageHeight(int imageHeight)](#setImageHeight-int-) | Tek bir görüntüyü HTML'ye dönüştürürken çıktı görüntüsünün piksel cinsinden yüksekliğini ayarlar. |
|
|  | [isForPrinting()](#isForPrinting--) | Çıktı HTML'nin yazdırma için optimize edilip edilmediğini denetler. |
|
|  | [setForPrinting(boolean value)](#setForPrinting-boolean-) | Çıktı HTML'nin yazdırma için optimize edilip edilmeyeceğini ayarlar. |
|
|  | [isExcludeFonts()](#isExcludeFonts--) | Yazı tiplerinin HTML belgesinden dışarıda bırakılıp bırakılmayacağını belirler. |
|
|  | [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | Yazı tiplerinin HTML belgesinden dışarıda bırakılıp bırakılmayacağını ayarlar. |
|
|  | [getFontsToExclude()](#getFontsToExclude--) | HTML belgesinden dışarıda bırakılacak yazı tipi adlarının listesini alır. |
|
|  | [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | HTML belgesinden dışarıda bırakılacak yazı tipi adlarının listesini ayarlar. |
|
|  | [isRemoveJavaScript()](#isRemoveJavaScript--) | Girdi belgeleri render edilirken, betik içeren durumlarda, sonuç HTML belgelerindeki bağlantılardan JavaScript kaynak kodunu kaldırmaya izin verir. |
|
|  | [setRemoveJavaScript(boolean value)](#setRemoveJavaScript-boolean-) | Girdi belgeleri render edilirken, betik içeren durumlarda, sonuç HTML belgelerindeki bağlantılardan JavaScript kaynak kodunu kaldırma iznini ayarlar. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Words veya Email belgesinin kaydetme ilerlemesini tahmin etmek için kullanılan geri çağırmayı alır. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Words veya Email belgesinin kaydetme ilerlemesini tahmin etmek için kullanılan geri çağırmayı ayarlar. |
|
|  | [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | Yeni bir örnek başlatır |
HtmlViewOptions
gömülü kaynaklarla HTML'ye renderleme için sınıf.
|
|  | [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Yeni bir örnek başlatır |
HtmlViewOptions
gömülü kaynaklarla HTML'ye renderleme için sınıf.
|
|  | [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Yeni bir örnek başlatır |
HtmlViewOptions
gömülü kaynaklarla HTML'ye renderleme için sınıf.
|
|  | [forEmbeddedResources()](#forEmbeddedResources--) | Yeni bir örnek başlatır |
HtmlViewOptions
sınıf.
|
|  | [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | Yeni bir örnek başlatır |
HtmlViewOptions
sınıf.
|
|  | [forEmbeddedResources(Path filePathFormat)](#forEmbeddedResources-java.nio.file.Path-) | Yeni bir örnek başlatır |
HtmlViewOptions
sınıf.
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | Yeni bir örnek başlatır |
HtmlViewOptions
dış kaynaklarla HTML'ye renderleme için sınıf.
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) | Yeni bir örnek başlatır |
HtmlViewOptions
dış kaynaklarla HTML'ye renderleme için sınıf.
|
|  | [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | Yeni bir örnek başlatır |
HtmlViewOptions
dış kaynaklarla HTML'ye renderleme için sınıf.
|
|  | [forExternalResources()](#forExternalResources--) | Yeni bir örnek başlatır |
HtmlViewOptions
sınıf.
|
|  | [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | Yeni bir örnek başlatır |
HtmlViewOptions
sınıf.
|
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


Duyarlı render'ının etkin olup olmadığını belirler.
Duyarlı web sayfaları, farklı ekran boyutlarına sahip cihazlarda iyi render eder.


Duyarlı tasarım, web sayfalarının çeşitli cihazlarda iyi render etmesini amaçlar. Duyarlı bir düzenle renderlemek için bu özelliği true olarak ayarlayın.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/) bakın.


**Returns:**
boolean -  true  eğer duyarlı renderleme etkinse,  false  aksi takdirde.

### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


Duyarlı render'ın etkin olup olmadığını ayarlar.
Duyarlı web sayfaları, farklı ekran boyutlarına sahip cihazlarda iyi render eder.


Duyarlı tasarım, web sayfalarının çeşitli cihazlarda iyi render etmesini amaçlar. Duyarlı bir düzenle renderlemek için bu özelliği true olarak ayarlayın.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  duyarlı renderlemeyi etkinleştirmek için,  false  devre dışı bırakmak için. |
|

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


HTML içeriği ve HTML kaynaklarının küçültülmesinin etkin olup olmadığını denetler.


Çıktı içeriğinin (HTML, CSS ve SVG) sıkıştırılması, HTML dosyasını optimize etmenin yollarından biridir. Bunu yapmak için bu özelliği true olarak ayarlayın.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/minify-html/) bakın.


**Returns:**
boolean -  true  eğer küçültme etkinse,  false  aksi takdirde.

### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


HTML içeriği ve HTML kaynaklarının küçültülmesinin etkin olup olmadığını ayarlar.


Çıktı içeriğinin (HTML, CSS ve SVG) sıkıştırılması, HTML dosyasını optimize etmenin yollarından biridir. Bunu yapmak için bu özelliği true olarak ayarlayın.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/minify-html/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  küçültmeyi etkinleştirmek için,  false  devre dışı bırakmak için. |
|

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```


Tüm belgeyi tek bir HTML dosyasına render etmeyi etkinleştirir.

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer(\"invoice.docx\")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setRenderToSinglePage(boolean renderSinglePage) {#setRenderToSinglePage-boolean-}
```
public void setRenderToSinglePage(boolean renderSinglePage)
```


Tüm belgeyi tek bir HTML dosyasına render etmeyi etkinleştirir.

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer(\"invoice.docx\")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderSinglePage | boolean |  |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Çıktı görüntüsünün piksel cinsinden maksimum genişliğini döndürür.
***Note:** This value is used when converting a single image to HTML.
Ayrıntılar ve kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/) bakın.*


**Returns:**
int - çıktının maksimum genişliği.

### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Çıktı görüntüsünün piksel cinsinden maksimum genişliğini ayarlar.
***Note:** This value is used when converting a single image to HTML.
Ayrıntılar ve kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/) bakın.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | imageMaxWidth | int | Çıktının maksimum genişliği. |
|

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini alır.
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
Ayrıntılar ve kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/) bakın.*


**Returns:**
int - çıktının maksimum yüksekliği.

### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini ayarlar.
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
Ayrıntılar ve kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/) bakın.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | imageMaxHeight | int | Çıktının maksimum yüksekliği. |
|

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Çıktı görüntüsünün piksel cinsinden genişliğini alır.


***Note:** This value is applicable only when converting a single image to HTML.*
Ayrıntılar ve kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/) bakın.


**Returns:**
int - çıktının genişliği.

### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Çıktı görüntüsünün piksel cinsinden genişliğini ayarlar.


***Note:** This value is applicable only when converting a single image to HTML.*
Ayrıntılar ve kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | imageWidth | int | Çıktı görüntüsünün genişliği. |
|

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Tek bir görüntüyü HTML'ye dönüştürürken çıktı görüntüsünün piksel cinsinden yüksekliğini alır.


Ayrıntılar ve kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/) bakın.


**Returns:**
int - çıktı görüntüsünün piksel cinsinden yüksekliği.

### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Tek bir görüntüyü HTML'ye dönüştürürken çıktı görüntüsünün piksel cinsinden yüksekliğini ayarlar.


Ayrıntılar ve kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | imageHeight | int | Çıktı görüntüsünün piksel cinsinden yüksekliği. |
|

### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


Çıktı HTML'nin yazdırma için optimize edilip edilmediğini denetler.


Bu seçeneği etkinleştirerek çıktı HTML sayfalarını vektör SVG formatına dönüştürün.
Ayrıntılar ve kod örneği için [belgelendirme](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/) sayfasına bakın.


**Returns:**
boolean -  true  çıktı HTML'si yazdırma için optimize edilecekse,  false  aksi takdirde.

### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


Çıktı HTML'nin yazdırma için optimize edilip edilmeyeceğini ayarlar.


Bu seçeneği etkinleştirerek çıktı HTML sayfalarını vektör SVG formatına dönüştürün.
Ayrıntılar ve kod örneği için [belgelendirme](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/) sayfasına bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  çıktı HTML'sini yazdırma için optimize etmek,  false  aksi takdirde. |
|

### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


Yazı tiplerinin HTML belgesinden dışarıda bırakılıp bırakılmayacağını belirler.


Varsayılan olarak, GroupDocs.Viewer belgede kullanılan yazı tiplerini HTML'e gömer. Bunu önlemek için bu özelliği true olarak ayarlayın.
Ayrıntılar ve kod örneği için [belgelendirme](../https://docs.groupdocs.com/viewer/java/exclude-fonts/) sayfasına bakın.


**Returns:**
boolean -  true  yazı tipleri dışlanacaksa,  false  aksi takdirde.

### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


Yazı tiplerinin HTML belgesinden dışarıda bırakılıp bırakılmayacağını ayarlar.


Varsayılan olarak, GroupDocs.Viewer belgede kullanılan yazı tiplerini HTML'e gömer. Bunu önlemek için bu özelliği true olarak ayarlayın.
Ayrıntılar ve kod örneği için [belgelendirme](../https://docs.groupdocs.com/viewer/java/exclude-fonts/) sayfasına bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  yazı tiplerini dışlamak için,  false  aksi takdirde. |
|

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


HTML belgesinden dışarıda bırakılacak yazı tipi adlarının listesini alır.


Bu seçenek yalnızca sunumlar için desteklenir.
HTML belgesine yazı tiplerinin eklenmesi, çıktı görünümünün kararlılığını artırır ancak render sonucunun boyutunu büyütür.
Bu seçeneği, kararlılık ile çıktı boyutu arasında bir denge bulmak için kullanın.
Çoğu sistemde popüler ve yüklü olan yazı tipi adlarını dahil edin.


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) seçeneği devre dışı bırakıldı.*
Ayrıntılar ve kod örneği için [belgelendirme](../https://docs.groupdocs.com/viewer/java/exclude-fonts/) sayfasına bakın.


**Returns:**
java.util.List<java.lang.String> - HTML belgesinden dışlanacak yazı tipi adlarının listesi.

### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


HTML belgesinden dışarıda bırakılacak yazı tipi adlarının listesini ayarlar.


Bu seçenek yalnızca sunumlar için desteklenir.
HTML belgesine yazı tiplerinin eklenmesi, çıktı görünümünün kararlılığını artırır ancak render sonucunun boyutunu büyütür.
Bu seçeneği, kararlılık ile çıktı boyutu arasında bir denge bulmak için kullanın.
Çoğu sistemde popüler ve yüklü olan yazı tipi adlarını dahil edin.


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) seçeneği devre dışı bırakıldı.*
Ayrıntılar ve kod örneği için [belgelendirme](../https://docs.groupdocs.com/viewer/java/exclude-fonts/) sayfasına bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.util.List<java.lang.String> | HTML belgesinden dışlanacak yazı tipi adlarının listesi. |
|

### isRemoveJavaScript() {#isRemoveJavaScript--}
```
public final boolean isRemoveJavaScript()
```


Girdi belgeleri işlenirken, betik içeren durumlarda, sonuç HTML belgelerindeki bağlantılardan JavaScript kaynak kodunu kaldırmaya izin verir. Varsayılan olarak etkindir (true).


JavaScript kaldırma hakkında ayrıntılar için [belgelendirme](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html) sayfasına bakın.


**Returns:**
boolean
### setRemoveJavaScript(boolean value) {#setRemoveJavaScript-boolean-}
```
public void setRemoveJavaScript(boolean value)
```


Girdi belgeleri işlenirken, betik içeren durumlarda, sonuç HTML belgelerindeki bağlantılardan JavaScript kaynak kodunu kaldırma izni ayarlar. Varsayılan olarak etkindir (true).


JavaScript kaldırma hakkında ayrıntılar için [belgelendirme](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html) sayfasına bakın.


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
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - belge kaydetme ilerlemesini tahmin etmek için kullanılan geri çağırma.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Words veya Email belgesinin kaydetme ilerlemesini tahmin etmek için kullanılan geri çağırmayı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Belge kaydetme ilerlemesini tahmin etmek için kullanılan geri çağırma. |
|

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


Yeni bir örnek başlatır
HtmlViewOptions
gömülü kaynaklarla HTML'ye renderleme için sınıf.


***Note:** The method takes a 
CreatePageStream
parametre, çıktı sayfa verilerini yazmak için bir akış oluşturmakta kullanılan bir yöntemdir.*
Kod örneği için [belgelendirme](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources) sayfasına bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Çıktı sayfa verilerini yazmak için kullanılan akışı başlatan yöntem. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Yeni bir örnek başlatır
HtmlViewOptions
gömülü kaynaklarla HTML'ye renderleme için sınıf.


Kod örneği için [belgelendirme](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources) sayfasına bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Çıktı sayfa verilerini yazmak için kullanılan akışı başlatan yöntem. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | createPageStream parametresine atanmış yöntem tarafından oluşturulan akışı serbest bırakan yöntem. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


Yeni bir örnek başlatır
HtmlViewOptions
gömülü kaynaklarla HTML'ye renderleme için sınıf.


Kod örneği için [belgelendirme](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources) sayfasına bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Çıktı sayfa akışını oluşturma ve serbest bırakma yöntemlerini uygulayan fabrika. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


Yeni bir örnek başlatır
HtmlViewOptions
sınıf.


Kod örneği için [belgelendirme](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources) sayfasına bakın.


**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


Yeni bir örnek başlatır
HtmlViewOptions
sınıf.


Kod örneği için [belgelendirme](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources) sayfasına bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Dosya yolu biçimi, ör. 'page_{0}.html'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(Path filePathFormat) {#forEmbeddedResources-java.nio.file.Path-}
```
public static HtmlViewOptions forEmbeddedResources(Path filePathFormat)
```


Yeni bir örnek başlatır
HtmlViewOptions
sınıf.


Kod örneği için [belgelendirme](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources) sayfasına bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | Dosya yolu biçimi, ör. 'page_{0}.html'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


Yeni bir örnek başlatır
HtmlViewOptions
dış kaynaklarla HTML'ye renderleme için sınıf.


***Note:** This method should be used when rendering HTML with external resources, such as CSS and JavaScript files.*
Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources) bölümüne bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Çıktı sayfa verilerini yazmak için kullanılan akışı başlatan yöntem. |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | createPageStream yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | HTML kaynağı için URL'yi oluşturan yöntem. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```


Yeni bir örnek başlatır
HtmlViewOptions
dış kaynaklarla HTML'ye renderleme için sınıf.


Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources) bölümüne bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Çıktı sayfa verilerini yazmak için kullanılan akışı başlatan yöntem. |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | Çıktı HTML kaynağı verilerini yazmak için kullanılan akışı başlatan yöntem. |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | HTML kaynağı için URL'yi oluşturan yöntem. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | createPageStream yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |
|
|  | releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) | createResourceStream yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


Yeni bir örnek başlatır
HtmlViewOptions
dış kaynaklarla HTML'ye renderleme için sınıf.


Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources) bölümüne bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Çıktı sayfa akışını oluşturma ve serbest bırakma yöntemlerini uygulayan fabrika. |
|
|  | resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Kaynak URL'lerini oluşturma ve çıktı HTML kaynağı akışını başlatma/serbest bırakma yöntemlerini uygulayan fabrika. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


Yeni bir örnek başlatır
HtmlViewOptions
sınıf.


* - with "p_{0}.html" as file path format for the output HTML files;
* - with "p_{0}_{1}" as file path format for the output HTML-resource files;
* - with "p_{0}_{1}" as URL format for HTML-resources;

Çıktı dosyaları uygulamanın geçerli çalışma dizinine yerleştirilecektir. Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources) bölümüne bakın.

<br />



**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat) {#forExternalResources-java.lang.String-java.lang.String-java.lang.String-}
```
public static HtmlViewOptions forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)
```


Yeni bir örnek başlatır
HtmlViewOptions
sınıf.


Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources) bölümüne bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Dosya yolu biçimi, ör. 'page_{0}.html'. |
|
|  | resourceFilePathFormat | java.lang.String | Kaynak dosya yolu biçimi, ör. 'page_{0}/resource_{1}'. |
|
|  | resourceUrlFormat | java.lang.String | Kaynak URL biçimi, ör. 'page_{0}/resource_{1}'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
