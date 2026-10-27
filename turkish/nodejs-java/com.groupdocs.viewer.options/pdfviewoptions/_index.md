---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Belgeleri PDF formatına renderleme seçeneklerini sağlar."
type: docs
weight: 23
url: /tr/nodejs-java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

Belgeleri PDF formatına renderleme seçeneklerini sağlar.

PdfViewOptions sınıfı, GroupDocs.Viewer bileşeninde belgelerin PDF formatına dönüştürülmesini kontrol etmek için kullanılabilecek ek ayarları ve parametreleri kapsar. Ayrıntılar için [belgelendirme][].

Örnek kullanım:

```

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | PdfViewOptions sınıfının yeni bir örneğini başlatır. |
| [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | PdfViewOptions sınıfının yeni bir örneğini başlatır. |
| [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | PdfViewOptions sınıfının yeni bir örneğini başlatır. |
| [PdfViewOptions()](#PdfViewOptions--) | PdfViewOptions sınıfının yeni bir örneğini varsayılan ayarlarla başlatır. |
| [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | PdfViewOptions sınıfının yeni bir örneğini başlatır. |
| [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | PdfViewOptions sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | Farklı seçeneklerle optimizasyon teknikleri uygulayarak çıktı PDF dosya boyutunu azaltın. |
| [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | Farklı seçeneklerle optimizasyon teknikleri uygulayarak çıktı PDF dosya boyutunu azaltın. |
| [getImageMaxWidth()](#getImageMaxWidth--) | Çıktı görüntüsünün piksel cinsinden maksimum genişliğini alır. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Çıktı görüntüsünün piksel cinsinden maksimum genişliğini ayarlar. |
| [getImageMaxHeight()](#getImageMaxHeight--) | Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini alır. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Çıktı görüntüsünün piksel cinsinden maksimum yüksekliğini ayarlar. |
| [getImageWidth()](#getImageWidth--) | Çıktı görüntüsünün piksel cinsinden genişliğini alır. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | Çıktı görüntüsünün piksel cinsinden genişliğini ayarlar. |
| [getImageHeight()](#getImageHeight--) | Çıktı görüntüsünün yüksekliğini piksel olarak alır. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | Çıktı görüntüsünün yüksekliğini piksel olarak ayarlar. |
| [getSecurity()](#getSecurity--) | Çıktı PDF belgesi için güvenlik seçeneklerini alır. |
| [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | Çıktı PDF belgesi için güvenlik seçeneklerini ayarlar. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Bir Words veya Email belgesinin kaydedilme ilerlemesini tahmin etmek için kullanılan geri aramayı alır. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Bir Words veya Email belgesinin kaydedilme ilerlemesini tahmin etmek için kullanılan geri aramayı ayarlar. |
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


PdfViewOptions sınıfının yeni bir örneğini başlatır.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


PdfViewOptions sınıfının yeni bir örneğini başlatır.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | Çıktı dosya verilerini yazmak için akışı başlatmak için kullanılan yöntem. |
| releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | createFileStream yöntemi tarafından oluşturulan akışı serbest bırakmak için kullanılan yöntem. |

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


PdfViewOptions sınıfının yeni bir örneğini başlatır.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | Çıktı dosya akışını oluşturma ve serbest bırakma yöntemlerini uygulayan fabrika. |

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


PdfViewOptions sınıfının yeni bir örneğini varsayılan ayarlarla başlatır.

Bu yapıcı, çıktı dosyası için dosya yolu biçimi olarak "output.pdf" ile yeni bir  PdfViewOptions  nesnesi oluşturur. Çıktı dosyası, uygulamanın geçerli çalışma dizinine yerleştirilecektir. Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


PdfViewOptions sınıfının yeni bir örneğini başlatır.

Bu yapıcı, çıktı PDF dosyasının yolunu temsil eden belirtilen  outputFilePath  parametresiyle yeni bir  PdfViewOptions  nesnesi oluşturur. Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFilePath | java.lang.String | Çıktı PDF dosyasının yolu. |

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


PdfViewOptions sınıfının yeni bir örneğini başlatır.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outputFilePath | java.nio.file.Path | Çıktı PDF dosyasının yolu. |

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


Farklı seçeneklerle optimizasyon teknikleri uygulayarak çıktı PDF dosya boyutunu azaltın.

Bu seçenek, PDF'ye dönüştürme için desteklenen tüm giriş dosya formatları için desteklenir: [Desteklenen belge formatları][] Detaylar ve kod örnekleri için, bu [sayfa][] ve alt sayfalarına bakın.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.
### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


Farklı seçeneklerle optimizasyon teknikleri uygulayarak çıktı PDF dosya boyutunu azaltın.

Bu seçenek, PDF'ye dönüştürme için desteklenen tüm giriş dosya formatları için desteklenir: [Desteklenen belge formatları][] Detaylar ve kod örnekleri için, bu [sayfa][] ve alt sayfalarına bakın.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | PdfOptimizationOptions nesnesi veya null. |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Çıktı görüntüsünün maksimum genişliğini piksel olarak alır. Bu parametre yalnızca tek bir görüntünün HTML'ye dönüştürülmesinde uygulanır.

Bu özelliği, maksimum çıktı görüntüsü genişliğini (piksel olarak) ayarlamak için kullanın. GroupDocs.Viewer, tek bir görüntüyü PDF'ye render ederken bu özelliği uygular. Detaylar için, [belgeleme][]. Özelliği ayarlarsanız, bu özellik yok sayılır.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - çıktı görüntüsünün maksimum genişliği piksel olarak.
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Çıktı görüntüsünün maksimum genişliğini piksel olarak ayarlar. Bu parametre yalnızca tek bir görüntünün HTML'ye dönüştürülmesinde uygulanır.

Bu özelliği, maksimum çıktı görüntüsü genişliğini (piksel olarak) ayarlamak için kullanın. GroupDocs.Viewer, tek bir görüntüyü PDF'ye render ederken bu özelliği uygular. Detaylar için, [belgeleme][]. Özelliği ayarlarsanız, bu özellik yok sayılır.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageMaxWidth | int | Çıktı görüntüsünün maksimum genişliği piksel olarak. |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Çıktı görüntüsünün maksimum yüksekliğini piksel olarak alır. Bu parametre yalnızca tek bir görüntünün HTML'ye dönüştürülmesinde uygulanır.

Bu özelliği, maksimum çıktı görüntüsü yüksekliğini (piksel olarak) ayarlamak için kullanın. GroupDocs.Viewer, tek bir görüntüyü PDF'ye render ederken bu özelliği uygular. Detaylar için, [belgeleme][]. Özelliği ayarlarsanız, bu özellik yok sayılır.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - çıktının maksimum yüksekliği piksel olarak.
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Çıktı görüntüsünün maksimum yüksekliğini piksel cinsinden ayarlar. Bu parametre yalnızca tek bir görüntüyü HTML'ye dönüştürürken uygulanır.

Bu özelliği, maksimum çıktı görüntüsü yüksekliğini (piksel olarak) ayarlamak için kullanın. GroupDocs.Viewer bu özelliği yalnızca tek bir görüntüyü HTML'ye render ederken uygular. Ayrıntılar için [documentation][] belgesine bakın. Bu özelliği ayarlarsanız, bu özellik yok sayılır.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageMaxHeight | int | Çıktı görüntüsünün piksel cinsinden maksimum yüksekliği. |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Çıktı görüntüsünün genişliğini piksel olarak alır. Bu parametre yalnızca tek bir görüntüyü HTML'ye dönüştürürken uygulanır.

Bu özelliği, çıktı görüntüsü genişliğini (piksel olarak) ayarlamak için kullanın. GroupDocs.Viewer bu özelliği tek bir görüntüyü PDF'ye render ederken uygular. Ayrıntılar için [documentation][] belgesine bakın. Bu özelliği ayarlarsanız, bu özellik yok sayılır.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - çıktı görüntüsünün piksel cinsinden genişliği.
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Çıktı görüntüsünün genişliğini piksel olarak ayarlar. Bu parametre yalnızca tek bir görüntüyü PDF'ye dönüştürürken uygulanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageWidth | int | Çıktı görüntüsünün piksel cinsinden genişliği. |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Çıktı görüntüsünün yüksekliğini piksel olarak alır. Bu parametre yalnızca tek bir görüntüyü HTML'ye dönüştürürken uygulanır.

Bu özelliği, çıktı görüntüsü yüksekliğini (piksel olarak) ayarlamak için kullanın. GroupDocs.Viewer bu özelliği yalnızca tek bir görüntüyü HTML'ye render ederken uygular. Ayrıntılar için [documentation][] belgesine bakın. Bu özelliği ayarlarsanız, bu özellik yok sayılır.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - çıktı görüntüsünün piksel cinsinden yüksekliği.
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Çıktı görüntüsünün yüksekliğini piksel olarak ayarlar. Bu parametre yalnızca tek bir görüntüyü HTML'ye dönüştürürken uygulanır.

Bu özelliği, çıktı görüntüsü yüksekliğini (piksel olarak) ayarlamak için kullanın. GroupDocs.Viewer bu özelliği yalnızca tek bir görüntüyü HTML'ye render ederken uygular. Ayrıntılar için [documentation][] belgesine bakın. Bu özelliği ayarlarsanız, bu özellik yok sayılır.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageHeight | int | Çıktı görüntüsünün piksel cinsinden yüksekliği. |

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


Çıktı PDF belgesi için güvenlik seçeneklerini alır.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.
### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


Çıktı PDF belgesi için güvenlik seçeneklerini ayarlar.

Ayrıntılar için, [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Security](../../com.groupdocs.viewer.options/security) | Çıktı PDF belgesi için güvenlik seçenekleri. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Bir Words veya Email belgesinin kaydedilme ilerlemesini tahmin etmek için kullanılan geri aramayı alır.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - belge kaydetme ilerlemesini tahmin etmek için geri çağırma.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Bir Words veya Email belgesinin kaydedilme ilerlemesini tahmin etmek için kullanılan geri aramayı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | Belge kaydetme ilerlemesini tahmin etmek için geri çağırma. |

