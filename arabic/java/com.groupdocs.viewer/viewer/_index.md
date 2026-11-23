---
title: "Viewer"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يمثل الفئة الرئيسية التي تتحكم في عملية عرض المستند."
type: docs
weight: 12
url: /ar/java/com.groupdocs.viewer/viewer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Viewer implements Closeable
```

يمثل الفئة الرئيسية التي تتحكم في عملية عرض المستند.


فئة Viewer هي نقطة الدخول لتصيير المستندات باستخدام مكوّن GroupDocs.Viewer.
توفر طرقًا وخيارات لتحميل المستندات من مصادر مختلفة، وتخصيص عملية التصيير، واسترجاع المخرجات المصورة بصيغ مختلفة.


مثال على الاستخدام:

````

 try (Viewer viewer = new Viewer("source.pdf")) {
     viewer.view(new PngViewOptions("result-page{0}.png"));
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [Viewer(InputStream fileStream)](#Viewer-java.io.InputStream-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(InputStream fileStream, boolean leaveOpen)](#Viewer-java.io.InputStream-boolean-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(InputStream fileStream, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(URL url)](#Viewer-java.net.URL-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(URL url, LoadOptions loadOptions)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(URL url, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(FileReader fileReader, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(String filePath)](#Viewer-java.lang.String-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(Path filePath)](#Viewer-java.nio.file.Path-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(String filePath, LoadOptions loadOptions)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(Path filePath, LoadOptions loadOptions)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(String filePath, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(Path filePath, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
|  | [Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | ينشئ مثيلًا جديدًا لفئة Viewer. |
|
## الحقول

| حقل | الوصف |
| --- | --- |
| [LOAD_OPTIONS](#LOAD-OPTIONS) |  |
| [SETTINGS](#SETTINGS) |  |
| [FILE_READER](#FILE-READER) |  |
| [OPTIONS](#OPTIONS) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getViewInfo(ViewInfoOptions options)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-) | يعيد معلومات حول العرض ومعلومات محددة عن المستند. |
|
|  | [getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-com.groupdocs.viewer.utils.CancellationToken-) | يعيد معلومات حول العرض ومعلومات محددة عن المستند. |
|
|  | [getAttachments()](#getAttachments--) | يعيد المرفقات الموجودة في المستند. |
|
|  | [getAttachments(CancellationToken cancellationToken)](#getAttachments-com.groupdocs.viewer.utils.CancellationToken-) | يعيد المرفقات الموجودة في المستند. |
|
|  | [saveAttachment(Attachment attachment, OutputStream destination)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-) | يحفظ ملف المرفق إلى تدفق الوجهة. |
|
|  | [saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-com.groupdocs.viewer.utils.CancellationToken-) | يحفظ ملف المرفق إلى تدفق الوجهة. |
|
|  | [view(ViewOptions options)](#view-com.groupdocs.viewer.options.ViewOptions-) | ينشئ عرضًا لجميع صفحات المستند. |
|
|  | [view(ViewOptions options, CancellationToken cancellationToken)](#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-) | ينشئ عرضًا لجميع صفحات المستند. |
|
|  | [view(ViewOptions options, int pageNumber)](#view-com.groupdocs.viewer.options.ViewOptions-int-) | ينشئ عرضًا لصفحة مستند محددة. |
|
|  | [view(ViewOptions options, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-int...-) | ينشئ عرضًا لصفحات مستند محددة. |
|
|  | [view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-int...-) | ينشئ عرضًا لصفحات مستند محددة. |
|
|  | [getAllFonts()](#getAllFonts--) | يعيد جميع الخطوط المستخدمة في المستندات المحملة، بما في ذلك تلك المدمجة داخل المستند نفسه وتلك الخطوط النظامية المثبتة في نظام التشغيل والمستخدمة في المستند. |
|
|  | [search(SearchHighlightOptions options)](#search-com.groupdocs.viewer.options.SearchHighlightOptions-) | ينفذ بحثًا نصيًا ويبرز التطابقات (إن وجدت) في المستند المحمل وفقًا للخيارات المقدمة. |
|
|  | [getFileInfo()](#getFileInfo--) | يعيد معلومات حول الملف، مثل نوع الملف وعلامة تشير إلى ما إذا كان الملف مشفرًا. |
|
|  | [close()](#close--) | يطلق تدفق الملف والموارد الداخلية المدارة. |
|
### Viewer(InputStream fileStream) {#Viewer-java.io.InputStream-}
```
public Viewer(InputStream fileStream)
```


ينشئ مثيلًا جديدًا لفئة Viewer.


مزيد من المعلومات حول أنواع الملفات التي يدعمها GroupDocs.Viewer:
[Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | الطريقة التي تعيد تدفقًا قابلًا للقراءة. |
|

### Viewer(InputStream fileStream, boolean leaveOpen) {#Viewer-java.io.InputStream-boolean-}
```
public Viewer(InputStream fileStream, boolean leaveOpen)
```


ينشئ مثيلًا جديدًا لفئة Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | دفق الملف. |
|
|  | leaveOpen | boolean | true لترك التدفق مفتوحًا بعد التخلص من كائن Viewer؛ وإلا false. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions)
```


