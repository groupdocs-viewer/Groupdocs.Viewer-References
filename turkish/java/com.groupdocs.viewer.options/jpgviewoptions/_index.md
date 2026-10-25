---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Belgeleri JPG formatına işlemek için seçenekler sunar."
type: docs
weight: 17
url: /tr/java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

Belgeleri JPG formatına işlemek için seçenekler sunar.


JpgViewOptions sınıfı, belgelerin işlenmesini kontrol etmek için kullanılabilecek ek ayarları ve parametreleri kapsüller.
GroupDocs.Viewer bileşeninde JPG formatına.


Örnek kullanım:

````

 JpgViewOptions options = new JpgViewOptions();
 options.setMaxWidth(1920);
 options.setMaxHeight(1080);
 options.setQuality((byte) 96);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The JpgViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output JPG images.*

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Yeni bir örnek başlatır |
JpgViewOptions
sınıf.
|
|  | [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Yeni bir örnek başlatır |
JpgViewOptions
sınıf.
|
|  | [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Yeni bir örnek başlatır |
JpgViewOptions
sınıf.
|
|  | [JpgViewOptions()](#JpgViewOptions--) | Yeni bir örnek başlatır |
JpgViewOptions
çıktı dosyaları için dosya yolu biçimi olarak "p_{0}.jpg" ile.
|
|  | [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | Yeni bir örnek başlatır |
JpgViewOptions
sınıf.
|
|  | [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | Yeni bir örnek başlatır |
JpgViewOptions
sınıf.
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | Çıktı görüntüsünün piksel cinsinden maksimum genişliğini alır. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Çıktı görüntüsünün piksel cinsinden maksimum genişliğini ayarlar. |
|
|  | [getMaxHeight()](#getMaxHeight--) | Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini alır. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini ayarlar. |
|
|  | [getQuality()](#getQuality--) | Çıktı görüntüsünün kalitesini alır. |
|
|  | [setQuality(byte value)](#setQuality-byte-) | Çıktı görüntüsünün kalitesini ayarlar. |
|
|  | [isExtractText()](#isExtractText--) | Metin çıkarma özelliğini etkinleştirir. |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | Metin çıkarımını etkinleştirir veya devre dışı bırakır. |
|
|  | [getWidth()](#getWidth--) | Çıktı görüntüsünün piksel cinsinden genişliğini alır. |
|
|  | [setWidth(int value)](#setWidth-int-) | Çıktı görüntüsünün piksel cinsinden genişliğini ayarlar. |
|
|  | [getHeight()](#getHeight--) | Çıktı görüntüsünün piksel cinsinden yüksekliğini alır. |
|
|  | [setHeight(int value)](#setHeight-int-) | Çıktı görüntüsünün piksel cinsinden yüksekliğini ayarlar. |
|
|  | [getPageStreamFactory()](#getPageStreamFactory--) | Çıktı sayfa akışını oluşturmak ve serbest bırakmak için yöntemleri uygulayan fabrikayı alır. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Words veya Email belgesinin kaydetme ilerlemesini tahmin etmek için geri aramayı alır. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Words veya Email belgesinin kaydetme ilerlemesini tahmin etmek için geri aramayı ayarlar. |
|
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


Yeni bir örnek başlatır
JpgViewOptions
sınıf.


Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Çıktı sayfa verilerini yazmak için kullanılan akışı örnekleyen yöntem. |
|

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Yeni bir örnek başlatır
JpgViewOptions
sınıf.


Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | Çıktı sayfa verilerini yazmak için kullanılan akışı örnekleyen yöntem. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | delegate'e geçirilen createPageStream parametresine atanan metoda atanan yöntemin oluşturduğu akışı serbest bırakan yöntem. |
|

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


Yeni bir örnek başlatır
JpgViewOptions
sınıf.


Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | Çıktı sayfa akışını oluşturma ve serbest bırakma yöntemlerini uygulayan fabrika. |
|

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


Yeni bir örnek başlatır
JpgViewOptions
çıktı dosyaları için dosya yolu biçimi olarak "p_{0}.jpg" ile.
Çıktı dosyaları, uygulamanın geçerli çalışma dizinine yerleştirilecektir.


Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg) adresine bakın.


### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


Yeni bir örnek başlatır
JpgViewOptions
sınıf.


Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | Dosya yolu biçimi, ör. 'page_{0}.jpg'. |
|

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


Yeni bir örnek başlatır
JpgViewOptions
sınıf.


Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | Dosya yolu biçimi, ör. 'page_{0}.jpg'. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Çıktı görüntüsünün piksel cinsinden maksimum genişliğini alır.


Bu özelliği, maksimum çıktı görüntüsü genişliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için [belgelere](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/) bakın.
Eğer #setWidth(int).setWidth(int) özelliğini ayarlarsanız, bu özellik yok sayılır.


**Returns:**
int - çıktının maksimum genişliği.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Çıktı görüntüsünün piksel cinsinden maksimum genişliğini ayarlar.


Bu özelliği, maksimum çıktı görüntüsü genişliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için [belgelere](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/) bakın.
Eğer #setWidth(int).setWidth(int) özelliğini ayarlarsanız, bu özellik yok sayılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | maxWidth | int | Çıktının maksimum genişliği. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini alır.


Bu özelliği, maksimum çıktı görüntüsü yüksekliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için, [belgeleme](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/) sayfasına bakın.
Eğer #setHeight(int).setHeight(int) özelliğini ayarlarsanız, bu özellik yok sayılır.


**Returns:**
int - çıktının maksimum yüksekliği.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini ayarlar.


Bu özelliği, maksimum çıktı görüntüsü yüksekliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için, [belgeleme](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/) sayfasına bakın.
Eğer #setHeight(int).setHeight(int) özelliğini ayarlarsanız, bu özellik yok sayılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | maxHeight | int | Çıktının maksimum yüksekliği. |
|

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


Çıktı görüntüsünün kalitesini alır.


***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.*
Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/) adresine bakın.


**Returns:**
byte - çıktının görüntü kalitesi.

### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


Çıktı görüntüsünün kalitesini ayarlar.


***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.*
Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/) adresine bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | byte | Çıktı görüntüsünün kalitesi. |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Metin çıkarma özelliğini etkinleştirir.


***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.*
Kod örneği için, [belgeleme](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/) sayfasına bakın.


**Returns:**
boolean -  true  metin çıkarma etkinse,  false  aksi takdirde.

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Metin çıkarımını etkinleştirir veya devre dışı bırakır.


***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.*
Kod örneği için, [belgeleme](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/) sayfasına bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | boolean | true  metin çıkarmayı etkinleştirmek için,  false  devre dışı bırakmak için. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Çıktı görüntüsünün piksel cinsinden genişliğini alır.


Bu özelliği, çıktı görüntüsü genişliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için, [belgeleme](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/) sayfasına bakın.
Bu özelliği ayarlarsanız, #setMaxWidth(int).setMaxWidth(int) özelliği yok sayılır.


**Returns:**
int - çıktının genişliği.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Çıktı görüntüsünün piksel cinsinden genişliğini ayarlar.


Bu özelliği, çıktı görüntüsü genişliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için, [belgeleme](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/) sayfasına bakın.
Bu özelliği ayarlarsanız, #setMaxWidth(int).setMaxWidth(int) özelliği yok sayılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | int | Çıktı görüntüsünün genişliği. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Çıktı görüntüsünün piksel cinsinden yüksekliğini alır.


Bu özelliği, çıktı görüntüsü yüksekliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için, [belgeleme](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/) sayfasına bakın.
Bu özelliği ayarlarsanız, #setMaxHeight(int).setMaxHeight(int) özelliği yok sayılır.


**Returns:**
int - çıktı görüntüsünün yüksekliği.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Çıktı görüntüsünün piksel cinsinden yüksekliğini ayarlar.


Bu özelliği, çıktı görüntüsü yüksekliğini (piksel cinsinden) ayarlamak için kullanın. Kod örneği için, [belgeleme](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/) sayfasına bakın.
Bu özelliği ayarlarsanız, #setMaxHeight(int).setMaxHeight(int) özelliği yok sayılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | int | Çıktı görüntüsünün yüksekliği. |
|

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


Çıktı sayfa akışını oluşturmak ve serbest bırakmak için yöntemleri uygulayan fabrikayı alır.


**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) - the factory for the output page stream.

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Words veya Email belgesinin kaydetme ilerlemesini tahmin etmek için geri aramayı alır.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - belge kaydetme ilerlemesini tahmin etmek için geri arama.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Words veya Email belgesinin kaydetme ilerlemesini tahmin etmek için geri aramayı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Belge kaydetme ilerlemesini tahmin etmek için geri arama. |
|

