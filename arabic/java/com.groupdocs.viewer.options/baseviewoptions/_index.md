---
title: "BaseViewOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يحتوي على خيارات العرض الأساسية."
type: docs
weight: 12
url: /ar/java/com.groupdocs.viewer.options/baseviewoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseViewOptions
```

يحتوي على خيارات العرض الأساسية.


ال
BaseViewOptions
الفئة تعمل كأساس لخيارات العرض في GroupDocs.Viewer.
يسمح لك بتخصيص سلوك العرض لملفات HTML و PDF و PNG و JPEG الناتجة عند العرض
صيغ المستندات المحددة.


***Note:** For internal usage.*

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [BaseViewOptions()](#BaseViewOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getTextOptions()](#getTextOptions--) | يسترجع الخيارات لتقسيم ملفات النص إلى صفحات. |
|
|  | [setTextOptions(TextOptions textOptions)](#setTextOptions-com.groupdocs.viewer.options.TextOptions-) | يضبط الخيارات لتقسيم ملفات النص إلى صفحات. |
|
|  | [isRenderComments()](#isRenderComments--) | يفعل عرض التعليقات. |
|
|  | [setRenderComments(boolean value)](#setRenderComments-boolean-) | يفعل عرض التعليقات. |
|
|  | [isRemoveComments()](#isRemoveComments--) | يعطل عرض التعليقات عندما يتم تعيينه إلى true. |
|
|  | [setRemoveComments(boolean value)](#setRemoveComments-boolean-) | يعطل عرض التعليقات عندما يتم تعيينه إلى true. |
|
|  | [isRenderNotes()](#isRenderNotes--) | يفعل عرض الملاحظات. |
|
|  | [setRenderNotes(boolean value)](#setRenderNotes-boolean-) | يفعل عرض الملاحظات. |
|
|  | [isRenderHiddenPages()](#isRenderHiddenPages--) | يفعل عرض الصفحات المخفية. |
|
|  | [setRenderHiddenPages(boolean value)](#setRenderHiddenPages-boolean-) | يفعل عرض الصفحات المخفية. |
|
|  | [getDefaultFontName()](#getDefaultFontName--) | الخط الافتراضي الذي يُستخدم عندما لا يمكن العثور على خط معين مستخدم في المستند. |
|
|  | [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | الخط الافتراضي الذي يُستخدم عندما لا يمكن العثور على خط معين مستخدم في المستند. |
|
|  | [getArchiveOptions()](#getArchiveOptions--) | يسترجع خيارات عرض ملفات الأرشيف. |
|
|  | [setArchiveOptions(ArchiveOptions value)](#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-) | يضبط خيارات عرض ملفات الأرشيف. |
|
|  | [getCadOptions()](#getCadOptions--) | يسترجع خيارات عرض رسومات CAD. |
|
|  | [setCadOptions(CadOptions value)](#setCadOptions-com.groupdocs.viewer.options.CadOptions-) | يضبط خيارات عرض رسومات CAD. |
|
| [isCadOptionsInitialized_Internal()](#isCadOptionsInitialized-Internal--) |  |
|  | [getEmailOptions()](#getEmailOptions--) | يسترجع خيارات عرض رسائل البريد الإلكتروني. |
|
|  | [setEmailOptions(EmailOptions value)](#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-) | يضبط خيارات عرض رسائل البريد الإلكتروني. |
|
|  | [getOutlookOptions()](#getOutlookOptions--) | يسترجع خيارات عرض ملفات بيانات MS Outlook. |
|
|  | [setOutlookOptions(OutlookOptions value)](#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-) | يضبط خيارات عرض ملفات بيانات MS Outlook. |
|
|  | [getPdfOptions()](#getPdfOptions--) | يسترجع خيارات عرض مستندات PDF. |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-) | يسترجع خيارات عرض مستندات PDF. |
|
|  | [getMailStorageOptions()](#getMailStorageOptions--) | يسترجع خيارات عرض ملفات بيانات تخزين Lotus Notes. |
|
|  | [setMailStorageOptions(MailStorageOptions mailStorageOptions)](#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-) | يضبط خيارات عرض ملفات بيانات تخزين Lotus Notes. |
|
|  | [getProjectManagementOptions()](#getProjectManagementOptions--) | يسترجع خيارات عرض ملفات إدارة المشاريع. |
|
|  | [setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)](#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-) | يضبط خيارات عرض ملفات إدارة المشاريع. |
|
|  | [getSpreadsheetOptions()](#getSpreadsheetOptions--) | يسترجع خيارات عرض ملفات جداول البيانات. |
|
|  | [setSpreadsheetOptions(SpreadsheetOptions value)](#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-) | يضبط خيارات عرض ملفات جداول البيانات. |
|
|  | [getWordProcessingOptions()](#getWordProcessingOptions--) | خيارات عرض ملفات معالجة Word. |
|
|  | [setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)](#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-) | خيارات عرض ملفات معالجة Word. |
|
|  | [getVisioRenderingOptions()](#getVisioRenderingOptions--) | يسترجع خيارات العرض لمعالجة ملفات Visio عند عرض المستندات. |
|
|  | [setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)](#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-) | يضبط خيارات العرض لمعالجة ملفات Visio عند عرض المستندات. |
|
|  | [getPresentationOptions()](#getPresentationOptions--) | يسترجع خيارات العرض لمعالجة مستندات العروض التقديمية. |
|
|  | [setPresentationOptions(PresentationOptions presentationOptions)](#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-) | يضبط خيارات العرض لمعالجة مستندات العروض التقديمية. |
|
|  | [getWebDocumentOptions()](#getWebDocumentOptions--) | يحصل على خيارات العرض التي تسمح بتخصيص مظهر مخرجات HTML/PDF/PNG/JPEG |
عند عرض مستندات الويب.
|
|  | [setWebDocumentOptions(WebDocumentOptions webDocumentOptions)](#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-) | يضبط خيارات العرض التي تسمح بتخصيص مظهر مخرجات HTML/PDF/PNG/JPEG |
عند عرض مستندات الويب.
|
### BaseViewOptions() {#BaseViewOptions--}
```
public BaseViewOptions()
```


### getTextOptions() {#getTextOptions--}
```
public TextOptions getTextOptions()
```


يسترجع الخيارات لتقسيم ملفات النص إلى صفحات.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-text-files/).


**Returns:**
[TextOptions](../../com.groupdocs.viewer.options/textoptions) - the text file splitting options.

### setTextOptions(TextOptions textOptions) {#setTextOptions-com.groupdocs.viewer.options.TextOptions-}
```
public void setTextOptions(TextOptions textOptions)
```


يضبط الخيارات لتقسيم ملفات النص إلى صفحات.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-text-files/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | textOptions | [TextOptions](../../com.groupdocs.viewer.options/textoptions) | خيارات تقسيم ملفات النص. |
|

### isRenderComments() {#isRenderComments--}
```
public final boolean isRenderComments()
```


يفعل عرض التعليقات.


بشكل افتراضي، لا يقوم GroupDocs.Viewer بعرض التعليقات. للقيام بذلك، اضبط هذه الخاصية إلى true.
للحصول على مثال الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments).


**Returns:**
منطقي -  true  إذا كان يجب عرض التعليقات،  false  خلاف ذلك.

### setRenderComments(boolean value) {#setRenderComments-boolean-}
```
public final void setRenderComments(boolean value)
```


يفعل عرض التعليقات.


بشكل افتراضي، لا يقوم GroupDocs.Viewer بعرض التعليقات. للقيام بذلك، اضبط هذه الخاصية إلى true.
للحصول على مثال الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-word-documents/#render-comments).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  إذا كان يجب عرض التعليقات،  false  خلاف ذلك. |
|

### isRemoveComments() {#isRemoveComments--}
```
public final boolean isRemoveComments()
```


يعطل عرض التعليقات عندما يتم ضبطه على true. بشكل افتراضي يكون false \\u2014 جميع التعليقات تُعرض.


بعض تنسيقات المستندات مثل PDF وWordProcessing قد تحتوي على تعليقات. بشكل افتراضي يقوم GroupDocs.Viewer بعرضها. عند ضبط هذا الخيار على true قد تُستبعد التعليقات من المستند الناتج.
هذا الخيار يستبدل الخاصية القديمة 'RenderComments'.


**Returns:**
منطقي -  true  إذا كان يجب عرض التعليقات،  false  خلاف ذلك.

### setRemoveComments(boolean value) {#setRemoveComments-boolean-}
```
public final void setRemoveComments(boolean value)
```


يعطل عرض التعليقات عندما يتم ضبطه على true. بشكل افتراضي يكون false \\u2014 جميع التعليقات تُعرض.


بعض تنسيقات المستندات مثل PDF وWordProcessing قد تحتوي على تعليقات. بشكل افتراضي يقوم GroupDocs.Viewer بعرضها. عند ضبط هذا الخيار على true قد تُستبعد التعليقات من المستند الناتج.
هذا الخيار يستبدل الخاصية القديمة 'RenderComments'.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  إذا كان يجب عرض التعليقات،  false  خلاف ذلك. |
|

### isRenderNotes() {#isRenderNotes--}
```
public final boolean isRenderNotes()
```


يفعل عرض الملاحظات.


بعض الملفات، مثل العروض التقديمية أو ملفات Microsoft project، قد تحتوي على ملاحظات. بشكل افتراضي، لا يقوم GroupDocs.Viewer بعرض الملاحظات. للقيام بذلك، اضبط هذه الخاصية إلى true.
للحصول على مثال الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-speaker-notes).


**Returns:**
منطقي -  true  إذا كان يجب عرض الملاحظات،  false  خلاف ذلك.

### setRenderNotes(boolean value) {#setRenderNotes-boolean-}
```
public final void setRenderNotes(boolean value)
```


يفعل عرض الملاحظات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  إذا كان يجب عرض الملاحظات،  false  خلاف ذلك. |
|

### isRenderHiddenPages() {#isRenderHiddenPages--}
```
public final boolean isRenderHiddenPages()
```


يفعل عرض الصفحات المخفية.


بعض الملفات، مثل العروض التقديمية أو جداول البيانات، قد تحتوي على صفحات مخفية. بشكل افتراضي، لا يقوم GroupDocs.Viewer بعرض هذه الصفحات. للقيام بذلك، اضبط هذه الخاصية إلى true.
للحصول على مثال الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides).


**Returns:**
منطقي -  true  إذا كان يجب عرض الصفحات المخفية،  false  خلاف ذلك.

### setRenderHiddenPages(boolean value) {#setRenderHiddenPages-boolean-}
```
public final void setRenderHiddenPages(boolean value)
```


يفعل عرض الصفحات المخفية.


بعض الملفات، مثل العروض التقديمية أو جداول البيانات، قد تحتوي على صفحات مخفية. بشكل افتراضي، لا يقوم GroupDocs.Viewer بعرض هذه الصفحات. للقيام بذلك، اضبط هذه الخاصية إلى true.
للحصول على مثال الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-presentations/#render-hidden-slides).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  إذا كان يجب عرض الصفحات المخفية،  false  خلاف ذلك. |
|

### getDefaultFontName() {#getDefaultFontName--}
```
public final String getDefaultFontName()
```


الخط الافتراضي الذي يُستخدم عندما لا يمكن العثور على خط معين مستخدم في المستند.


استخدم هذه الخاصية لتعيين الخط الافتراضي للمستند. يستخدم GroupDocs.Viewer هذا الخط أثناء العرض بدلاً من أي خطوط غير مثبتة.
لأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/replace-missing-font/).


**Returns:**
java.lang.String - اسم الخط الافتراضي.

### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public final void setDefaultFontName(String value)
```


