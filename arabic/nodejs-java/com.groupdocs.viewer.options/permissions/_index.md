---
title: "Permissions"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يحدد أذونات مستند PDF."
type: docs
weight: 24
url: /ar/nodejs-java/com.groupdocs.viewer.options/permissions/
---
**Inheritance:**
java.lang.Object
```
public class Permissions
```

يحدد أذونات مستند PDF.

توفر فئة Permissions ثوابت تمثل أذونات مختلفة يمكن تطبيقها على مستند PDF في مكوّن GroupDocs.Viewer. تتحكم هذه الأذونات في الإجراءات التي يمكن إجراؤها على مستند PDF، مثل الطباعة، نسخ النص، تعديل التعليقات، وأكثر.

مثال على الاستخدام:

```

 int permissions = Permissions.DENY_PRINTING | Permissions.DENY_MODIFICATION;
 final Security security = new Security();
 security.setPermissions(permissions);
 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [Permissions()](#Permissions--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | السماح بالطباعة، والتعديل، واستخراج البيانات. |
| [DENY_PRINTING](#DENY-PRINTING) | رفض الطباعة. |
| [DENY_MODIFICATION](#DENY-MODIFICATION) | رفض تعديل المحتوى، تعبئة النماذج، إضافة أو تعديل التعليقات. |
| [DENY_DATA_EXTRACTION](#DENY-DATA-EXTRACTION) | رفض استخراج النصوص والرسومات. |
| [DENY_ALL](#DENY-ALL) | رفض الطباعة، والتعديل، واستخراج البيانات. |
### Permissions() {#Permissions--}
```
public Permissions()
```


### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


السماح بالطباعة، والتعديل، واستخراج البيانات.

### DENY_PRINTING {#DENY-PRINTING}
```
public static final int DENY_PRINTING
```


رفض الطباعة.

### DENY_MODIFICATION {#DENY-MODIFICATION}
```
public static final int DENY_MODIFICATION
```


رفض تعديل المحتوى، تعبئة النماذج، إضافة أو تعديل التعليقات.

### DENY_DATA_EXTRACTION {#DENY-DATA-EXTRACTION}
```
public static final int DENY_DATA_EXTRACTION
```


رفض استخراج النصوص والرسومات.

### DENY_ALL {#DENY-ALL}
```
public static final int DENY_ALL
```


رفض الطباعة، والتعديل، واستخراج البيانات.

