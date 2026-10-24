---
title: "LoadOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يوفر خيارات تُستخدم لفتح ملف."
type: docs
weight: 18
url: /ar/java/com.groupdocs.viewer.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

يوفر خيارات تُستخدم لفتح ملف.


تُجَمِّع فئة LoadOptions إعدادات ومعلمات مختلفة يمكن استخدامها
لتحديد كيفية فتح الملف وتحميله في مكوّن GroupDocs.Viewer.
للتفاصيل، راجع هذه [الصفحة](../https://docs.groupdocs.com/viewer/java/loading/) وأقسامها الفرعية.


مثال على الاستخدام:

````

 LoadOptions options = new LoadOptions();
 options.setPassword("myPassword");
 options.setFileType(PDF);
 options.setCharset(Charset.forName("UTF-8"));

 try (Viewer viewer = new Viewer(pdfFileInputStream, options)) {
     // Use the viewer object for further operations
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | ينشئ مثلاً جديداً من |
LoadOptions
الفئة.
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.viewer.FileType-) | ينشئ مثلاً جديداً من |
LoadOptions
الفئة.
|
## الحقول

| حقل | الوصف |
| --- | --- |
| [DEFAULT_URL_CONNECT_TIMEOUT](#DEFAULT-URL-CONNECT-TIMEOUT) |  |
| [DEFAULT_URL_READ_TIMEOUT](#DEFAULT-URL-READ-TIMEOUT) |  |
| [_tryRepair](#-tryRepair) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isTryRepair()](#isTryRepair--) | عند التفعيل، يحاول GroupDocs.Viewer إصلاح الفساد الهيكلي في مستندات PDF. |
|
|  | [setTryRepair(boolean tryRepair)](#setTryRepair-boolean-) | عند التفعيل، يحاول GroupDocs.Viewer إصلاح الفساد الهيكلي في مستندات PDF. |
|
|  | [getFileType()](#getFileType--) | يحصل على نوع الملف المراد فتحه. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.viewer.FileType-) | يضبط نوع الملف المراد فتحه. |
|
|  | [getPassword()](#getPassword--) | يحصل على كلمة المرور لفتح ملف مشفر. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يضبط كلمة المرور لفتح ملف مشفر. |
|
|  | [getCharset()](#getCharset--) | مجموعة الأحرف المستخدمة عند فتح ملفات نصية أو رسائل بريد إلكتروني مثل |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
و[FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [setCharset(Charset value)](#setCharset-java.nio.charset.Charset-) | مجموعة الأحرف المستخدمة عند فتح ملفات نصية أو رسائل بريد إلكتروني مثل |
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
و[FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
|
|  | [isDetectCharset()](#isDetectCharset--) | يُتيح هذا الخيار اكتشاف مجموعة الأحرف لملفات [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT)، [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV)، و[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV). |
|
|  | [setDetectCharset(boolean detectCharset)](#setDetectCharset-boolean-) | يُتيح هذا الخيار اكتشاف مجموعة الأحرف لملفات [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT)، [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV)، و[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV). |
|
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | يحصل على مهلة تحميل الموارد الخارجية. |
|
|  | [setResourceLoadingTimeout(int resourceLoadingTimeout)](#setResourceLoadingTimeout-int-) | يضبط مهلة تحميل الموارد الخارجية، مثل الرسومات. |
|
|  | [getUrlConnectTimeout()](#getUrlConnectTimeout--) | يحصل على مهلة الاتصال لإنشاء [Viewer](../../com.groupdocs.viewer/viewer) باستخدام java.net.URL لتحميل مستند. |
|
|  | [setUrlConnectTimeout(int urlConnectTimeout)](#setUrlConnectTimeout-int-) | يضبط مهلة الاتصال لإنشاء [Viewer](../../com.groupdocs.viewer/viewer) باستخدام java.net.URL لتحميل مستند. |
|
|  | [getUrlReadTimeout()](#getUrlReadTimeout--) | يحصل على مهلة القراءة لإنشاء [Viewer](../../com.groupdocs.viewer/viewer) باستخدام java.net.URL لتحميل مستند. |
|
|  | [setUrlReadTimeout(int urlReadTimeout)](#setUrlReadTimeout-int-) | يضبط مهلة القراءة لإنشاء [Viewer](../../com.groupdocs.viewer/viewer) باستخدام java.net.URL لتحميل مستند. |
|
|  | [getArchiveSecurityOptions()](#getArchiveSecurityOptions--) | يحصل على خيارات الأمان للتحكم في عملية استخراج الأرشيفات. |
|
|  | [setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)](#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-) | يضبط خيارات الأمان للتحكم في عملية استخراج الأرشيفات. |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | عند تعيينه إلى `true`، لن يتم تحميل جميع الموارد الخارجية مثل الصور باستثناء #getWhitelistedResources().getWhitelistedResources(). |
|
|  | [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) | عند تعيينه إلى `true`، لن يتم تحميل جميع الموارد الخارجية مثل الصور باستثناء #getWhitelistedResources().getWhitelistedResources(). |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | قائمة أجزاء URL المقابلة للموارد الخارجية التي يجب تحميلها عندما يتم تعيين #isSkipExternalResources().isSkipExternalResources() إلى `true`. |
|
|  | [setWhitelistedResources(List<String> whitelistedResources)](#setWhitelistedResources-java.util.List-java.lang.String--) | يحدد قائمة أجزاء URL المقابلة للموارد الخارجية التي يجب تحميلها عندما يتم تعيين #isSkipExternalResources().isSkipExternalResources() إلى `true`. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


ينشئ مثلاً جديداً من
LoadOptions
الفئة.


للحصول على مثال شفري، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.viewer.FileType-}
```
public LoadOptions(FileType fileType)
```


ينشئ مثلاً جديداً من
LoadOptions
الفئة.


للحصول على مثال شفري، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | نوع الملف المراد فتحه. |
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


عند التفعيل، يحاول GroupDocs.Viewer إصلاح الفساد الهيكلي في مستندات PDF. القيمة الافتراضية هي false.


تتعامل هذه الميزة مع المشكلات التالية في مستند PDF:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Returns:**
boolean
### setTryRepair(boolean tryRepair) {#setTryRepair-boolean-}
```
public void setTryRepair(boolean tryRepair)
```


عند التفعيل، يحاول GroupDocs.Viewer إصلاح الفساد الهيكلي في مستندات PDF. القيمة الافتراضية هي false.


تتعامل هذه الميزة مع المشكلات التالية في مستند PDF:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tryRepair | boolean |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


يحصل على نوع الملف المراد فتحه.


للحصول على مثال شفري، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.

### setFileType(FileType value) {#setFileType-com.groupdocs.viewer.FileType-}
```
public final void setFileType(FileType value)
```


يضبط نوع الملف المراد فتحه.


للحصول على مثال شفري، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-file-type-when-loading-a-document/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [FileType](../../com.groupdocs.viewer/filetype) | نوع الملف. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


يحصل على كلمة المرور لفتح ملف مشفر.


للحصول على مثال شفري، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/).


**Returns:**
java.lang.String - كلمة المرور لفتح الملف.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يضبط كلمة المرور لفتح ملف مشفر.


للحصول على مثال شفري، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/load-password-protected-document/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | كلمة المرور لفتح الملف. |
|

### getCharset() {#getCharset--}
```
public final Charset getCharset()
```


مجموعة الأحرف المستخدمة عند فتح ملفات نصية أو رسائل بريد إلكتروني مثل
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
و[FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
القيمة الافتراضية هي java.nio.charset.StandardCharsets#UTF_8.UTF_8. للحصول على مثال شفري، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/).

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // تعيين مجموعة الأحرف

try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
java.nio.charset.Charset
### setCharset(Charset value) {#setCharset-java.nio.charset.Charset-}
```
public final void setCharset(Charset value)
```


مجموعة الأحرف المستخدمة عند فتح ملفات نصية أو رسائل بريد إلكتروني مثل
[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV),
[FileType.TXT](../../com.groupdocs.viewer/filetype#TXT),
و[FileType.MSG](../../com.groupdocs.viewer/filetype#MSG).
القيمة الافتراضية هي java.nio.charset.StandardCharsets#UTF_8.UTF_8. للحصول على مثال شفري، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-encoding-when-loading-documents/).

**Learn more**

* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files)
* [Render email messages as HTML, PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-email-messages/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setCharset(StandardCharsets.US_ASCII); // تعيين مجموعة الأحرف

try (Viewer viewer = new Viewer("message.txt", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.nio.charset.Charset |  |

### isDetectCharset() {#isDetectCharset--}
```
public boolean isDetectCharset()
```


يُتيح هذا الخيار اكتشاف مجموعة الأحرف لملفات [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT)، [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV)، و[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV). في حال عدم إمكانية اكتشاف مجموعة الأحرف، يتم استخدام [getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--) الافتراضية.

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


إذا تعذر اكتشاف الترميز، يتم استخدام الافتراضي. للحصول على مثال شفري، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // تمكين اكتشاف الترميز

try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setDetectCharset(boolean detectCharset) {#setDetectCharset-boolean-}
```
public void setDetectCharset(boolean detectCharset)
```


يُتيح هذا الخيار اكتشاف مجموعة الأحرف لملفات [FileType.TXT](../../com.groupdocs.viewer/filetype#TXT)، [FileType.TSV](../../com.groupdocs.viewer/filetype#TSV)، و[FileType.CSV](../../com.groupdocs.viewer/filetype#CSV). في حال عدم إمكانية اكتشاف مجموعة الأحرف، يتم استخدام [getCharset()](../../com.groupdocs.viewer.options/loadoptions#getCharset--) الافتراضية.

**Learn more about rendering text and tab/comma delimited files**

* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)


إذا تعذر اكتشاف الترميز، يتم استخدام الافتراضي. للحصول على مثال شفري، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents/).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setDetectCharset(true); // تمكين اكتشاف الترميز

try (Viewer viewer = new Viewer("employees.csv", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| detectCharset | boolean |  |

### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public int getResourceLoadingTimeout()
```


يحصل على مهلة تحميل الموارد الخارجية.


**Note:** The default value is 10 seconds.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)


القيمة الافتراضية هي 30 ثانية. للحصول على مثال شفري، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents).

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setResourceLoadingTimeout(5000); // تعيين مهلة تحميل الموارد إلى 5 ثوانٍ

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
int
### setResourceLoadingTimeout(int resourceLoadingTimeout) {#setResourceLoadingTimeout-int-}
```
public void setResourceLoadingTimeout(int resourceLoadingTimeout)
```


يضبط مهلة تحميل الموارد الخارجية، مثل الرسومات.


***Note:** The default value is 30 seconds.*


يتم دعم هذا الخيار لمستندات معالجة النصوص التي تحتوي على موارد خارجية.
القيمة الافتراضية هي 30 ثانية. للحصول على مثال شفري، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/detect-encoding-when-loading-documents).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | resourceLoadingTimeout | int | مهلة التحميل، بالمللي ثانية. |
|

### getUrlConnectTimeout() {#getUrlConnectTimeout--}
```
public int getUrlConnectTimeout()
```


يحصل على مهلة الاتصال لإنشاء [Viewer](../../com.groupdocs.viewer/viewer) باستخدام java.net.URL لتحميل مستند.


***Note:** The default value is 5 seconds.*


**Returns:**
int - مهلة الاتصال.

### setUrlConnectTimeout(int urlConnectTimeout) {#setUrlConnectTimeout-int-}
```
public void setUrlConnectTimeout(int urlConnectTimeout)
```


يضبط مهلة الاتصال لإنشاء [Viewer](../../com.groupdocs.viewer/viewer) باستخدام java.net.URL لتحميل مستند.


***Note:** The default value is 5 seconds.*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | urlConnectTimeout | int | مهلة الاتصال. |
|

### getUrlReadTimeout() {#getUrlReadTimeout--}
```
public int getUrlReadTimeout()
```


يحصل على مهلة القراءة لإنشاء [Viewer](../../com.groupdocs.viewer/viewer) باستخدام java.net.URL لتحميل مستند.


***Note:** The default value is 30 seconds.*


**Returns:**
int - مهلة القراءة.

### setUrlReadTimeout(int urlReadTimeout) {#setUrlReadTimeout-int-}
```
public void setUrlReadTimeout(int urlReadTimeout)
```


يضبط مهلة القراءة لإنشاء [Viewer](../../com.groupdocs.viewer/viewer) باستخدام java.net.URL لتحميل مستند.


***Note:** The default value is 30 seconds.*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | urlReadTimeout | int | مهلة القراءة. |
|

### getArchiveSecurityOptions() {#getArchiveSecurityOptions--}
```
public ArchiveSecurityOptions getArchiveSecurityOptions()
```


يحصل على خيارات الأمان للتحكم في عملية استخراج الأرشيفات.


***Note:** Not each archive type supports all options.*


**Returns:**
com.groupdocs.viewer.options.ArchiveSecurityOptions - كائن الخيارات لتكوين عملية استخراج الأرشيفات.

### setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions) {#setArchiveSecurityOptions-com.groupdocs.viewer.options.ArchiveSecurityOptions-}
```
public void setArchiveSecurityOptions(ArchiveSecurityOptions archiveSecurityOptions)
```


يضبط خيارات الأمان للتحكم في عملية استخراج الأرشيفات.


***Note:** Not each archive type supports all options.*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | archiveSecurityOptions | com.groupdocs.viewer.options.ArchiveSecurityOptions | كائن الخيارات لتكوين عملية استخراج الأرشيفات. |
|

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


عند تعيينه إلى `true`، لن يتم تحميل جميع الموارد الخارجية مثل الصور باستثناء #getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // تخطي تحميل الموارد الخارجية

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```


عند تعيينه إلى `true`، لن يتم تحميل جميع الموارد الخارجية مثل الصور باستثناء #getWhitelistedResources().getWhitelistedResources().

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // تخطي تحميل الموارد الخارجية

try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | skipExternalResources | boolean | العلم لتفعيل أو تعطيل تحميل الموارد الخارجية. |
|

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


قائمة أجزاء URL المقابلة للموارد الخارجية التي يجب تحميلها عندما يتم تعيين #isSkipExternalResources().isSkipExternalResources() إلى `true`.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // تخطي تحميل الموارد الخارجية
loadOptions.getWhitelistedResources().add("avatars.githubusercontent.com"); // تمكين تحميل الموارد الخارجية التي تحتوي على الجزء 'avatars.githubusercontent.com' في عنوان URL للمورد.
try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whitelistedResources) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whitelistedResources)
```


يحدد قائمة أجزاء URL المقابلة للموارد الخارجية التي يجب تحميلها عندما يتم تعيين #isSkipExternalResources().isSkipExternalResources() إلى `true`.

**This option applies to the following file formats:**

* [Presentation file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#presentation-file-formats)
* [Spreadsheet file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#spreadsheet-file-formats)
* [Web file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#web-file-formats)
* [Word processing file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#word-processing-file-formats)

**Learn more about options to manage external resources:**

* [Set timeout for loading external resources](../https://docs.groupdocs.com/viewer/java/set-timeout-for-loading-external-resources-contained-by-a-document/)

**Example:**


LoadOptions loadOptions = new LoadOptions();
loadOptions.setSkipExternalResources(true); // تخطي تحميل الموارد الخارجية
loadOptions.setWhitelistedResources(Arrays.asList("avatars.githubusercontent.com")); // تمكين تحميل الموارد الخارجية التي تحتوي على الجزء 'avatars.githubusercontent.com' في عنوان URL للمورد.
try (Viewer viewer = new Viewer("business-flyer.docx", loadOptions)) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();

viewer.view(viewOptions);
}
     


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | whitelistedResources | java.util.List<java.lang.String> | قائمة أجزاء URL التي تتطابق مع الموارد الخارجية التي يجب تحميلها. |
|

