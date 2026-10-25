---
title: "LoadOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Bir dosya açmak için kullanılan seçenekleri sağlar."
type: docs
weight: 18
url: /tr/java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Bir dosya açmak için kullanılan seçenekleri sağlar.


LoadOptions sınıfı, kullanılabilecek çeşitli ayarları ve parametreleri kapsar
bir dosyanın GroupDocs.Viewer bileşeninde nasıl açılması ve yüklenmesi gerektiğini belirtmek için.
Ayrıntılar için, bu [sayfa](../https://docs.groupdocs.com/viewer/java/loading/) ve alt sayfalarına bakın.


Örnek kullanım:

````

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Yeni bir örnek başlatır |
LoadOptions
sınıf.
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | Yeni bir örnek başlatır |
LoadOptions
sınıf.
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [isTryRepair()](#isTryRepair--) | When enabled, GroupDocs.Viewer tries to repair structural corruption in PDF documents. |
|
|  | [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | When enabled, GroupDocs.Viewer tries to repair structural corruption in PDF documents. |
|
|  | [getFileType()](#getFileType--) | Açılacak dosyanın türünü alır. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | Açılacak dosyanın türünü ayarlar. |
|
|  | [getPassword()](#getPassword--) | Şifreli bir dosyayı açmak için şifreyi alır. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Şifreli bir dosyayı açmak için şifreyi ayarlar. |
|
|  | [getCharset()](#getCharset--) | Metin tabanlı dosyalar veya e-posta mesajları açılırken kullanılan karakter kümesi, örneğin |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
ve [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | Metin tabanlı dosyalar veya e-posta mesajları açılırken kullanılan karakter kümesi, örneğin |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
ve [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [isDetectCharset()](#isDetectCharset--) | Bu seçenek, [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) ve [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) dosyalarının karakter kümesi algılamasını etkinleştirir. |
|
|  | [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | Bu seçenek, [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV) ve [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) dosyalarının karakter kümesi algılamasını etkinleştirir. |
|
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Dış kaynakların yüklenmesi için zaman aşımını alır. |
|
|  | [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | Dış kaynakların, örneğin grafiklerin, yüklenmesi için zaman aşımını ayarlar. |
|
|  | [getUrlConnectTimeout()](#getUrlConnectTimeout--) | Bir belgeyi yüklemek için java.net.URL kullanarak bir [Viewer](../../com.groupdocs.viewer/viewer) oluştururken bağlantı zaman aşımını alır. |
|
|  | [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | Bir belgeyi yüklemek için java.net.URL kullanarak bir [Viewer](../../com.groupdocs.viewer/viewer) oluştururken bağlantı zaman aşımını ayarlar. |
|
|  | [getUrlReadTimeout()](#getUrlReadTimeout--) | Bir belgeyi yüklemek için java.net.URL kullanarak bir [Viewer](../../com.groupdocs.viewer/viewer) oluştururken okuma zaman aşımını alır. |
|
|  | [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | Bir belgeyi yüklemek için java.net.URL kullanarak bir [Viewer](../../com.groupdocs.viewer/viewer) oluştururken okuma zaman aşımını ayarlar. |
|
|  | [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | Arşivlerin çıkarma sürecini kontrol etmek için güvenlik seçeneklerini alır. |
|
|  | [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | Arşivlerin çıkarma sürecini kontrol etmek için güvenlik seçeneklerini ayarlar. |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | true olarak ayarlandığında, #getWhitelistedResources().getWhitelistedResources() dışındaki tüm dış kaynaklar, örneğin görüntüler, yüklenmez. |
|
|  | [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | true olarak ayarlandığında, #getWhitelistedResources().getWhitelistedResources() dışındaki tüm dış kaynaklar, örneğin görüntüler, yüklenmez. |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | #isSkipExternalResources().isSkipExternalResources() `true` olarak ayarlandığında yüklenmesi gereken dış kaynaklara karşılık gelen URL parçacıklarının listesi. |
|
|  | [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | #isSkipExternalResources().isSkipExternalResources() `true` olarak ayarlandığında yüklenmesi gereken dış kaynaklara karşılık gelen URL parçacıklarının listesini ayarlar. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Yeni bir örnek başlatır
LoadOptions
sınıf.


Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/) bölümüne bakın.


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


Yeni bir örnek başlatır
LoadOptions
sınıf.


Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/) bölümüne bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Açılacak dosyanın türü. |
|

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


Bu özellik, bir PDF belgesindeki aşağıdaki sorunları ele alır:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


Etkinleştirildiğinde, GroupDocs.Viewer PDF belgelerindeki yapısal bozulmaları onarmaya çalışır. Varsayılan değer false'tur.


Bu özellik, bir PDF belgesindeki aşağıdaki sorunları ele alır:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Açılacak dosyanın türünü alır.


Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/) bölümüne bakın.


**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.

### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


Açılacak dosyanın türünü ayarlar.


Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/) bölümüne bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.viewer/filetype) | Dosya türü. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Şifreli bir dosyayı açmak için şifreyi alır.


Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/) bakın.


**Returns:**
java.lang.String - dosyayı açmak için şifre.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Şifreli bir dosyayı açmak için şifreyi ayarlar.


Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | Dosyayı açmak için şifre. |
|

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


Metin tabanlı dosyalar veya e-posta mesajları açılırken kullanılan karakter kümesi, örneğin
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
ve [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
Varsayılan değer java.nio.charset.StandardCharsets#UTF_8.UTF_8. Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/) bakın.

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // Karakter kümesini ayarla

try (Viewer viewer = new Viewer(\"message.txt\", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
java.nio.charset.Charset
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


Metin tabanlı dosyalar veya e-posta mesajları açılırken kullanılan karakter kümesi, örneğin
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
ve [FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
Varsayılan değer java.nio.charset.StandardCharsets#UTF_8.UTF_8. Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/) bakın.

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // Karakter kümesini ayarla

try (Viewer viewer = new Viewer(\"message.txt\", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


Bu seçenek, [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV), ve [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) dosyalarının karakter kümesi algılamasını etkinleştirir. Karakter kümesi algılanamazsa varsayılan [getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--) kullanılır.

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


Kodlama algılanamazsa, varsayılan kullanılır. Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/) bakın.

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // Kodlama algılamayı etkinleştir

try (Viewer viewer = new Viewer(\"employees.csv\", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setDetectCharset(boolean detectCharset) {#setDetectCharset-boolean-}
```
public void setDetectCharset(boolean detectCharset)
```


Bu seçenek, [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT), [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV), ve [FileType.CSV](../../com.groupdocs.viewer/filetype#CSV) dosyalarının karakter kümesi algılamasını etkinleştirir. Karakter kümesi algılanamazsa varsayılan [getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--) kullanılır.

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


Kodlama algılanamazsa, varsayılan kullanılır. Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/) bakın.

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // Kodlama algılamayı etkinleştir

try (Viewer viewer = new Viewer(\"employees.csv\", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


Dış kaynakların yüklenmesi için zaman aşımını alır.


**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)


Varsayılan değer 30 saniyedir. Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents) bakın.

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setResourceLoadingTimeout(5000); // Kaynak yükleme zaman aşımını 5 saniyeye ayarla

try (Viewer viewer = new Viewer(\"business-flyer.docx\", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
int
### setResourceLoadingTimeout(int resourceLoadingTimeout) {#setResourceLoadingTimeout-int-}
```
public void setResourceLoadingTimeout(int resourceLoadingTimeout)
```


Dış kaynakların, örneğin grafiklerin, yüklenmesi için zaman aşımını ayarlar.


***Note:** The default value is 30 seconds.*


Bu seçenek, harici kaynaklar içeren Word İşleme belgeleri için desteklenir.
Varsayılan değer 30 saniyedir. Kod örneği için, [belgelere](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents) bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | resourceLoadingTimeout | int | Yükleme zaman aşımı, milisaniye. |
|

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


Bir belgeyi yüklemek için java.net.URL kullanarak bir [Viewer](../../com.groupdocs.viewer/viewer) oluştururken bağlantı zaman aşımını alır.


***Note:** The default value is 5 seconds.*


**Returns:**
int - bağlantı zaman aşımı.

### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


Bir belgeyi yüklemek için java.net.URL kullanarak bir [Viewer](../../com.groupdocs.viewer/viewer) oluştururken bağlantı zaman aşımını ayarlar.


***Note:** The default value is 5 seconds.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | urlConnectTimeout | int | Bağlantı zaman aşımı. |
|

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


Bir belgeyi yüklemek için java.net.URL kullanarak bir [Viewer](../../com.groupdocs.viewer/viewer) oluştururken okuma zaman aşımını alır.


***Note:** The default value is 30 seconds.*


**Returns:**
int - okuma zaman aşımı.

### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


Bir belgeyi yüklemek için java.net.URL kullanarak bir [Viewer](../../com.groupdocs.viewer/viewer) oluştururken okuma zaman aşımını ayarlar.


***Note:** The default value is 30 seconds.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | urlReadTimeout | int | Okuma zaman aşımı. |
|

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


Arşivlerin çıkarma sürecini kontrol etmek için güvenlik seçeneklerini alır.


***Note:** Not each archive type supports all options.*


**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - arşivlerin çıkarılma sürecini yapılandırmak için seçenek nesnesi.

### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


Arşivlerin çıkarma sürecini kontrol etmek için güvenlik seçeneklerini ayarlar.


***Note:** Not each archive type supports all options.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | Arşivlerin çıkarılma sürecini yapılandırmak için seçenek nesnesi. |
|

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


true olarak ayarlandığında, #getWhitelistedResources().getWhitelistedResources() dışındaki tüm dış kaynaklar, örneğin görüntüler, yüklenmez.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Dış kaynakların yüklenmesini atla

try (Viewer viewer = new Viewer(\"business-flyer.docx\", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```


true olarak ayarlandığında, #getWhitelistedResources().getWhitelistedResources() dışındaki tüm dış kaynaklar, örneğin görüntüler, yüklenmez.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Dış kaynakların yüklenmesini atla

try (Viewer viewer = new Viewer(\"business-flyer.docx\", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | skipExternalResources | boolean | Dış kaynakların yüklenmesini etkinleştirmek veya devre dışı bırakmak için bayrak. |
|

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


#isSkipExternalResources().isSkipExternalResources() `true` olarak ayarlandığında yüklenmesi gereken dış kaynaklara karşılık gelen URL parçacıklarının listesi.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Dış kaynakların yüklenmesini atla
loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // Kaynak URL'sinde 'avatars.githubusercontent.com' parçacığı bulunan dış kaynakların yüklenmesini etkinleştir.
try (Viewer viewer = new Viewer(\"business-flyer.docx\", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whitelistedResources) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whitelistedResources)
```


#isSkipExternalResources().isSkipExternalResources() `true` olarak ayarlandığında yüklenmesi gereken dış kaynaklara karşılık gelen URL parçacıklarının listesini ayarlar.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // Dış kaynakların yüklenmesini atla
loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // Kaynak URL'sinde 'avatars.githubusercontent.com' parçacığı bulunan dış kaynakların yüklenmesini etkinleştir.
try (Viewer viewer = new Viewer(\"business-flyer.docx\", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | whitelistedResources | java.util.List<java.lang.String> | Yüklenmesi gereken dış kaynaklara karşılık gelen URL parçacıklarının listesi. |
|

