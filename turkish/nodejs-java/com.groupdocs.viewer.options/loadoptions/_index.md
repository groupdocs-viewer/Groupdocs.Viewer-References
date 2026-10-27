---
title: "LoadOptions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "Bir dosyayı açmak için kullanılan seçenekleri sağlar."
type: docs
weight: 18
url: /tr/nodejs-java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Bir dosyayı açmak için kullanılan seçenekleri sağlar.

LoadOptions sınıfı, bir dosyanın GroupDocs.Viewer bileşeninde nasıl açılacağını ve yükleneceğini belirlemek için kullanılabilecek çeşitli ayarları ve parametreleri kapsüller. Ayrıntılar için bu [sayfa][] ve alt öğelerine bakın.

Örnek kullanım:

```

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/loading/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | LoadOptions sınıfının yeni bir örneğini başlatır. |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | LoadOptions sınıfının yeni bir örneğini başlatır. |
## Fields

| Field | Açıklama |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isTryRepair()](#isTryRepair--) | Etkinleştirildiğinde, GroupDocs.Viewer PDF belgelerindeki yapısal bozulmaları onarmaya çalışır. |
| [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | Etkinleştirildiğinde, GroupDocs.Viewer PDF belgelerindeki yapısal bozulmaları onarmaya çalışır. |
| [getFileType()](#getFileType--) | Açılacak dosyanın türünü alır. |
| [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | Açılacak dosyanın türünü ayarlar. |
| [getPassword()](#getPassword--) | Şifreli bir dosyayı açmak için şifreyi alır. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Şifreli bir dosyayı açmak için şifreyi ayarlar. |
| [getCharset()](#getCharset--) | Metin tabanlı dosyalar veya [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) ve [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG) gibi e-posta mesajları açılırken kullanılan karakter kümesi. |
| [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | Metin tabanlı dosyalar veya [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) ve [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG) gibi e-posta mesajları açılırken kullanılan karakter kümesi. |
| [isDetectCharset()](#isDetectCharset--) | Bu seçenek, [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) ve [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) dosyalarının karakter kümesi algılamasını etkinleştirir. |
| [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | Bu seçenek, [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) ve [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) dosyalarının karakter kümesi algılamasını etkinleştirir. |
| [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Harici kaynakların yüklenmesi için zaman aşımını alır. |
| [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | Grafikler gibi harici kaynakların yüklenmesi için zaman aşımını ayarlar. |
| [getUrlConnectTimeout()](#getUrlConnectTimeout--) | java.net.URL kullanarak bir belge yüklemek için bir [Viewer](../../com.groupdocs.viewer/viewer) oluştururken bağlantı zaman aşımını alır. |
| [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | java.net.URL kullanarak bir belge yüklemek için bir [Viewer](../../com.groupdocs.viewer/viewer) oluştururken bağlantı zaman aşımını ayarlar. |
| [getUrlReadTimeout()](#getUrlReadTimeout--) | java.net.URL kullanarak bir belge yüklemek için bir [Viewer](../../com.groupdocs.viewer/viewer) oluştururken okuma zaman aşımını alır. |
| [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | java.net.URL kullanarak bir belge yüklemek için bir [Viewer](../../com.groupdocs.viewer/viewer) oluştururken okuma zaman aşımını ayarlar. |
| [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | Arşivlerin çıkarma sürecini kontrol etmek için güvenlik seçeneklerini alır. |
| [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | Arşivlerin çıkarma sürecini kontrol etmek için güvenlik seçeneklerini ayarlar. |
| [isSkipExternalResources()](#isSkipExternalResources--) | Doğru olarak ayarlandığında, görüntüler gibi tüm dış kaynaklar \#getWhitelistedResources().getWhitelistedResources() dışındaki durumlarda yüklenmez. |
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | Doğru olarak ayarlandığında, görüntüler gibi tüm dış kaynaklar \#getWhitelistedResources().getWhitelistedResources() dışındaki durumlarda yüklenmez. |
| [getWhitelistedResources()](#getWhitelistedResources--) | `true` olarak ayarlandığında \#isSkipExternalResources().isSkipExternalResources() tarafından yüklenmesi gereken dış kaynaklara karşılık gelen URL parçacıklarının listesi. |
| [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | `true` olarak ayarlandığında \#isSkipExternalResources().isSkipExternalResources() tarafından yüklenmesi gereken dış kaynaklara karşılık gelen URL parçacıklarının listesini ayarlar. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


LoadOptions sınıfının yeni bir örneğini başlatır.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


LoadOptions sınıfının yeni bir örneğini başlatır.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | Açılacak dosyanın türü. |

### DEFAULT_URL_CONNECT_TIMEOUT {#DEFAULT-URL-CONNECT-TIMEOUT}
```
public static final int DEFAULT_URL_CONNECT_TIMEOUT
```


### DEFAULT_URL_READ_TIMEOUT {#DEFAULT-URL-READ-TIMEOUT}
```
public static final int DEFAULT_URL_READ_TIMEOUT
```


### _tryRepair {#-tryRepair}
```
public boolean _tryRepair
```


### isTryRepair() {#isTryRepair--}
```
public boolean isTryRepair()
```


Etkinleştirildiğinde, GroupDocs.Viewer PDF belgelerindeki yapısal bozulmaları onarmaya çalışır. Varsayılan değer false'tur.

Bu özellik bir PDF belgesindeki aşağıdaki sorunları ele alır:

 *  Broken references within the document (incorrect object offsets in the Cross-reference list).
 *  Missing critical elements like root object, page object, or page content.
 *  Circular references (Form X-object referencing itself).

**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


Etkinleştirildiğinde, GroupDocs.Viewer PDF belgelerindeki yapısal bozulmaları onarmaya çalışır. Varsayılan değer false'tur.

Bu özellik bir PDF belgesindeki aşağıdaki sorunları ele alır:

 *  Broken references within the document (incorrect object offsets in the Cross-reference list).
 *  Missing critical elements like root object, page object, or page content.
 *  Circular references (Form X-object referencing itself).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Açılacak dosyanın türünü alır.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.
### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


Açılacak dosyanın türünü ayarlar.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.viewer/filetype) | Dosya türü. |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Şifreli bir dosyayı açmak için şifreyi alır.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/java/load-password-protected-document/

**Returns:**
java.lang.String - dosyayı açmak için şifre.
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Şifreli bir dosyayı açmak için şifreyi ayarlar.

Kod örneği için, [belgeleme][].


[documentation]: https://docs.groupdocs.com/viewer/java/load-password-protected-document/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String | Dosyayı açmak için şifre. |

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


Metin tabanlı dosyalar veya [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) ve [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG) gibi e-posta mesajları açılırken kullanılan karakter kümesi.

Varsayılan değer java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8'tir. Kod örneği için [documentation][] belgesine bakın.

**Learn more**

 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render email messages as HTML, PDF, PNG, and JPEG files][Render email messages as HTML_ PDF_ PNG_ and JPEG files]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setCharset(StandardCharsets.US_ASCII); // Set the charset

 try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files
[Render email messages as HTML_ PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Returns:**
java.nio.charset.Charset
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


Metin tabanlı dosyalar veya [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV), [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT) ve [FileType.MSG](../../com.groupdocs.viewer/filetype\#MSG) gibi e-posta mesajları açılırken kullanılan karakter kümesi.

Varsayılan değer java.nio.charset.StandardCharsets\#UTF\_8.UTF\_8'tir. Kod örneği için [documentation][] belgesine bakın.

**Learn more**

 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]
 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render email messages as HTML, PDF, PNG, and JPEG files][Render email messages as HTML_ PDF_ PNG_ and JPEG files]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setCharset(StandardCharsets.US_ASCII); // Set the charset

 try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files
[Render email messages as HTML_ PDF_ PNG_ and JPEG files]: https://docs.groupdocs.com/viewer/java/render-email-messages/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


Bu seçenek [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) ve [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) dosyalarının karakter seti algılamasını etkinleştirir. Karakter seti algılanamazsa varsayılan [getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--) kullanılır.

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

Kodlama algılanamazsa varsayılan  kullanılır. Kod örneği için [documentation][] belgesine bakın.

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setDetectCharset(true); // Enable encoding detection

 try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/

**Returns:**
boolean
### setDetectCharset(boolean detectCharset) {#setDetectCharset-boolean-}
```
public void setDetectCharset(boolean detectCharset)
```


Bu seçenek [FileType.TXT](../../com.groupdocs.viewer/filetype\#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype\#TSV) ve [FileType.CSV](../../com.groupdocs.viewer/filetype\#CSV) dosyalarının karakter seti algılamasını etkinleştirir. Karakter seti algılanamazsa varsayılan [getCharset()](../../com.groupdocs.viewer.options/loadoptions\#getCharset--) kullanılır.

**Learn more about rendering text and tab/comma delimited files**

 *  [Render text documents as HTML, PDF, and image files][Render text documents as HTML_ PDF_ and image files]
 *  [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files][Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]

Kodlama algılanamazsa varsayılan  kullanılır. Kod örneği için [documentation][] belgesine bakın.

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setDetectCharset(true); // Enable encoding detection

 try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Render text documents as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-text-files/
[Render Excel and Apple Numbers spreadsheets as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


Harici kaynakların yüklenmesi için zaman aşımını alır.

**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

Varsayılan değer 30 saniyedir. Kod örneği için [documentation][] belgesine bakın.

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setResourceLoadingTimeout(5000); // Set resource loading timeout to 5 seconds

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/
[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents

**Returns:**
int
### setResourceLoadingTimeout(int resourceLoadingTimeout) {#setResourceLoadingTimeout-int-}
```
public void setResourceLoadingTimeout(int resourceLoadingTimeout)
```


Grafikler gibi harici kaynakların yüklenmesi için zaman aşımını ayarlar.

***Note:** The default value is 30 seconds.*

Bu seçenek dış kaynaklar içeren Word İşleme belgeleri için desteklenir. Varsayılan değer 30 saniyedir. Kod örneği için [documentation][] belgesine bakın.


[documentation]: https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| resourceLoadingTimeout | int | Yükleme zaman aşımı, milisaniye. |

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


java.net.URL kullanarak bir belge yüklemek için bir [Viewer](../../com.groupdocs.viewer/viewer) oluştururken bağlantı zaman aşımını alır.

***Note:** The default value is 5 seconds.*

**Returns:**
int - bağlantı zaman aşımı.
### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


java.net.URL kullanarak bir belge yüklemek için bir [Viewer](../../com.groupdocs.viewer/viewer) oluştururken bağlantı zaman aşımını ayarlar.

***Note:** The default value is 5 seconds.*

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| urlConnectTimeout | int | Bağlantı zaman aşımı. |

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


java.net.URL kullanarak bir belge yüklemek için bir [Viewer](../../com.groupdocs.viewer/viewer) oluştururken okuma zaman aşımını alır.

***Note:** The default value is 30 seconds.*

**Returns:**
int - okuma zaman aşımı.
### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


java.net.URL kullanarak bir belge yüklemek için bir [Viewer](../../com.groupdocs.viewer/viewer) oluştururken okuma zaman aşımını ayarlar.

***Note:** The default value is 30 seconds.*

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| urlReadTimeout | int | Okuma zaman aşımı. |

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


Arşivlerin çıkarma sürecini kontrol etmek için güvenlik seçeneklerini alır.

***Note:** Not each archive type supports all options.*

**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - arşivlerin çıkarma sürecini yapılandırmak için seçenek nesnesi.
### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


Arşivlerin çıkarma sürecini kontrol etmek için güvenlik seçeneklerini ayarlar.

***Note:** Not each archive type supports all options.*

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | Arşivlerin çıkarma sürecini yapılandırmak için seçenek nesnesi. |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Doğru olarak ayarlandığında, görüntüler gibi tüm dış kaynaklar \#getWhitelistedResources().getWhitelistedResources() dışındaki durumlarda yüklenmez.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```


