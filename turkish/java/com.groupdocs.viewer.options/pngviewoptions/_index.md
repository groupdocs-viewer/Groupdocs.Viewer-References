---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Belgeleri PNG formatına dönüştürmek için seçenekler sağlar."
type: docs
weight: 25
url: /tr/java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

Belgeleri PNG formatına dönüştürmek için seçenekler sağlar.


PngViewOptions sınıfı, kullanılabilecek ek ayarları ve parametreleri kapsar
GroupDocs.Viewer bileşeninde belgelerin PNG formatına render edilmesini kontrol etmek için.


Örnek kullanım:

````

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.*
Ayrıntılar için bu [sayfaya](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/) ve alt sayfalara bakın.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Yeni bir örnek başlatır |
PngViewOptions
sınıf.
|
|  | [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Yeni bir örnek başlatır |
PngViewOptions
sınıf.
|
|  | [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Yeni bir örnek başlatır |
PngViewOptions
sınıf.
|
|  | [PngViewOptions()](#PngViewOptions--) | Yeni bir örnek başlatır |
PngViewOptions
sınıf.
|
|  | [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | Yeni bir örnek başlatır |
PngViewOptions
sınıf.
|
|  | [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | Yeni bir örnek başlatır |
PngViewOptions
sınıf.
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | Çıktı görüntüsünün piksel cinsinden maksimum genişliğini döndürür. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Çıktı görüntüsünün piksel cinsinden maksimum genişliğini ayarlar. |
|
|  | [getMaxHeight()](#getMaxHeight--) | Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini döndürür. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini ayarlar. |
|
|  | [isExtractText()](#isExtractText--) | Metin çıkarımının etkin olup olmadığını belirler. |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | Metin çıkarımını etkinleştirir veya devre dışı bırakır. |
|
|  | [getWidth()](#getWidth--) | Çıktı görüntüsünün piksel cinsinden genişliğini döndürür. |
|
|  | [setWidth(int value)](#setWidth-int-) | Çıktı görüntüsünün piksel cinsinden genişliğini ayarlar. |
|
|  | [getHeight()](#getHeight--) | Çıktı görüntüsünün piksel cinsinden yüksekliğini döndürür. |
|
|  | [setHeight(int value)](#setHeight-int-) | Çıktı görüntüsünün piksel cinsinden yüksekliğini ayarlar. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Bir belgenin kaydetme ilerlemesini tahmin etmek için geri aramayı alır. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Bir belgenin kaydetme ilerlemesini tahmin etmek için geri aramayı ayarlar. |
|
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


Yeni bir örnek başlatır
PngViewOptions
sınıf.


Kod örneği için [belgelere](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Çıktı sayfa verilerini yazmak için kullanılan akışı örnekleyen yöntem. |
|

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Yeni bir örnek başlatır
PngViewOptions
sınıf.


Kod örneği için [belgelere](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Çıktı sayfa verilerini yazmak için kullanılan akışı örnekleyen yöntem. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | createPageStream parametresine atanmış yöntem tarafından oluşturulan akışı serbest bırakan yöntem. |
|

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


Yeni bir örnek başlatır
PngViewOptions
sınıf.


Kod örneği için [belgelere](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Çıktı sayfa akışını oluşturma ve serbest bırakma yöntemlerini uygulayan fabrika. |
|

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


Yeni bir örnek başlatır
PngViewOptions
sınıf.


Bu yapıcı, yeni bir örnek başlatır
PngViewOptions

çıktı dosyaları için dosya yolu biçimi olarak "p_{0}.png" ile.
Çıktı dosyaları, uygulamanın geçerli çalışma dizinine yerleştirilecektir.
Kod örneği için [belgelere](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png) bakın.


### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


Yeni bir örnek başlatır
PngViewOptions
sınıf.


Örneğin, dosya yolu biçimi 'page_{0}.png' ise, çıktı dosyaları
sayfa numarasına göre 'page_1.png', 'page_2.png' vb. olarak adlandırılacaktır.


***Note:** It is important to note that the output files will be placed into the current working directory of the application.*
Kod örneği için [belgelere](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Dosya yolu biçimi, örn., 'page_{0}.png'. |
|

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


Yeni bir örnek başlatır
PngViewOptions
sınıf.


Örneğin, dosya yolu biçimi 'page_{0}.png' ise, çıktı dosyaları
sayfa numarasına göre 'page_1.png', 'page_2.png' vb. olarak adlandırılacaktır.
Kod örneği için [belgelere](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | Dosya yolu biçimi, örn., 'page_{0}.png'. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Çıktı görüntüsünün piksel cinsinden maksimum genişliğini döndürür.


Bu özelliği, maksimum çıktı görüntüsü genişliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için [belgelere](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/) bakın.
Özelliği ayarlarsanız, bu özellik yok sayılır.


**Returns:**
int - çıktı görüntüsünün maksimum genişliği.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Çıktı görüntüsünün piksel cinsinden maksimum genişliğini ayarlar.


Bu özelliği, maksimum çıktı görüntüsü genişliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için [belgelere](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/) bakın.
Özelliği ayarlarsanız, bu özellik yok sayılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | maxWidth | int | Çıktı görüntüsünün maksimum genişliği. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini döndürür.


Bu özelliği, maksimum çıktı görüntüsü yüksekliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için, [belgeleme](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/) sayfasına bakın.
Özelliği ayarlarsanız, bu özellik yok sayılır.


**Returns:**
int - çıktı görüntüsünün maksimum yüksekliği.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini ayarlar.


Bu özelliği, maksimum çıktı görüntüsü yüksekliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için, [belgeleme](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/) sayfasına bakın.
Özelliği ayarlarsanız, bu özellik yok sayılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | maxHeight | int | Çıktı görüntüsünün maksimum yüksekliği. |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Metin çıkarımının etkin olup olmadığını belirler.


Bu seçenek, görüntünün üzerine seçilebilir bir metin katmanı eklemek istediğinizde faydalı olabilir.
Bu özelliği, kaynak belgede bulunan metni ve koordinatlarını almak için kullanın. Ardından bu verileri, görüntünün üzerine seçilebilir bir metin eklemek veya görüntü tabanlı renderlamada metin araması uygulamak için kullanabilirsiniz.
Kod örneği için, [belgeleme](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/) sayfasına bakın.


**Returns:**
boolean -  true  metin çıkarma etkinse,  false  aksi takdirde.

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Metin çıkarımını etkinleştirir veya devre dışı bırakır.


Bu seçenek, görüntünün üzerine seçilebilir bir metin katmanı eklemek istediğinizde faydalı olabilir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  metin çıkarmayı etkinleştirmek için,  false  devre dışı bırakmak için. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Çıktı görüntüsünün piksel cinsinden genişliğini döndürür.


Bu özelliği, çıktı görüntüsü genişliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için, [belgeleme](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/) sayfasına bakın.
Bu özelliği ayarlarsanız, özellik yok sayılır.


**Returns:**
int - çıktının genişliği.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Çıktı görüntüsünün piksel cinsinden genişliğini ayarlar.


Bu özelliği, çıktı görüntüsü genişliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için, [belgeleme](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/) sayfasına bakın.
Bu özelliği ayarlarsanız, özellik yok sayılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | int | Çıktı görüntüsünün genişliği. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Çıktı görüntüsünün piksel cinsinden yüksekliğini döndürür.


Bu özelliği, çıktı görüntüsü yüksekliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için, [belgeleme](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/) sayfasına bakın.
Bu özelliği ayarlarsanız, özellik yok sayılır.


**Returns:**
int - çıktı görüntüsünün yüksekliği.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Çıktı görüntüsünün piksel cinsinden yüksekliğini ayarlar.


Bu özelliği, çıktı görüntüsü yüksekliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için, [belgeleme](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/) sayfasına bakın.
Bu özelliği ayarlarsanız, özellik yok sayılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | int | Çıktı görüntüsünün yüksekliği. |
|

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Bir belgenin kaydetme ilerlemesini tahmin etmek için geri aramayı alır.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - belge kaydetme ilerlemesini tahmin etmek için geri arama.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Bir belgenin kaydetme ilerlemesini tahmin etmek için geri aramayı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Belge kaydetme ilerlemesini tahmin etmek için geri arama. |
|

