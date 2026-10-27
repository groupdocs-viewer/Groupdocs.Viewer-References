---
title: "Viewer"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Belge işleme sürecini kontrol eden ana sınıfı temsil eder."
type: docs
weight: 12
url: /tr/nodejs-java/com.groupdocs.viewer/viewer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Viewer implements Closeable
```

Belge işleme sürecini kontrol eden ana sınıfı temsil eder.

Viewer sınıfı, GroupDocs.Viewer bileşeni kullanılarak belgeleri renderlemek için giriş noktasıdır. Belgeleri çeşitli kaynaklardan yüklemek, renderleme sürecini özelleştirmek ve renderlenmiş çıktıyı farklı formatlarda almak için yöntemler ve seçenekler sunar.

Örnek kullanım:

```

 try (Viewer viewer = new Viewer("source.pdf")) {
     viewer.view(new PngViewOptions("result-page{0}.png"));
 }
 
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Viewer(InputStream fileStream)](#Viewer-java.io.InputStream-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(InputStream fileStream, boolean leaveOpen)](#Viewer-java.io.InputStream-boolean-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(InputStream fileStream, LoadOptions loadOptions)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(InputStream fileStream, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(URL url)](#Viewer-java.net.URL-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(URL url, LoadOptions loadOptions)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(URL url, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(FileReader fileReader, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(String filePath)](#Viewer-java.lang.String-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(Path filePath)](#Viewer-java.nio.file.Path-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(String filePath, LoadOptions loadOptions)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(Path filePath, LoadOptions loadOptions)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(String filePath, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(Path filePath, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer sınıfının yeni bir örneğini başlatır. |
| [Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Viewer sınıfının yeni bir örneğini başlatır. |
## Fields

| Field | Açıklama |
| --- | --- |
| [LOAD_OPTIONS](#LOAD-OPTIONS) |  |
| [SETTINGS](#SETTINGS) |  |
| [FILE_READER](#FILE-READER) |  |
| [OPTIONS](#OPTIONS) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getViewInfo(ViewInfoOptions options)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-) | Görünüm ve belgeye özgü bilgiler hakkında bilgi döndürür. |
| [getAttachments()](#getAttachments--) | Belge içinde bulunan ekleri döndürür. |
| [saveAttachment(Attachment attachment, OutputStream destination)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-) | Bir ek dosyasını hedef akışa kaydeder. |
| [view(ViewOptions options)](#view-com.groupdocs.viewer.options.ViewOptions-) | Tüm belge sayfalarının bir görünümünü oluşturur. |
| [view(ViewOptions options, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-int...-) | Belirli belge sayfalarının bir görünümünü oluşturur. |
| [getAllFonts()](#getAllFonts--) | Yüklenen belgelerde kullanılan tüm yazı tiplerini döndürür; belgeye gömülü olanlar ve işletim sistemine kurulu olup belgede kullanılan sistem yazı tipleri dahil. |
| [search(SearchHighlightOptions options)](#search-com.groupdocs.viewer.options.SearchHighlightOptions-) | Sağlanan seçeneklere göre yüklü belgede metin araması yapar ve eşleşmeleri (bulunursa) vurgular. |
| [getFileInfo()](#getFileInfo--) | Dosya hakkında bilgi döndürür; dosya türü ve dosyanın şifreli olup olmadığını gösteren bir işaret gibi. |
| [close()](#close--) | Dosya akışını ve yönetilen iç kaynakları serbest bırakır. |
### Viewer(InputStream fileStream) {#Viewer-java.io.InputStream-}
```
public Viewer(InputStream fileStream)
```


Viewer sınıfının yeni bir örneğini başlatır.

GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [Document formats supported by GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileStream | java.io.InputStream | Okunabilir bir akış döndüren yöntem. |

### Viewer(InputStream fileStream, boolean leaveOpen) {#Viewer-java.io.InputStream-boolean-}
```
public Viewer(InputStream fileStream, boolean leaveOpen)
```


Viewer sınıfının yeni bir örneğini başlatır.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileStream | java.io.InputStream | Dosya akışı. |
| leaveOpen | boolean | Viewer nesnesi imha edildikten sonra akışı açık bırakmak için true; aksi takdirde false. |

### Viewer(InputStream fileStream, LoadOptions loadOptions) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions)
```


Viewer sınıfının yeni bir örneğini başlatır.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileStream | java.io.InputStream | Okunabilir akış. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Belge yükleme seçenekleri. |

### Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)
```


Viewer sınıfının yeni bir örneğini başlatır.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileStream | java.io.InputStream | Dosya akışı. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Belge yükleme seçenekleri. |
| leaveOpen | boolean | Viewer nesnesi imha edildikten sonra akışı açık bırakmak için true; aksi takdirde false. |

### Viewer(InputStream fileStream, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, ViewerSettings settings)
```


Viewer sınıfının yeni bir örneğini başlatır.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileStream | java.io.InputStream | Dosya akışı. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer ayarları. |

### Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)
```


Viewer sınıfının yeni bir örneğini başlatır.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileStream | java.io.InputStream | Dosya akışı. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer ayarları. |
| leaveOpen | boolean | Viewer nesnesi imha edildikten sonra akışı açık bırakmak için true; aksi takdirde false. |

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer sınıfının yeni bir örneğini başlatır.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileStream | java.io.InputStream | Dosya akışı. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Belge yükleme seçenekleri. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer ayarları. |

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)
```


Viewer sınıfının yeni bir örneğini başlatır.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileStream | java.io.InputStream | Dosya akışı. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Belge yükleme seçenekleri. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer ayarları. |
| leaveOpen | boolean | Viewer nesnesi imha edildikten sonra akışı açık bırakmak için true; aksi takdirde false. |

### Viewer(URL url) {#Viewer-java.net.URL-}
```
public Viewer(URL url)
```


Viewer sınıfının yeni bir örneğini başlatır.

GroupDocs.Viewer tarafından desteklenen dosya türleri hakkında daha fazla bilgi: [Document formats supported by GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | java.net.URL | Viewer içine yüklenmesi gereken bir dosyaya ait URL. |

### Viewer(URL url, LoadOptions loadOptions) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(URL url, LoadOptions loadOptions)
```


Viewer sınıfının yeni bir örneğini başlatır.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | java.net.URL | Viewer içine yüklenmesi gereken bir dosyaya ait URL. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Belge yükleme seçenekleri. |

### Viewer(URL url, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, ViewerSettings settings)
```


Viewer sınıfının yeni bir örneğini başlatır.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | java.net.URL | Viewer içine yüklenmesi gereken bir dosyaya ait URL. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer ayarları. |

### Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer sınıfının yeni bir örneğini başlatır.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| url | java.net.URL | Viewer içine yüklenmesi gereken bir dosyaya ait URL. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Belge yükleme seçenekleri. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer ayarları. |

### Viewer(FileReader fileReader, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, ViewerSettings settings)
```


Viewer sınıfının yeni bir örneğini başlatır.

Bu yapıcı, belirtilen [ViewerSettings](../../com.groupdocs.viewer/viewersettings) ile bir [FileReader](../../com.groupdocs.viewer.interfaces/filereader) üzerinden belge görüntülemek için bir Viewer nesnesi oluşturmanıza olanak tanır.

 **Learn more**

 *  To learn about the file types supported by GroupDocs.Viewer, visit: [Document formats supported by GroupDocs.Viewer][]
 *  To explore the features of GroupDocs.Viewer for Java, refer to: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | Viewer içine yüklenecek belgeyi içeren [FileReader](../../com.groupdocs.viewer.interfaces/filereader). |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer'a uygulanacak [ViewerSettings](../../com.groupdocs.viewer/viewersettings). |

### Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer sınıfının yeni bir örneğini başlatır.

GroupDocs.Viewer kullanarak belgeleri yükleme ve görüntüleme işlevselliği sağlar.

**Note:** Ensure that the file reader, load options, and settings are properly configured for accurate document processing.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | Dosya okuyucu. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Yükleme seçenekleri. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer ayarları. |

### Viewer(String filePath) {#Viewer-java.lang.String-}
```
public Viewer(String filePath)
```


Viewer sınıfının yeni bir örneğini başlatır.

 **Learn more:**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Render edilecek dosyanın yolu. |

### Viewer(Path filePath) {#Viewer-java.nio.file.Path-}
```
public Viewer(Path filePath)
```


Viewer sınıfının yeni bir örneğini başlatır.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.nio.file.Path | Render edilecek dosyanın yolu. |

### Viewer(String filePath, LoadOptions loadOptions) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(String filePath, LoadOptions loadOptions)
```


Viewer sınıfının yeni bir örneğini başlatır.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Render edilecek dosyanın yolu. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Belge yükleme seçenekleri. |

### Viewer(Path filePath, LoadOptions loadOptions) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(Path filePath, LoadOptions loadOptions)
```


Viewer sınıfının yeni bir örneğini başlatır.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view a document with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view a document with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.nio.file.Path | Render edilecek dosyanın yolu. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Belge yükleme seçenekleri. |

### Viewer(String filePath, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, ViewerSettings settings)
```


Viewer sınıfının yeni bir örneğini başlatır.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Render edilecek dosyanın yolu. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer ayarları. |

### Viewer(Path filePath, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, ViewerSettings settings)
```


Viewer sınıfının yeni bir örneğini başlatır.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.nio.file.Path | Render edilecek dosyanın yolu. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer ayarları. |

### Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer sınıfının yeni bir örneğini başlatır.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view documents with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Render edilecek dosyanın yolu. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Belge yükleme seçenekleri. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer ayarları. |

### Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Viewer sınıfının yeni bir örneğini başlatır.

 **Learn more**

 *  More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer][]
 *  More about GroupDocs.Viewer for Java features: [Developer Guide][]
 *  More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer][]


[Document formats supported by GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats
[Developer Guide]: https://docs.groupdocs.com/display/viewerjava/Developer+Guide
[How to load and view documents with GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Loading

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.nio.file.Path | Render edilecek dosyanın yolu. |
| loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Belge yükleme seçenekleri. |
| settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Viewer ayarları. |

### LOAD_OPTIONS {#LOAD-OPTIONS}
```
public static final String LOAD_OPTIONS
```


### SETTINGS {#SETTINGS}
```
public static final String SETTINGS
```


### FILE_READER {#FILE-READER}
```
public static final String FILE_READER
```


### OPTIONS {#OPTIONS}
```
public static final String OPTIONS
```


### getViewInfo(ViewInfoOptions options) {#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-}
```
public final ViewInfo getViewInfo(ViewInfoOptions options)
```


Görünüm ve belgeye özgü bilgiler hakkında bilgi döndürür.

 **Learn more:**

 *  Learn more about the document - file type, page count, and other format specific properties: [How to get file information using GroupDocs.Viewer][]


[How to get file information using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Get+file+information

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | Görünüm bilgisi seçenekleri. |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.
### getAttachments() {#getAttachments--}
```
public final List<Attachment> getAttachments()
```


Belge içinde bulunan ekleri döndürür.

 **Learn more:**

 *  Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer][]
 *  Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer][]


[How to get a list of document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Get+attachments
[How to save document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Save+attachments

**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - belge tarafından içerilen ekler.
### saveAttachment(Attachment attachment, OutputStream destination) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-}
```
public void saveAttachment(Attachment attachment, OutputStream destination)
```


Bir ek dosyasını hedef akışa kaydeder.

 **Learn more:**

 *  Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer][]
 *  Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer][]


[How to get a list of document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Get+attachments
[How to save document attachments using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Save+attachments

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | Ek. |
| hedef | java.io.OutputStream | Yazılabilir akış. |

### view(ViewOptions options) {#view-com.groupdocs.viewer.options.ViewOptions-}
```
public final void view(ViewOptions options)
```


Tüm belge sayfalarının bir görünümünü oluşturur.

 **Learn more**

 *  Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer][]


[How to customize document viewing output using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Viewing

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Görünüm seçenekleri. |

### view(ViewOptions options, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-int...-}
```
public final void view(ViewOptions options, int[] pageNumbers)
```


Belirli belge sayfalarının bir görünümünü oluşturur.

 **Learn more**

 *  Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer][]


[How to customize document viewing output using GroupDocs.Viewer]: https://docs.groupdocs.com/display/viewerjava/Viewing

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Görünüm seçenekleri. |
| pageNumbers | int[] | Görüntülenecek sayfa numaraları. |

### getAllFonts() {#getAllFonts--}
```
public IFontInfo[] getAllFonts()
```


Yüklenen belgelerde kullanılan tüm yazı tiplerini döndürür; belgeye gömülü olanlar ve işletim sistemine kurulu olup belgede kullanılan sistem yazı tipleri dahil.

Ayrıntılar için, [ documentation][documentation] adresine bakın.


[documentation]: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

**Returns:**
com.groupdocs.viewer.fonts.IFontInfo[] - Bu [Viewer](../../com.groupdocs.viewer/viewer) örneğine yüklenen belgede kullanılan tüm yazı tiplerinin null olmayan listesi.
### search(SearchHighlightOptions options) {#search-com.groupdocs.viewer.options.SearchHighlightOptions-}
```
public void search(SearchHighlightOptions options)
```


Sağlanan seçeneklere göre yüklü belgede metin araması yapar ve eşleşmeleri (bulunursa) vurgular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| seçenekler | com.groupdocs.viewer.options.SearchHighlightOptions | Arama ve vurgulama seçenekleri, içinde aranacak bir metin ifadesi de bulunur. Null olamaz. |

### getFileInfo() {#getFileInfo--}
```
public FileInfo getFileInfo()
```


Dosya hakkında bilgi döndürür; dosya türü ve dosyanın şifreli olup olmadığını gösteren bir işaret gibi.

**Learn more:**

 *  Learn more about how to check if a file is encrypted: [How to check if a file is encrypted][]


[How to check if a file is encrypted]: https://docs.groupdocs.com/viewer/net/how-to-check-if-file-is-encrypted/

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - the file information.
### close() {#close--}
```
public final void close()
```


Dosya akışını ve yönetilen iç kaynakları serbest bırakır.