ينشئ مثيلًا جديدًا لفئة Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | التدفق القابل للقراءة. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | خيارات تحميل المستند. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)
```


ينشئ مثيلًا جديدًا لفئة Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | دفق الملف. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | خيارات تحميل المستند. |
|
|  | leaveOpen | boolean | true لترك التدفق مفتوحًا بعد التخلص من كائن Viewer؛ وإلا false. |
|

### Viewer(InputStream fileStream, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, ViewerSettings settings)
```


ينشئ مثيلًا جديدًا لفئة Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | دفق الملف. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | إعدادات Viewer. |
|

### Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)
```


ينشئ مثيلًا جديدًا لفئة Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | دفق الملف. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | إعدادات Viewer. |
|
|  | leaveOpen | boolean | true لترك التدفق مفتوحًا بعد التخلص من كائن Viewer؛ وإلا false. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)
```


ينشئ مثيلًا جديدًا لفئة Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | دفق الملف. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | خيارات تحميل المستند. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | إعدادات Viewer. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)
```


ينشئ مثيلًا جديدًا لفئة Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | دفق الملف. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | خيارات تحميل المستند. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | إعدادات Viewer. |
|
|  | leaveOpen | boolean | true لترك التدفق مفتوحًا بعد التخلص من كائن Viewer؛ وإلا false. |
|

### Viewer(URL url) {#Viewer-java.net.URL-}
```
public Viewer(URL url)
```


ينشئ مثيلًا جديدًا لفئة Viewer.


مزيد من المعلومات حول أنواع الملفات التي يدعمها GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | url | java.net.URL | عنوان URL إلى ملف يجب تحميله في Viewer. |
|

### Viewer(URL url, LoadOptions loadOptions) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(URL url, LoadOptions loadOptions)
```


ينشئ مثيلًا جديدًا لفئة Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | url | java.net.URL | عنوان URL إلى ملف يجب تحميله في Viewer. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | خيارات تحميل المستند. |
|

### Viewer(URL url, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, ViewerSettings settings)
```


ينشئ مثيلًا جديدًا لفئة Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | url | java.net.URL | عنوان URL إلى ملف يجب تحميله في Viewer. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | إعدادات Viewer. |
|

### Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)
```


ينشئ مثيلًا جديدًا لفئة Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | url | java.net.URL | عنوان URL إلى ملف يجب تحميله في Viewer. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | خيارات تحميل المستند. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | إعدادات Viewer. |
|

