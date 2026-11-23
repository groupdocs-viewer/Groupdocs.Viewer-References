---
title: "الأمان"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يوفر خيارات أمان مستند PDF."
type: docs
weight: 29
url: /ar/java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

يوفر خيارات أمان مستند PDF.


فئة Security تضم إعدادات وخيارات مختلفة يمكن استخدامها لتطبيق إجراءات الأمان
إلى مستند PDF في مكوّن GroupDocs.Viewer. تشمل هذه الخيارات حماية كلمة المرور،
الأذونات، وأكثر.
للحصول على تفاصيل، راجع [الوثائق](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


مثال على الاستخدام:

````

 Security security = new Security();
 security.setDocumentOpenPassword("myPassword");
 security.setPermissions(Permissions.DENY_MODIFICATION);

 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [Security()](#Security--) | ينشئ مثلاً جديداً من |
الأمان
الفئة.
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getDocumentOpenPassword()](#getDocumentOpenPassword--) | يحصل على كلمة المرور المطلوبة لفتح مستند PDF. |
|
|  | [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | يضبط كلمة المرور المطلوبة لفتح مستند PDF. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | يحصل على كلمة المرور المطلوبة لتغيير إعدادات الأذونات. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | يضبط كلمة المرور المطلوبة لتغيير إعدادات الأذونات. |
|
|  | [getPermissions()](#getPermissions--) | يحصل على أذونات مستند PDF مثل الطباعة، التعديل، واستخراج البيانات. |
|
|  | [setPermissions(int value)](#setPermissions-int-) | يضبط أذونات مستند PDF مثل الطباعة، التعديل، واستخراج البيانات. |
|
### Security() {#Security--}
```
public Security()
```


ينشئ مثلاً جديداً من
الأمان
الفئة.


### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


يحصل على كلمة المرور المطلوبة لفتح مستند PDF.


لعينة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
java.lang.String - كلمة مرور فتح المستند.

### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


يضبط كلمة المرور المطلوبة لفتح مستند PDF.


لعينة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | كلمة مرور فتح المستند. |
|

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


يحصل على كلمة المرور المطلوبة لتغيير إعدادات الأذونات.


باستخدام كلمة مرور الأذونات، يمكنك تقييد الطباعة، التعديل، واستخراج البيانات.
استخدم كلمة مرور الأذونات لتقييد الطباعة، التعديل واستخراج البيانات. لعينة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
java.lang.String - كلمة مرور الأذونات.

### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


يضبط كلمة المرور المطلوبة لتغيير إعدادات الأذونات.


باستخدام كلمة مرور الأذونات، يمكنك تقييد الطباعة، التعديل، واستخراج البيانات.
استخدم كلمة مرور الأذونات لتقييد الطباعة، التعديل واستخراج البيانات. لعينة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.lang.String | كلمة مرور الأذونات. |
|

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


يحصل على أذونات مستند PDF مثل الطباعة، التعديل، واستخراج البيانات.


لعينة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
int - أذونات مستند PDF.

### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


يضبط أذونات مستند PDF مثل الطباعة، التعديل، واستخراج البيانات.


لعينة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | أذونات مستند PDF. |
|