Doğru olarak ayarlandığında, görüntüler gibi tüm dış kaynaklar \#getWhitelistedResources().getWhitelistedResources() dışındaki durumlarda yüklenmez.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources

 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| skipExternalResources | boolean | Harici kaynakların yüklenmesini etkinleştirmek veya devre dışı bırakmak için bayrak. |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


`true` olarak ayarlandığında \#isSkipExternalResources().isSkipExternalResources() tarafından yüklenmesi gereken dış kaynaklara karşılık gelen URL parçacıklarının listesi.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources
 loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // Enable loading of external resources that have 'avatars.githubusercontent.com' fragment in resource URL.
 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whitelistedResources) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whitelistedResources)
```


`true` olarak ayarlandığında \#isSkipExternalResources().isSkipExternalResources() tarafından yüklenmesi gereken dış kaynaklara karşılık gelen URL parçacıklarının listesini ayarlar.

**This option applies to the following file formats:**

 *  [Presentation file formats][]
 *  [Spreadsheet file formats][]
 *  [Web file formats][]
 *  [Word processing file formats][]

**Learn more about options to manage external resources:**

 *  [Set timeout for loading external resources][]

**Example:**

```
LoadOptions loadOptions = new LoadOptions();
 loadOptions.setSkipExternalResources(true); // Skip loading of external resources
 loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // Enable loading of external resources that have 'avatars.githubusercontent.com' fragment in resource URL.
 try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
     HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

     viewer.view(viewOptions);
 }
```


[Presentation file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats
[Spreadsheet file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats
[Web file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats
[Word processing file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats
[Set timeout for loading external resources]: https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| whitelistedResources | java.util.List<java.lang.String> | Yüklenmesi gereken harici kaynaklara karşılık gelen URL parçacıklarının listesi. |

