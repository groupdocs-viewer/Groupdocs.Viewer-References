---
title: "OutlookOptions"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يوفر خيارات لعرض ملفات بيانات Outlook."
type: docs
weight: 20
url: /ar/nodejs-java/com.groupdocs.viewer.options/outlookoptions/
---
**Inheritance:**
java.lang.Object
```
public class OutlookOptions
```

يوفر خيارات لعرض ملفات بيانات Outlook.

تحتوي فئة OutlookOptions على إعدادات ومعلمات مختلفة يمكن استخدامها للتحكم في عرض ملفات بيانات Outlook (مثل ملفات PST أو OST) في مكوّن GroupDocs.Viewer.

للتفاصيل، راجع [documentation][].

مثال على الاستخدام:

```

 OutlookOptions options = new OutlookOptions();
 options.setAddressFilter("@gmail.com");
 options.setFolder("folderName");

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setOutlookOptions(options);

 try (Viewer viewer = new Viewer("mail.pst")) {
   viewer.view(htmlViewOptions);
   // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [OutlookOptions()](#OutlookOptions--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFolder()](#getFolder--) | يحصل على اسم المجلد المراد عرضه. |
| [setFolder(String value)](#setFolder-java.lang.String-) | يضبط اسم المجلد المراد عرضه. |
| [getTextFilter()](#getTextFilter--) | يحصل على الكلمات المفتاحية المستخدمة لتصفية الرسائل. |
| [setTextFilter(String value)](#setTextFilter-java.lang.String-) | يحصل على الكلمات المفتاحية المستخدمة لتصفية الرسائل. |
| [getAddressFilter()](#getAddressFilter--) | يحصل على عنوان البريد الإلكتروني المستخدم لتصفية الرسائل حسب المرسل أو المستلم. |
| [setAddressFilter(String value)](#setAddressFilter-java.lang.String-) | يضبط عنوان البريد الإلكتروني المستخدم لتصفية الرسائل حسب المرسل أو المستلم. |
| [getMaxItemsInFolder()](#getMaxItemsInFolder--) | يحصل على الحد الأقصى لعدد الرسائل أو العناصر التي يمكن عرضها من مجلد واحد. |
| [setMaxItemsInFolder(int value)](#setMaxItemsInFolder-int-) | يضبط الحد الأقصى لعدد الرسائل أو العناصر التي يمكن عرضها من مجلد واحد. |
### OutlookOptions() {#OutlookOptions--}
```
public OutlookOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


يحصل على اسم المجلد المراد عرضه. اسم المجلد (مثل Inbox أو Sent Item أو Deleted Items) المراد عرضه.

عند عرض ملف بيانات Outlook، يقوم GroupDocs.Viewer بعرض الرسائل من جميع المجلدات الموجودة في الملف (بما في ذلك المجلدات المتداخلة). استخدم هذه الخاصية لعرض العناصر من مجلد محدد. للحصول على مثال على الشيفرة، راجع هذا [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder

**Returns:**
java.lang.String - اسم المجلد المراد عرضه.
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


يضبط اسم المجلد المراد عرضه. اسم المجلد (مثل Inbox أو Sent Item أو Deleted Items) للعرض.

عند عرض ملف بيانات Outlook، يقوم GroupDocs.Viewer بعرض الرسائل من جميع المجلدات الموجودة في الملف (بما في ذلك المجلدات المتداخلة). استخدم هذه الخاصية لعرض العناصر من مجلد محدد. للحصول على مثال على الشيفرة، راجع هذا [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | اسم المجلد المراد عرضه. |

### getTextFilter() {#getTextFilter--}
```
public final String getTextFilter()
```


يحصل على الكلمات المفتاحية المستخدمة لتصفية الرسائل.

استخدم هذه الخاصية لعرض جميع الرسائل التي تحتوي على نص محدد في الموضوع أو النص. للحصول على مثال على الشفرة، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Returns:**
java.lang.String - الكلمات المفتاحية.
### setTextFilter(String value) {#setTextFilter-java.lang.String-}
```
public final void setTextFilter(String value)
```


يحصل على الكلمات المفتاحية المستخدمة لتصفية الرسائل.

استخدم هذه الخاصية لعرض جميع الرسائل التي تحتوي على نص محدد في الموضوع أو النص. للحصول على مثال على الشفرة، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | الكلمات المفتاحية. |

### getAddressFilter() {#getAddressFilter--}
```
public final String getAddressFilter()
```


يحصل على عنوان البريد الإلكتروني المستخدم لتصفية الرسائل حسب المرسل أو المستلم.

استخدم هذه الخاصية لعرض جميع الرسائل التي تحتوي على نص محدد في عنوان المرسل\ufffds أو المستلم\ufffds. للحصول على مثال على الشيفرة، راجع الـ [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Returns:**
java.lang.String - عنوان البريد الإلكتروني المستخدم لتصفية الرسائل.
### setAddressFilter(String value) {#setAddressFilter-java.lang.String-}
```
public final void setAddressFilter(String value)
```


يضبط عنوان البريد الإلكتروني المستخدم لتصفية الرسائل حسب المرسل أو المستلم.

استخدم هذه الخاصية لعرض جميع الرسائل التي تحتوي على نص محدد في عنوان المرسل\ufffds أو المستلم\ufffds. للحصول على مثال على الشيفرة، راجع الـ [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | عنوان البريد الإلكتروني المستخدم لتصفية الرسائل. |

### getMaxItemsInFolder() {#getMaxItemsInFolder--}
```
public final int getMaxItemsInFolder()
```


يحصل على الحد الأقصى لعدد الرسائل أو العناصر التي يمكن عرضها من مجلد واحد.

يمكن أن تكون ملفات بيانات Outlook كبيرة وقد يستغرق استرجاع جميع الرسائل وقتًا كبيرًا. يحد هذا الإعداد الحد الأقصى لعدد الرسائل أو العناصر (مثل جهات الاتصال والمهام) التي يتم عرضها. القيمة الافتراضية هي 50. اضبط القيمة على 0 لعرض جميع الرسائل. للحصول على مثال على الشيفرة، راجع الـ [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render

**Returns:**
int - الحد الأقصى لعدد الرسائل أو العناصر التي يمكن عرضها من مجلد واحد.
### setMaxItemsInFolder(int value) {#setMaxItemsInFolder-int-}
```
public final void setMaxItemsInFolder(int value)
```


يضبط الحد الأقصى لعدد الرسائل أو العناصر التي يمكن عرضها من مجلد واحد.

يمكن أن تكون ملفات بيانات Outlook كبيرة وقد يستغرق استرجاع جميع الرسائل وقتًا كبيرًا. يحد هذا الإعداد الحد الأقصى لعدد الرسائل أو العناصر (مثل جهات الاتصال والمهام) التي يتم عرضها. القيمة الافتراضية هي 50. اضبط القيمة على 0 لعرض جميع الرسائل. للحصول على مثال على الشيفرة، راجع الـ [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | الحد الأقصى لعدد الرسائل أو العناصر التي يمكن عرضها من مجلد واحد. |

