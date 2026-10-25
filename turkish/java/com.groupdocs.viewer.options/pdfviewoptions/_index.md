---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Belgeleri PDF formatına dönüştürmek için seçenekler sağlar."
type: docs
weight: 23
url: /tr/java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

Belgeleri PDF formatına dönüştürmek için seçenekler sağlar.


PdfViewOptions sınıfı ek ayarları ve parametreleri kapsar.
belge işleme sürecini PDF formatına dönüştürmeyi GroupDocs.Viewer bileşeninde kontrol etmek için kullanılabilir.
Ayrıntılar için, [belgelere](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) bakın.


Örnek kullanım:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | Yeni bir örnek başlatır |
PdfViewOptions
sınıf.
|
|  | [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | Yeni bir örnek başlatır |
PdfViewOptions
sınıf.
|
|  | [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | PdfViewOptions sınıfının yeni bir örneğini başlatır. |
|
|  | [PdfViewOptions()](#PdfViewOptions--) | PdfViewOptions sınıfının yeni bir örneğini varsayılan ayarlarla başlatır. |
|
|  | [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | Yeni bir örnek başlatır |
PdfViewOptions
sınıf.
|
|  | [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | Yeni bir örnek başlatır |
PdfViewOptions
sınıf.
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | Farklı seçeneklerle optimizasyon teknikleri uygulayarak çıktı PDF dosya boyutunu azaltın. |
|
|  | [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | Farklı seçeneklerle optimizasyon teknikleri uygulayarak çıktı PDF dosya boyutunu azaltın. |
|
|  | [getImageMaxWidth()](#getImageMaxWidth--) | Çıktı görüntüsünün piksel cinsinden maksimum genişliğini alır. |
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
|  | [getImageHeight()](#getImageHeight--) | Çıktı görüntüsünün piksel cinsinden yüksekliğini alır. |
|
|  | [setImageHeight(int imageHeight)](#setImageHeight-int-) | Çıktı görüntüsünün piksel cinsinden yüksekliğini ayarlar. |
|
|  | [getSecurity()](#getSecurity--) | Çıktı PDF belgesi için güvenlik seçeneklerini alır. |
|
|  | [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | Çıktı PDF belgesi için güvenlik seçeneklerini ayarlar. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Words veya Email belgesinin kaydedilme ilerlemesini tahmin etmek için kullanılan geri çağırmayı alır. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Words veya Email belgesinin kaydedilme ilerlemesini tahmin etmek için kullanılan geri çağırmayı ayarlar. |
|
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


Yeni bir örnek başlatır
PdfViewOptions
sınıf.


Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


Yeni bir örnek başlatır
PdfViewOptions
sınıf.


Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | Çıktı dosyası verilerini yazmak için akışı örneklemek amacıyla kullanılan yöntem. |
|
|  | releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | createFileStream yöntemi tarafından oluşturulan akışı serbest bırakmak için kullanılan yöntem. |
|

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


PdfViewOptions sınıfının yeni bir örneğini başlatır.


Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | Çıktı dosyası akışını oluşturma ve serbest bırakma yöntemlerini uygulayan fabrika. |
|

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


PdfViewOptions sınıfının yeni bir örneğini varsayılan ayarlarla başlatır.


Bu yapıcı yeni bir
PdfViewOptions
"output.pdf" dosya yolu biçimiyle çıktı dosyası için bir nesne.
Çıktı dosyası, uygulamanın geçerli çalışma dizinine yerleştirilecektir.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) bakın.


### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


Yeni bir örnek başlatır
PdfViewOptions
sınıf.


Bu yapıcı yeni bir
PdfViewOptions
belirtilen
outputFilePath
parametre
çıktı PDF dosyasının yolunu temsil eder.
Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputFilePath | java.lang.String | Çıktı PDF dosyasının yolu. |
|

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


Yeni bir örnek başlatır
PdfViewOptions
sınıf.


Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | outputFilePath | java.nio.file.Path | Çıktı PDF dosyasının yolu. |
|

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


Farklı seçeneklerle optimizasyon teknikleri uygulayarak çıktı PDF dosya boyutunu azaltın.


Bu seçenek, PDF'ye dönüştürme için desteklenen tüm giriş dosyası biçimleri için desteklenir: [Desteklenen belge biçimleri](../https://docs.groupdocs.com/viewer/net/supported-document-formats/)
Ayrıntılar ve kod örnekleri için bu [sayfaya](../https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) ve alt sayfalarına bakın.


**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.

### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


Farklı seçeneklerle optimizasyon teknikleri uygulayarak çıktı PDF dosya boyutunu azaltın.


Bu seçenek, PDF'ye dönüştürme için desteklenen tüm giriş dosyası biçimleri için desteklenir: [Desteklenen belge biçimleri](../https://docs.groupdocs.com/viewer/net/supported-document-formats/)
Ayrıntılar ve kod örnekleri için bu [sayfaya](../https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) ve alt sayfalarına bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | PdfOptimizationOptions nesnesi veya null. |
|

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Çıktı görüntüsünün piksel cinsinden maksimum genişliğini alır. Bu parametre yalnızca tek bir görüntüyü HTML'ye dönüştürürken uygulanır.


Bu özelliği, maksimum çıktı görüntüsü genişliğini (piksel olarak) ayarlamak için kullanın. GroupDocs.Viewer, tek bir görüntüyü PDF'ye render ederken bu özelliği uygular. Ayrıntılar için [belgelere](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/) bakın.
Özelliği ayarlarsanız, bu özellik yok sayılır.


**Returns:**
int - çıktı görüntüsünün piksel cinsinden maksimum genişliği.

### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Çıktı görüntüsünün piksel cinsinden maksimum genişliğini ayarlar. Bu parametre yalnızca tek bir görüntüyü HTML'ye dönüştürürken uygulanır.


Bu özelliği, maksimum çıktı görüntüsü genişliğini (piksel olarak) ayarlamak için kullanın. GroupDocs.Viewer, tek bir görüntüyü PDF'ye render ederken bu özelliği uygular. Ayrıntılar için [belgelere](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/) bakın.
Özelliği ayarlarsanız, bu özellik yok sayılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | imageMaxWidth | int | Çıktı görüntüsünün piksel cinsinden maksimum genişliği. |
|

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini alır. Bu parametre yalnızca tek bir görüntüyü HTML'ye dönüştürürken uygulanır.


Bu özelliği, maksimum çıktı görüntüsü yüksekliğini (piksel olarak) ayarlamak için kullanın. GroupDocs.Viewer, tek bir görüntüyü PDF'ye render ederken bu özelliği uygular. Ayrıntılar için [belgelere](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/) bakın.
Özelliği ayarlarsanız, bu özellik yok sayılır.


**Returns:**
int - çıktı görüntüsünün piksel cinsinden maksimum yüksekliği.

### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini ayarlar. Bu parametre yalnızca tek bir görüntüyü HTML'ye dönüştürürken uygulanır.


Bu özelliği, maksimum çıktı görüntüsü yüksekliğini (piksel olarak) ayarlamak için kullanın. GroupDocs.Viewer bu özelliği yalnızca tek bir görüntüyü HTML'ye render ederken uygular. Ayrıntılar için [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/) bağlantısına bakın.
Özelliği ayarlarsanız, bu özellik yok sayılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | imageMaxHeight | int | Çıktı görüntüsünün piksel cinsinden maksimum yüksekliği. |
|

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Çıktı görüntüsünün piksel cinsinden genişliğini alır. Bu parametre yalnızca tek bir görüntüyü HTML'ye dönüştürürken uygulanır.


Bu özelliği, çıktı görüntüsü genişliğini (piksel olarak) ayarlamak için kullanın. GroupDocs.Viewer bu özelliği tek bir görüntüyü PDF'ye render ederken uygular. Ayrıntılar için [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/) bağlantısına bakın.
Bu özelliği ayarlarsanız, özellik yok sayılır.


**Returns:**
int - çıktı görüntüsünün piksel cinsinden genişliği.

### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Çıktı görüntüsünün piksel cinsinden genişliğini ayarlar. Bu parametre yalnızca tek bir görüntü PDF'si dönüştürülürken uygulanır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | imageWidth | int | Çıktı görüntüsünün piksel cinsinden genişliği. |
|

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Çıktı görüntüsünün piksel cinsinden yüksekliğini alır. Bu parametre yalnızca tek bir görüntüyü HTML'ye dönüştürürken uygulanır.


Bu özelliği, çıktı görüntüsü yüksekliğini (piksel olarak) ayarlamak için kullanın. GroupDocs.Viewer bu özelliği yalnızca tek bir görüntüyü HTML'ye render ederken uygular. Ayrıntılar için [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/) bağlantısına bakın.
Bu özelliği ayarlarsanız, özellik yok sayılır.


**Returns:**
int - çıktı görüntüsünün piksel cinsinden yüksekliği.

### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Çıktı görüntüsünün piksel cinsinden yüksekliğini ayarlar. Bu parametre yalnızca tek bir görüntüyü HTML'ye dönüştürürken uygulanır.


Bu özelliği, çıktı görüntüsü yüksekliğini (piksel olarak) ayarlamak için kullanın. GroupDocs.Viewer bu özelliği yalnızca tek bir görüntüyü HTML'ye render ederken uygular. Ayrıntılar için [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/) bağlantısına bakın.
Bu özelliği ayarlarsanız, özellik yok sayılır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | imageHeight | int | Çıktı görüntüsünün piksel cinsinden yüksekliği. |
|

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


Çıktı PDF belgesi için güvenlik seçeneklerini alır.


Ayrıntılar için [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/) bağlantısına bakın.


**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.

### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


Çıktı PDF belgesi için güvenlik seçeneklerini ayarlar.


Ayrıntılar için [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/) bağlantısına bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Security](../../com.groupdocs.viewer.options/security) | Çıktı PDF belgesi için güvenlik seçenekleri. |
|

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Words veya Email belgesinin kaydedilme ilerlemesini tahmin etmek için kullanılan geri çağırmayı alır.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - belge kaydetme ilerlemesini tahmin etmek için geri arama.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Words veya Email belgesinin kaydedilme ilerlemesini tahmin etmek için kullanılan geri çağırmayı ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Belge kaydetme ilerlemesini tahmin etmek için geri arama. |
|

