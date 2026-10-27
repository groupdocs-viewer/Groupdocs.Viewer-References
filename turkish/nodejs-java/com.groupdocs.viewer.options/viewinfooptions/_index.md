---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Görünüm hakkında bilgi almayı sağlayan seçenekler sunar."
type: docs
weight: 34
url: /tr/nodejs-java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

Görünüm hakkında bilgi almayı sağlayan seçenekler sunar.

ViewInfoOptions sınıfı, GroupDocs.Viewer bileşeninde bir görünüm hakkında bilgi almak için kullanılabilecek ek ayarları ve parametreleri kapsüller.

Örnek kullanım:

```

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isExtractText()](#isExtractText--) | Metin çıkarımının etkin olup olmadığını gösterir. |
| [setExtractText(boolean extractText)](#setExtractText-boolean-) | Metin çıkarımının etkin olup olmadığını gösteren bayrağı ayarlar. |
| [getMaxWidth()](#getMaxWidth--) | PNG/JPG render için çıktı görüntüsünün maksimum genişliğini döndürür. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Çıktı görüntüsünün maksimum genişliğini ayarlar (piksel cinsinden, yalnızca PNG/JPG render için). |
| [getMaxHeight()](#getMaxHeight--) | PNG/JPG render için çıktı görüntüsünün maksimum yüksekliğini döndürür. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Çıktı görüntüsünün maksimum yüksekliğini ayarlar (piksel cinsinden, yalnızca PNG/JPG render için). |
| [getWidth()](#getWidth--) | Çıktı görüntüsünün genişliği (piksel cinsinden, yalnızca PNG/JPG render için). |
| [setWidth(int width)](#setWidth-int-) | Çıktı görüntüsünün genişliği (piksel cinsinden, yalnızca PNG/JPG render için). |
| [getHeight()](#getHeight--) | Çıktı görüntüsünün yüksekliği (piksel cinsinden, yalnızca PNG/JPG render için). |
| [setHeight(int height)](#setHeight-int-) | Çıktı görüntüsünün yüksekliği (piksel cinsinden, yalnızca PNG/JPG render için). |
| [forHtmlView()](#forHtmlView--) | HTML'ye render ederken görünüm hakkında bilgi almak için yeni bir ViewInfoOptions sınıfı örneği başlatır. |
| [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | HTML'ye render ederken görünüm hakkında bilgi almak için yeni bir ViewInfoOptions sınıfı örneği başlatır. |
| [forJpgView()](#forJpgView--) | JPG'ye render ederken görünüm hakkında bilgi almak için yeni bir ViewInfoOptions sınıfı örneği başlatır. |
| [forJpgView(boolean extractText)](#forJpgView-boolean-) | JPG'ye render ederken görünüm hakkında bilgi almak için yeni bir ViewInfoOptions sınıfı örneği başlatır. |
| [forPngView()](#forPngView--) | PNG'ye render ederken görünüm hakkında bilgi almak için yeni bir ViewInfoOptions sınıfı örneği başlatır. |
| [forPngView(boolean extractText)](#forPngView-boolean-) | PNG'ye render ederken görünüm hakkında bilgi almak için yeni bir ViewInfoOptions sınıfı örneği başlatır. |
| [forPdfView()](#forPdfView--) | PDF'ye render edilirken görünüm hakkında bilgi almak için ViewInfoOptions sınıfının yeni bir örneğini başlatır. |
| [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | HtmlViewOptions nesnesine dayalı olarak ViewInfoOptions sınıfının yeni bir örneğini başlatır. |
| [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | ViewInfoOptions sınıfının yeni bir örneğini, [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) nesnesine dayanarak başlatır. |
| [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | ViewInfoOptions sınıfının yeni bir örneğini, [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) nesnesine dayanarak başlatır. |
| [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) sınıfının yeni bir örneğini, bir PdfViewOptions nesnesine dayanarak başlatır. |
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


Metin çıkarımının etkin olup olmadığını gösterir.

Bu özelliği, bir kaynak belgede bulunan metni ve koordinatlarını almak için kullanın. Ardından bu verileri, görüntünün üzerine seçilebilir bir metin eklemek veya görüntü tabanlı render'da metin araması uygulamak için kullanabilirsiniz. Kod örneği için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/

**Returns:**
boolean - Metin çıkarma etkinse True, aksi takdirde false.
### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


Metin çıkarımının etkin olup olmadığını gösteren bayrağı ayarlar.

Bu özelliği, bir kaynak belgede bulunan metni ve koordinatlarını almak için kullanın. Ardından bu verileri, görüntünün üzerine seçilebilir bir metin eklemek veya görüntü tabanlı render'da metin araması uygulamak için kullanabilirsiniz. Kod örneği için [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| extractText | boolean | Metin çıkarmayı etkinleştirmek için True, devre dışı bırakmak için false. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


PNG/JPG render için çıktı görüntüsünün maksimum genişliğini döndürür.

Bu özelliği, maksimum çıktı görüntüsü genişliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için [documentation][] bağlantısına bakın. Eğer  özelliğini ayarlarsanız, bu özellik yok sayılır.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - çıktının maksimum genişliği.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Çıktı görüntüsünün maksimum genişliğini ayarlar (piksel cinsinden, yalnızca PNG/JPG render için).

Bu özelliği, maksimum çıktı görüntüsü genişliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için [documentation][] bağlantısına bakın. Eğer  özelliğini ayarlarsanız, bu özellik yok sayılır.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| maxWidth | int | Çıktının maksimum genişliği. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


PNG/JPG render için çıktı görüntüsünün maksimum yüksekliğini döndürür.

Bu özelliği, maksimum çıktı görüntüsü yüksekliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için [documentation][] bağlantısına bakın. Eğer  özelliğini ayarlarsanız, bu özellik yok sayılır.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - çıktının maksimum yüksekliği.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Çıktı görüntüsünün maksimum yüksekliğini ayarlar (piksel cinsinden, yalnızca PNG/JPG render için).

Bu özelliği, maksimum çıktı görüntüsü yüksekliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için [documentation][] bağlantısına bakın. Eğer  özelliğini ayarlarsanız, bu özellik yok sayılır.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| maxHeight | int | Çıktının maksimum yüksekliği. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Çıktı görüntüsünün genişliği (piksel cinsinden, yalnızca PNG/JPG render için).

Bu özelliği, çıktı görüntüsü genişliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için [documentation][] bağlantısına bakın. Bu özelliği ayarlarsanız,  özelliği yok sayılır.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Returns:**
int - görüntünün genişliği.
### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


Çıktı görüntüsünün genişliği (piksel cinsinden, yalnızca PNG/JPG render için).

Bu özelliği, çıktı görüntüsü genişliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için [documentation][] bağlantısına bakın. Bu özelliği ayarlarsanız,  özelliği yok sayılır.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| width | int | Görüntünün genişliği. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Çıktı görüntüsünün yüksekliği (piksel cinsinden, yalnızca PNG/JPG render için).

Bu özelliği, çıktı görüntüsü yüksekliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için [documentation][] bağlantısına bakın. Bu özelliği ayarlarsanız,  özelliği yok sayılır.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Returns:**
int - görüntünün yüksekliği.
### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


Çıktı görüntüsünün yüksekliği (piksel cinsinden, yalnızca PNG/JPG render için).

Bu özelliği, çıktı görüntüsü yüksekliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için [documentation][] bağlantısına bakın. Bu özelliği ayarlarsanız,  özelliği yok sayılır.


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| height | int | Görüntünün yüksekliği. |

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


HTML'ye render ederken görünüm hakkında bilgi almak için yeni bir ViewInfoOptions sınıfı örneği başlatır.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.
### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


HTML'ye render ederken görünüm hakkında bilgi almak için yeni bir ViewInfoOptions sınıfı örneği başlatır.

***Note:** By default, HTML content will be rendered on multiple pages.*

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| renderSinglePage | boolean | HTML içeriğinin tek bir sayfada render edilmesini sağlar. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


JPG'ye render ederken görünüm hakkında bilgi almak için yeni bir ViewInfoOptions sınıfı örneği başlatır.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


JPG'ye render ederken görünüm hakkında bilgi almak için yeni bir ViewInfoOptions sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| extractText | boolean | Metin çıkarma özelliğini etkinleştirir. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


PNG'ye render ederken görünüm hakkında bilgi almak için yeni bir ViewInfoOptions sınıfı örneği başlatır.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


PNG'ye render ederken görünüm hakkında bilgi almak için yeni bir ViewInfoOptions sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| extractText | boolean | Metin çıkarma özelliğini etkinleştirir. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


PDF'ye render edilirken görünüm hakkında bilgi almak için ViewInfoOptions sınıfının yeni bir örneğini başlatır.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.
### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


HtmlViewOptions nesnesine dayalı olarak ViewInfoOptions sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | HTML görünüm seçenekleri. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


ViewInfoOptions sınıfının yeni bir örneğini, [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) nesnesine dayanarak başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | PNG görünüm seçenekleri. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


ViewInfoOptions sınıfının yeni bir örneğini, [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) nesnesine dayanarak başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | JPG görünüm seçenekleri. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) sınıfının yeni bir örneğini, bir PdfViewOptions nesnesine dayanarak başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | PDF görünüm seçenekleri. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.