### Viewer(FileReader fileReader, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, ViewerSettings settings)
```


ينشئ مثيلًا جديدًا لفئة Viewer.


يسمح لك هذا المُنشئ بإنشاء كائن Viewer لعرض مستند من [FileReader](../../com.groupdocs.viewer.interfaces/filereader) باستخدام [ViewerSettings](../../com.groupdocs.viewer/viewersettings) المحددة.
***Learn more**
* To learn about the file types supported by GroupDocs.Viewer, visit: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* To explore the features of GroupDocs.Viewer for Java, refer to: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | الـ [FileReader](../../com.groupdocs.viewer.interfaces/filereader) الذي يحتوي على المستند الذي سيتم تحميله في Viewer. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | الـ [ViewerSettings](../../com.groupdocs.viewer/viewersettings) التي سيتم تطبيقها على Viewer. |
|

### Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)
```


ينشئ مثيلًا جديدًا لفئة Viewer.


يوفر وظائف لتحميل وعرض المستندات باستخدام GroupDocs.Viewer.


**Note:** Ensure that the file reader, load options, and settings are properly configured for accurate document processing.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | قارئ الملف. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | خيارات التحميل. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | إعدادات Viewer. |
|

### Viewer(String filePath) {#Viewer-java.lang.String-}
```
public Viewer(String filePath)
```


ينشئ مثيلًا جديدًا لفئة Viewer.
***Learn more:**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار إلى الملف المراد عرضه. |
|

### Viewer(Path filePath) {#Viewer-java.nio.file.Path-}
```
public Viewer(Path filePath)
```


ينشئ مثيلًا جديدًا لفئة Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | المسار إلى الملف المراد عرضه. |
|

### Viewer(String filePath, LoadOptions loadOptions) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(String filePath, LoadOptions loadOptions)
```


ينشئ مثيلًا جديدًا لفئة Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار إلى الملف المراد عرضه. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | خيارات تحميل المستند. |
|

### Viewer(Path filePath, LoadOptions loadOptions) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(Path filePath, LoadOptions loadOptions)
```


ينشئ مثيلًا جديدًا لفئة Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view a document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | المسار إلى الملف المراد عرضه. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | خيارات تحميل المستند. |
|

### Viewer(String filePath, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, ViewerSettings settings)
```


ينشئ مثيلًا جديدًا لفئة Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار إلى الملف المراد عرضه. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | إعدادات Viewer. |
|

### Viewer(Path filePath, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, ViewerSettings settings)
```


ينشئ مثيلًا جديدًا لفئة Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | المسار إلى الملف المراد عرضه. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | إعدادات Viewer. |
|

### Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)
```


ينشئ مثيلًا جديدًا لفئة Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | المسار إلى الملف المراد عرضه. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | خيارات تحميل المستند. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | إعدادات Viewer. |
|

### Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)
```


ينشئ مثيلًا جديدًا لفئة Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | المسار إلى الملف المراد عرضه. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | خيارات تحميل المستند. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | إعدادات Viewer. |
|

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


يعيد معلومات حول العرض ومعلومات محددة عن المستند.
***Learn more:**
* Learn more about the document - file type, page count, and other format specific properties: [How to get file information using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+file+information)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | خيارات معلومات العرض. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.

### getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken) {#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-com.groupdocs.viewer.utils.CancellationToken-}
```
public final ViewInfo getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```


يعيد معلومات حول العرض ومعلومات محددة عن المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | خيارات معلومات العرض. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | رمز إلغاء لإلغاء العملية. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.

### getAttachments() {#getAttachments--}
```
public final List<Attachment> getAttachments()
```


يعيد المرفقات الموجودة في المستند.
***Learn more:**
* Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+attachments)
* Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Save+attachments)*


**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - المرفقات الموجودة في المستند.

### getAttachments(CancellationToken cancellationToken) {#getAttachments-com.groupdocs.viewer.utils.CancellationToken-}
```
public final List<Attachment> getAttachments(CancellationToken cancellationToken)
```


يعيد المرفقات الموجودة في المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | رمز إلغاء لإلغاء العملية. |
|

**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - المرفقات الموجودة في المستند.