الخط الافتراضي الذي يُستخدم عندما لا يمكن العثور على خط معين مستخدم في المستند.


استخدم هذه الخاصية لتعيين الخط الافتراضي للمستند. يستخدم GroupDocs.Viewer هذا الخط أثناء العرض بدلاً من أي خطوط غير مثبتة.
لأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/replace-missing-font/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | اسم الخط الافتراضي. |
|

### getArchiveOptions() {#getArchiveOptions--}
```
public final ArchiveOptions getArchiveOptions()
```


يسترجع خيارات عرض ملفات الأرشيف.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-archive-files/).


**Returns:**
[ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) - the archive files view options.

### setArchiveOptions(ArchiveOptions value) {#setArchiveOptions-com.groupdocs.viewer.options.ArchiveOptions-}
```
public final void setArchiveOptions(ArchiveOptions value)
```


يضبط خيارات عرض ملفات الأرشيف.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-archive-files/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [ArchiveOptions](../../com.groupdocs.viewer.options/archiveoptions) | خيارات عرض ملفات الأرشيف. |
|

### getCadOptions() {#getCadOptions--}
```
public final CadOptions getCadOptions()
```


يسترجع خيارات عرض رسومات CAD.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [عرض رسومات CAD والنماذج كملفات HTML و PDF وصور](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) و [تحديد خيارات العرض لملفات CAD](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - the CAD drawing view options.

### setCadOptions(CadOptions value) {#setCadOptions-com.groupdocs.viewer.options.CadOptions-}
```
public final void setCadOptions(CadOptions value)
```


يضبط خيارات عرض رسومات CAD.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [عرض رسومات CAD والنماذج كملفات HTML و PDF وصور](../https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) و [تحديد خيارات العرض لملفات CAD](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [CadOptions](../../com.groupdocs.viewer.options/cadoptions) | خيارات عرض رسومات CAD. |
|

### isCadOptionsInitialized_Internal() {#isCadOptionsInitialized-Internal--}
```
public boolean isCadOptionsInitialized_Internal()
```




**Returns:**
boolean
### getEmailOptions() {#getEmailOptions--}
```
public final EmailOptions getEmailOptions()
```


يسترجع خيارات عرض رسائل البريد الإلكتروني.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


**Returns:**
[EmailOptions](../../com.groupdocs.viewer.options/emailoptions) - Email messages view options.

### setEmailOptions(EmailOptions value) {#setEmailOptions-com.groupdocs.viewer.options.EmailOptions-}
```
public final void setEmailOptions(EmailOptions value)
```


يضبط خيارات عرض رسائل البريد الإلكتروني.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) | خيارات عرض رسائل البريد الإلكتروني. |
|

### getOutlookOptions() {#getOutlookOptions--}
```
public final OutlookOptions getOutlookOptions()
```


يسترجع خيارات عرض ملفات بيانات MS Outlook.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/).


