---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Görünüm hakkında bilgi almak için kullanılan seçenekleri sağlar."
type: docs
weight: 34
url: /tr/java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

Görünüm hakkında bilgi almak için kullanılan seçenekleri sağlar.


ViewInfoOptions sınıfı ek ayarları ve parametreleri kapsar
GroupDocs.Viewer bileşenindeki bir görünüm hakkında bilgi almak için kullanılabilir.


Örnek kullanım:

````

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isExtractText()](#isExtractText--) | Metin çıkarımının etkin olup olmadığını gösterir. |
|
|  | [setExtractText(boolean extractText)](#setExtractText-boolean-) | Metin çıkarımının etkin olup olmadığını gösteren bayrağı ayarlar. |
|
|  | [getMaxWidth()](#getMaxWidth--) | PNG/JPG olarak render etmek için çıktı görüntüsünün maksimum genişliğini döndürür. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Çıktı görüntüsünün maksimum genişliğini ayarlar (piksel cinsinden, yalnızca PNG/JPG render için). |
|
|  | [getMaxHeight()](#getMaxHeight--) | PNG/JPG olarak render etmek için çıktı görüntüsünün maksimum yüksekliğini döndürür. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Çıktı görüntüsünün maksimum yüksekliğini ayarlar (piksel cinsinden, yalnızca PNG/JPG render için). |
|
|  | [getWidth()](#getWidth--) | Çıktı görüntüsünün genişliği (piksel cinsinden, yalnızca PNG/JPG render için). |
|
|  | [setWidth(int width)](#setWidth-int-) | Çıktı görüntüsünün genişliği (piksel cinsinden, yalnızca PNG/JPG render için). |
|
|  | [getHeight()](#getHeight--) | Çıktı görüntüsünün yüksekliği (piksel cinsinden, yalnızca PNG/JPG render için). |
|
|  | [setHeight(int height)](#setHeight-int-) | Çıktı görüntüsünün yüksekliği (piksel cinsinden, yalnızca PNG/JPG render için). |
|
|  | [forHtmlView()](#forHtmlView--) | Yeni bir örnek başlatır |
ViewInfoOptions
HTML'ye render edildiğinde görünüm hakkında bilgi almak için sınıf.
|
|  | [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | Yeni bir örnek başlatır |
ViewInfoOptions
HTML'ye render edildiğinde görünüm hakkında bilgi almak için sınıf.
|
|  | [forJpgView()](#forJpgView--) | Yeni bir örnek başlatır |
ViewInfoOptions
JPG'ye render edildiğinde görünüm hakkında bilgi almak için sınıf.
|
|  | [forJpgView(boolean extractText)](#forJpgView-boolean-) | Yeni bir örnek başlatır |
ViewInfoOptions
JPG'ye render edildiğinde görünüm hakkında bilgi almak için sınıf.
|
|  | [forPngView()](#forPngView--) | Yeni bir örnek başlatır |
ViewInfoOptions
PNG'ye render edildiğinde görünüm hakkında bilgi almak için sınıf.
|
|  | [forPngView(boolean extractText)](#forPngView-boolean-) | Yeni bir örnek başlatır |
ViewInfoOptions
PNG'ye render edildiğinde görünüm hakkında bilgi almak için sınıf.
|
|  | [forPdfView()](#forPdfView--) | PDF'ye render edildiğinde görünüm hakkında bilgi almak için ViewInfoOptions sınıfının yeni bir örneğini başlatır. |
|
|  | [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | Yeni bir örnek başlatır |
ViewInfoOptions
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) nesnesine dayalı sınıf.
|
|  | [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | Yeni bir örnek başlatır |
ViewInfoOptions
[PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) nesnesine dayalı sınıf.
|
|  | [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | Yeni bir örnek başlatır |
ViewInfoOptions
[JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) nesnesine dayalı sınıf.
|
|  | [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) sınıfının, PdfViewOptions nesnesine dayalı yeni bir örneğini başlatır. |
|
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


Metin çıkarımının etkin olup olmadığını gösterir.
Bu özelliği, bir kaynak belgede bulunan metni ve koordinatlarını almak için kullanın. Ardından bu verileri, görüntünün üzerine seçilebilir bir metin eklemek veya görüntü tabanlı render'da metin araması uygulamak için kullanabilirsiniz. Kod örneği için, [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/) adresine bakın.


**Returns:**
boolean - Metin çıkarma etkinse True, aksi takdirde false.

### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


Metin çıkarımının etkin olup olmadığını gösteren bayrağı ayarlar.
Bu özelliği, bir kaynak belgede bulunan metni ve koordinatlarını almak için kullanın. Ardından bu verileri, görüntünün üzerine seçilebilir bir metin eklemek veya görüntü tabanlı render'da metin araması uygulamak için kullanabilirsiniz. Kod örneği için, [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | extractText | boolean | Metin çıkarmayı etkinleştirmek için True, devre dışı bırakmak için false. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


PNG/JPG olarak render etmek için çıktı görüntüsünün maksimum genişliğini döndürür.
Bu özelliği, çıkış görüntüsünün maksimum genişliğini (piksel olarak) ayarlamak için kullanın. Kod örneği için, [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/) adresine bakın. Özelliği ayarlarsanız, bu özellik yok sayılır.


**Returns:**
int - çıktı görüntüsünün maksimum genişliği.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Çıktı görüntüsünün maksimum genişliğini ayarlar (piksel cinsinden, yalnızca PNG/JPG render için).
Bu özelliği, çıkış görüntüsünün maksimum genişliğini (piksel olarak) ayarlamak için kullanın. Kod örneği için, [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/) adresine bakın. Özelliği ayarlarsanız, bu özellik yok sayılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | maxWidth | int | Çıktı görüntüsünün maksimum genişliği. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


PNG/JPG olarak render etmek için çıktı görüntüsünün maksimum yüksekliğini döndürür.
Bu özelliği, çıkış görüntüsünün maksimum yüksekliğini (piksel olarak) ayarlamak için kullanın. Kod örneği için, [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/) adresine bakın. Özelliği ayarlarsanız, bu özellik yok sayılır.


**Returns:**
int - çıktı görüntüsünün maksimum yüksekliği.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Çıktı görüntüsünün maksimum yüksekliğini ayarlar (piksel cinsinden, yalnızca PNG/JPG render için).
Bu özelliği, çıkış görüntüsünün maksimum yüksekliğini (piksel olarak) ayarlamak için kullanın. Kod örneği için, [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/) adresine bakın. Özelliği ayarlarsanız, bu özellik yok sayılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | maxHeight | int | Çıktı görüntüsünün maksimum yüksekliği. |
|

### getWidth() {#getWidth--}
```
public int getWidth()
```


Çıktı görüntüsünün genişliği (piksel cinsinden, yalnızca PNG/JPG render için).
Bu özelliği, çıkış görüntüsünün genişliğini (piksel olarak) ayarlamak için kullanın. Kod örneği için, [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/) adresine bakın. Bu özelliği ayarlarsanız, özellik yok sayılır.


**Returns:**
int - görüntünün genişliği.

### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


Çıktı görüntüsünün genişliği (piksel cinsinden, yalnızca PNG/JPG render için).
Bu özelliği, çıkış görüntüsünün genişliğini (piksel olarak) ayarlamak için kullanın. Kod örneği için, [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/) adresine bakın. Bu özelliği ayarlarsanız, özellik yok sayılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | width | int | Görüntünün genişliği. |
|

### getHeight() {#getHeight--}
```
public int getHeight()
```


Çıktı görüntüsünün yüksekliği (piksel cinsinden, yalnızca PNG/JPG render için).
Bu özelliği, çıkış görüntüsünün yüksekliğini (piksel olarak) ayarlamak için kullanın. Kod örneği için, [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/) adresine bakın. Bu özelliği ayarlarsanız, özellik yok sayılır.


**Returns:**
int - görüntünün yüksekliği.

### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


Çıktı görüntüsünün yüksekliği (piksel cinsinden, yalnızca PNG/JPG render için).
Bu özelliği, çıkış görüntüsünün yüksekliğini (piksel olarak) ayarlamak için kullanın. Kod örneği için, [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/) adresine bakın. Bu özelliği ayarlarsanız, özellik yok sayılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | height | int | Görüntünün yüksekliği. |
|

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


Yeni bir örnek başlatır
ViewInfoOptions
HTML'ye render edildiğinde görünüm hakkında bilgi almak için sınıf.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.

### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


Yeni bir örnek başlatır
ViewInfoOptions
HTML'ye render edildiğinde görünüm hakkında bilgi almak için sınıf.


***Note:** By default, HTML content will be rendered on multiple pages.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | renderSinglePage | boolean | HTML içeriğinin tek bir sayfada render edilmesini sağlar. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


Yeni bir örnek başlatır
ViewInfoOptions
JPG'ye render edildiğinde görünüm hakkında bilgi almak için sınıf.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


Yeni bir örnek başlatır
ViewInfoOptions
JPG'ye render edildiğinde görünüm hakkında bilgi almak için sınıf.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | extractText | boolean | Metin çıkarma özelliğini etkinleştirir. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


Yeni bir örnek başlatır
ViewInfoOptions
PNG'ye render edildiğinde görünüm hakkında bilgi almak için sınıf.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


Yeni bir örnek başlatır
ViewInfoOptions
PNG'ye render edildiğinde görünüm hakkında bilgi almak için sınıf.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | extractText | boolean | Metin çıkarma özelliğini etkinleştirir. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


PDF'ye render edildiğinde görünüm hakkında bilgi almak için ViewInfoOptions sınıfının yeni bir örneğini başlatır.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.

### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


Yeni bir örnek başlatır
ViewInfoOptions
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) nesnesine dayalı sınıf.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | HTML görünüm seçenekleri. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


Yeni bir örnek başlatır
ViewInfoOptions
[PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) nesnesine dayalı sınıf.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | PNG görüntü seçenekleri. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


Yeni bir örnek başlatır
ViewInfoOptions
[JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) nesnesine dayalı sınıf.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | JPG görüntü seçenekleri. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) sınıfının, PdfViewOptions nesnesine dayalı yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | PDF görüntü seçenekleri. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.

