---
title: "Security"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "Provides PDF document security options."
type: docs
weight: 29
url: /ar/nodejs-java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

Provides PDF document security options.

تُجمل فئة Security مجموعة متنوعة من الإعدادات والخيارات التي يمكن استخدامها لتطبيق إجراءات الأمان على مستند PDF في مكوّن GroupDocs.Viewer. تشمل هذه الخيارات حماية كلمة المرور، الأذونات، وأكثر من ذلك. للحصول على تفاصيل، راجع [documentation][].

مثال على الاستخدام:

```

 Security security = new Security();
 security.setDocumentOpenPassword("myPassword");
 security.setPermissions(Permissions.DENY_MODIFICATION);

 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [Security()](#Security--) | ينشئ مثيلاً جديداً من فئة  Security  . |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getDocumentOpenPassword()](#getDocumentOpenPassword--) | يحصل على كلمة المرور المطلوبة لفتح مستند PDF. |
| [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | يضبط كلمة المرور المطلوبة لفتح مستند PDF. |
| [getPermissionsPassword()](#getPermissionsPassword--) | يحصل على كلمة المرور المطلوبة لتغيير إعدادات الأذونات. |
| [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | يضبط كلمة المرور المطلوبة لتغيير إعدادات الأذونات. |
| [getPermissions()](#getPermissions--) | يحصل على أذونات مستند PDF مثل الطباعة والتعديل واستخراج البيانات. |
| [setPermissions(int value)](#setPermissions-int-) | يضبط أذونات مستند PDF مثل الطباعة والتعديل واستخراج البيانات. |
### Security() {#Security--}
```
public Security()
```


ينشئ مثيلاً جديداً من فئة  Security  .

### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


يحصل على كلمة المرور المطلوبة لفتح مستند PDF.

لعينة الكود، انظر إلى [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String - كلمة مرور فتح المستند.
### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


يضبط كلمة المرور المطلوبة لفتح مستند PDF.

لعينة الكود، انظر إلى [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | كلمة مرور فتح المستند. |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


يحصل على كلمة المرور المطلوبة لتغيير إعدادات الأذونات.

باستخدام كلمة مرور الأذونات، يمكنك تقييد الطباعة والتعديل واستخراج البيانات. استخدم كلمة مرور الأذونات لتقييد الطباعة والتعديل واستخراج البيانات. لعينة الكود، انظر إلى [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String - كلمة مرور الأذونات.
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


يضبط كلمة المرور المطلوبة لتغيير إعدادات الأذونات.

باستخدام كلمة مرور الأذونات، يمكنك تقييد الطباعة والتعديل واستخراج البيانات. استخدم كلمة مرور الأذونات لتقييد الطباعة والتعديل واستخراج البيانات. لعينة الكود، انظر إلى [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | كلمة مرور الأذونات. |

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


يحصل على أذونات مستند PDF مثل الطباعة والتعديل واستخراج البيانات.

لعينة الكود، انظر إلى [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
int - أذونات مستند PDF.
### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


يضبط أذونات مستند PDF مثل الطباعة والتعديل واستخراج البيانات.

لعينة الكود، انظر إلى [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | أذونات مستند PDF. |