**Returns:**
[OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) - MS Outlook data files view options.

### setOutlookOptions(OutlookOptions value) {#setOutlookOptions-com.groupdocs.viewer.options.OutlookOptions-}
```
public final void setOutlookOptions(OutlookOptions value)
```


يضبط خيارات عرض ملفات بيانات MS Outlook.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [OutlookOptions](../../com.groupdocs.viewer.options/outlookoptions) | خيارات عرض ملفات بيانات MS Outlook لتعيينها. |
|

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


يسترجع خيارات عرض مستندات PDF.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


**Returns:**
[PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) - the PDF documents view options.

### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.viewer.options.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


يسترجع خيارات عرض مستندات PDF.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [PdfOptions](../../com.groupdocs.viewer.options/pdfoptions) | خيارات عرض مستندات PDF. |
|

### getMailStorageOptions() {#getMailStorageOptions--}
```
public MailStorageOptions getMailStorageOptions()
```


يسترجع خيارات عرض ملفات بيانات تخزين Lotus Notes.


**Returns:**
[MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) - the Lotus Notes storage data files view options.

### setMailStorageOptions(MailStorageOptions mailStorageOptions) {#setMailStorageOptions-com.groupdocs.viewer.options.MailStorageOptions-}
```
public void setMailStorageOptions(MailStorageOptions mailStorageOptions)
```


