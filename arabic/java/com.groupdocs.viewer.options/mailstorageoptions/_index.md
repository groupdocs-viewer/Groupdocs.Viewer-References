---
title: "MailStorageOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يوفر خيارات لعرض ملفات بيانات Mail storage Lotus Notes MBox."
type: docs
weight: 19
url: /ar/java/com.groupdocs.viewer.options/mailstorageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageOptions
```

يوفر خيارات لتصيير ملفات تخزين البريد (Lotus Notes، MBox).


فئة MailStorageOptions تضم إعدادات ومعلمات مختلفة يمكن استخدامها
للتحكم في عرض ملفات تخزين البريد (مثل Lotus Notes أو MBox) في مكوّن GroupDocs.Viewer.


للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options).


مثال على الاستخدام:

````

 MailStorageOptions options = new MailStorageOptions();
 options.setAddressFilter("@gmail.com");
 options.setMaxItems(10);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setMailStorageOptions(options);

 try (Viewer viewer = new Viewer("mail.msg")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [MailStorageOptions()](#MailStorageOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getTextFilter()](#getTextFilter--) | يحصل على الكلمات المفتاحية المستخدمة لتصفية الرسائل. |
|
|  | [setTextFilter(String textFilter)](#setTextFilter-java.lang.String-) | يضبط الكلمات المفتاحية المستخدمة لتصفية الرسائل. |
|
|  | [getAddressFilter()](#getAddressFilter--) | يحصل على عنوان البريد الإلكتروني المستخدم لتصفية الرسائل حسب المرسل أو المستلم. |
|
|  | [setAddressFilter(String addressFilter)](#setAddressFilter-java.lang.String-) | يضبط عنوان البريد الإلكتروني المستخدم لتصفية الرسائل حسب المرسل أو المستلم. |
|
|  | [getMaxItems()](#getMaxItems--) | يحصل على الحد الأقصى لعدد الرسائل أو العناصر التي سيتم عرضها. |
|
|  | [setMaxItems(int maxItems)](#setMaxItems-int-) | يضبط الحد الأقصى لعدد الرسائل أو العناصر التي سيتم عرضها. |
|
### MailStorageOptions() {#MailStorageOptions--}
```
public MailStorageOptions()
```


### getTextFilter() {#getTextFilter--}
```
public String getTextFilter()
```


يحصل على الكلمات المفتاحية المستخدمة لتصفية الرسائل.


استخدم هذه الخاصية لعرض جميع الرسائل التي تحتوي على نص محدد في الموضوع أو النص. للحصول على مثال على الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages).


**Returns:**
java.lang.String - الكلمات المفتاحية المستخدمة لتصفية الرسائل.

### setTextFilter(String textFilter) {#setTextFilter-java.lang.String-}
```
public void setTextFilter(String textFilter)
```


يضبط الكلمات المفتاحية المستخدمة لتصفية الرسائل.


استخدم هذه الخاصية لعرض جميع الرسائل التي تحتوي على نص محدد في الموضوع أو النص. للحصول على مثال على الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | textFilter | java.lang.String | الكلمات المفتاحية المستخدمة لتصفية الرسائل. |
|

### getAddressFilter() {#getAddressFilter--}
```
public String getAddressFilter()
```


يحصل على عنوان البريد الإلكتروني المستخدم لتصفية الرسائل حسب المرسل أو المستلم.


استخدم هذه الخاصية لعرض جميع الرسائل التي تحتوي على نص محدد في عنوان المرسل\\u2019s أو عنوان المستلم\\u2019s. للحصول على مثال على الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages).


**Returns:**
java.lang.String - عنوان البريد الإلكتروني المستخدم لتصفية الرسائل.

### setAddressFilter(String addressFilter) {#setAddressFilter-java.lang.String-}
```
public void setAddressFilter(String addressFilter)
```


يضبط عنوان البريد الإلكتروني المستخدم لتصفية الرسائل حسب المرسل أو المستلم.


استخدم هذه الخاصية لعرض جميع الرسائل التي تحتوي على نص محدد في عنوان المرسل\\u2019s أو عنوان المستلم\\u2019s. للحصول على مثال على الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | addressFilter | java.lang.String | عنوان البريد الإلكتروني المستخدم لتصفية الرسائل. |
|

### getMaxItems() {#getMaxItems--}
```
public int getMaxItems()
```


يحصل على الحد الأقصى لعدد الرسائل أو العناصر التي سيتم عرضها.


يمكن أن تكون ملفات بيانات Lotus Notes كبيرة، وقد يستغرق استرجاع جميع الرسائل وقتًا كبيرًا.
يقوم هذا الإعداد بتحديد الحد الأقصى لعدد الرسائل أو العناصر التي يتم عرضها.


***Note:** The default value is 0, which means all messages will be rendered.*
للحصول على مثال على الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render).


**Returns:**
int - الحد الأقصى لعدد الرسائل أو العناصر التي سيتم عرضها.

### setMaxItems(int maxItems) {#setMaxItems-int-}
```
public void setMaxItems(int maxItems)
```


يضبط الحد الأقصى لعدد الرسائل أو العناصر التي سيتم عرضها.


يمكن أن تكون ملفات بيانات Lotus Notes كبيرة، وقد يستغرق استرجاع جميع الرسائل وقتًا كبيرًا.
يقوم هذا الإعداد بتحديد الحد الأقصى لعدد الرسائل أو العناصر التي يتم عرضها.


***Note:** The default value is 0, which means all messages will be rendered.*
للحصول على مثال على الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | maxItems | int | الحد الأقصى لعدد الرسائل أو العناصر التي سيتم عرضها. |
|