### saveAttachment(Attachment attachment, OutputStream destination) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-}
```
public void saveAttachment(Attachment attachment, OutputStream destination)
```


يحفظ ملف المرفق إلى تدفق الوجهة.
***Learn more:**
* Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+attachments)
* Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Save+attachments)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | المرفق. |
|
|  | الوجهة | java.io.OutputStream | دفق قابل للكتابة. |
|

### saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-com.groupdocs.viewer.utils.CancellationToken-}
```
public void saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken)
```


يحفظ ملف المرفق إلى تدفق الوجهة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | المرفق. |
|
|  | الوجهة | java.io.OutputStream | دفق قابل للكتابة. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | رمز إلغاء لإلغاء العملية. |
|

### view(ViewOptions options) {#view-com.groupdocs.viewer.options.ViewOptions-}
```
public final void view(ViewOptions options)
```


ينشئ عرضًا لجميع صفحات المستند.
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | خيارات العرض. |
|

### view(ViewOptions options, CancellationToken cancellationToken) {#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-}
```
public final void view(ViewOptions options, CancellationToken cancellationToken)
```


ينشئ عرضًا لجميع صفحات المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | خيارات العرض. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | رمز إلغاء لإلغاء عملية العرض. |
|

### view(ViewOptions options, int pageNumber) {#view-com.groupdocs.viewer.options.ViewOptions-int-}
```
public final void view(ViewOptions options, int pageNumber)
```


ينشئ عرضًا لصفحة مستند محددة.
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | خيارات العرض. |
|
|  | pageNumber | int | رقم الصفحة المراد عرضها. |
|

### view(ViewOptions options, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-int...-}
```
public final void view(ViewOptions options, int[] pageNumbers)
```


ينشئ عرضًا لصفحات مستند محددة.
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | خيارات العرض. |
|
|  | pageNumbers | int[] | أرقام الصفحات المراد عرضها. |
|

### view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-int...-}
```
public final void view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers)
```


ينشئ عرضًا لصفحات مستند محددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | خيارات العرض. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | رمز إلغاء لإلغاء عملية العرض. |
|
|  | pageNumbers | int[] | أرقام الصفحات المراد عرضها. |
|

### getAllFonts() {#getAllFonts--}
```
public IFontInfo[] getAllFonts()
```


يعيد جميع الخطوط المستخدمة في المستندات المحملة، بما في ذلك تلك المدمجة داخل المستند نفسه وتلك الخطوط النظامية المثبتة في نظام التشغيل والمستخدمة في المستند.

للتفاصيل، انظر إلى
[documentation](../https://docs.groupdocs.com/viewer/net/getting-used-fonts/).


**Returns:**
com.groupdocs.viewer.fonts.IFontInfo[] - قائمة غير فارغة بجميع الخطوط المستخدمة في المستند المحمَّل في هذه الحالة من [Viewer](../../com.groupdocs.viewer/viewer).

### search(SearchHighlightOptions options) {#search-com.groupdocs.viewer.options.SearchHighlightOptions-}
```
public void search(SearchHighlightOptions options)
```


ينفذ بحثًا نصيًا ويبرز التطابقات (إن وجدت) في المستند المحمل وفقًا للخيارات المقدمة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الخيارات | com.groupdocs.viewer.options.SearchHighlightOptions | خيارات البحث والتظليل، بما في ذلك عبارة نصية للبحث. لا يمكن أن تكون null. |
|

### getFileInfo() {#getFileInfo--}
```
public FileInfo getFileInfo()
```


يعيد معلومات حول الملف، مثل نوع الملف وعلامة تشير إلى ما إذا كان الملف مشفرًا.
***Learn more:**
* Learn more about how to check if a file is encrypted: [How to check if a file is encrypted](../https://docs.groupdocs.com/viewer/net/how-to-check-if-file-is-encrypted/)*


**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - the file information.

### close() {#close--}
```
public final void close()
```


يطلق تدفق الملف والموارد الداخلية المدارة.