يضبط خيارات عرض ملفات بيانات تخزين Lotus Notes.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | mailStorageOptions | [MailStorageOptions](../../com.groupdocs.viewer.options/mailstorageoptions) | خيارات عرض ملفات تخزين Lotus Notes. |
|

### getProjectManagementOptions() {#getProjectManagementOptions--}
```
public final ProjectManagementOptions getProjectManagementOptions()
```


يسترجع خيارات عرض ملفات إدارة المشاريع.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


**Returns:**
[ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) - the project management files view options.

### setProjectManagementOptions(ProjectManagementOptions projectManagementOptions) {#setProjectManagementOptions-com.groupdocs.viewer.options.ProjectManagementOptions-}
```
public final void setProjectManagementOptions(ProjectManagementOptions projectManagementOptions)
```


يضبط خيارات عرض ملفات إدارة المشاريع.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-ms-project-files/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | projectManagementOptions | [ProjectManagementOptions](../../com.groupdocs.viewer.options/projectmanagementoptions) | خيارات عرض ملفات إدارة المشاريع لتعيينها. |
|

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final SpreadsheetOptions getSpreadsheetOptions()
```


يسترجع خيارات عرض ملفات جداول البيانات.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [عرض جداول Excel و Apple Numbers كملفات HTML و PDF وصور](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)، [تقسيم ورقة العمل إلى صفحات](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/)، و [تحديد خيارات عرض جداول البيانات](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - the spreadsheet files view options.

### setSpreadsheetOptions(SpreadsheetOptions value) {#setSpreadsheetOptions-com.groupdocs.viewer.options.SpreadsheetOptions-}
```
public final void setSpreadsheetOptions(SpreadsheetOptions value)
```


يضبط خيارات عرض ملفات جداول البيانات.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [عرض جداول Excel و Apple Numbers كملفات HTML و PDF وصور](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)، [تقسيم ورقة العمل إلى صفحات](../https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/)، و [تحديد خيارات عرض جداول البيانات](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) | خيارات عرض ملفات جداول البيانات. |
|

### getWordProcessingOptions() {#getWordProcessingOptions--}
```
public final WordProcessingOptions getWordProcessingOptions()
```


خيارات عرض ملفات معالجة Word.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-word-documents/).


**Returns:**
[WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) - the Word processing options for rendering Word documents.

### setWordProcessingOptions(WordProcessingOptions wordProcessingOptions) {#setWordProcessingOptions-com.groupdocs.viewer.options.WordProcessingOptions-}
```
public final void setWordProcessingOptions(WordProcessingOptions wordProcessingOptions)
```


خيارات عرض ملفات معالجة Word.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-word-documents/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | wordProcessingOptions | [WordProcessingOptions](../../com.groupdocs.viewer.options/wordprocessingoptions) | خيارات معالجة Word لعرض مستندات Word. |
|

### getVisioRenderingOptions() {#getVisioRenderingOptions--}
```
public VisioRenderingOptions getVisioRenderingOptions()
```


يسترجع خيارات العرض لمعالجة ملفات Visio عند عرض المستندات.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


**Returns:**
[VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) - the Visio rendering options for processing Visio files.

### setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions) {#setVisioRenderingOptions-com.groupdocs.viewer.options.VisioRenderingOptions-}
```
public void setVisioRenderingOptions(VisioRenderingOptions visioRenderingOptions)
```


يضبط خيارات العرض لمعالجة ملفات Visio عند عرض المستندات.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | visioRenderingOptions | [VisioRenderingOptions](../../com.groupdocs.viewer.options/visiorenderingoptions) | خيارات عرض Visio لمعالجة ملفات Visio. |
|

### getPresentationOptions() {#getPresentationOptions--}
```
public PresentationOptions getPresentationOptions()
```


يسترجع خيارات العرض لمعالجة مستندات العروض التقديمية.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-presentations/).


**Returns:**
com.groupdocs.viewer.options.PresentationOptions - خيارات عرض العروض التقديمية لمعالجة مستندات العروض التقديمية.

### setPresentationOptions(PresentationOptions presentationOptions) {#setPresentationOptions-com.groupdocs.viewer.options.PresentationOptions-}
```
public void setPresentationOptions(PresentationOptions presentationOptions)
```


يضبط خيارات العرض لمعالجة مستندات العروض التقديمية.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-presentations/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | presentationOptions | com.groupdocs.viewer.options.PresentationOptions | خيارات عرض العروض التقديمية لمعالجة مستندات العروض التقديمية. |
|

### getWebDocumentOptions() {#getWebDocumentOptions--}
```
public WebDocumentOptions getWebDocumentOptions()
```


يحصل على خيارات العرض التي تسمح بتخصيص مظهر مخرجات HTML/PDF/PNG/JPEG
عند عرض مستندات الويب.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-web-documents/).


**Returns:**
com.groupdocs.viewer.options.WebDocumentOptions - كائن WebDocumentOptions لتخصيص خيارات العرض.

### setWebDocumentOptions(WebDocumentOptions webDocumentOptions) {#setWebDocumentOptions-com.groupdocs.viewer.options.WebDocumentOptions-}
```
public void setWebDocumentOptions(WebDocumentOptions webDocumentOptions)
```


يضبط خيارات العرض التي تسمح بتخصيص مظهر مخرجات HTML/PDF/PNG/JPEG
عند عرض مستندات الويب.


لمزيد من المعلومات وأمثلة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-web-documents/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | webDocumentOptions | com.groupdocs.viewer.options.WebDocumentOptions | كائن WebDocumentOptions لتخصيص خيارات العرض. |
|

