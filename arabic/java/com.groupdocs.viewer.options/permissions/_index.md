---
title: "Permissions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يحدد أذونات مستند PDF."
type: docs
weight: 24
url: /ar/java/com.groupdocs.viewer.options/permissions/
---
**Inheritance:**
java.lang.Object
```
public class Permissions
```

يحدد أذونات مستند PDF.


توفر فئة Permissions ثوابت تمثل أذونات مختلفة
يمكن تطبيقها على مستند PDF في مكوّن GroupDocs.Viewer.
تتحكم هذه الأذونات في الإجراءات التي يمكن تنفيذها على مستند PDF،
مثل الطباعة، نسخ النص، تعديل التعليقات التوضيحية، وأكثر.


مثال على الاستخدام:

````

 int permissions = Permissions.DENY_PRINTING | Permissions.DENY_MODIFICATION;
 final Security security = new Security();
 security.setPermissions(permissions);
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
| [Permissions()](#Permissions--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [ALLOW_ALL](#ALLOW-ALL) | السماح بالطباعة، التعديل، واستخراج البيانات. |
|
|  | [DENY_PRINTING](#DENY-PRINTING) | منع الطباعة. |
|
|  | [DENY_MODIFICATION](#DENY-MODIFICATION) | منع تعديل المحتوى، تعبئة النماذج، إضافة أو تعديل التعليقات التوضيحية. |
|
|  | [DENY_DATA_EXTRACTION](#DENY-DATA-EXTRACTION) | منع استخراج النص والرسومات. |
|
|  | [DENY_ALL](#DENY-ALL) | منع الطباعة، التعديل، واستخراج البيانات. |
|
### Permissions() {#Permissions--}
```
public Permissions()
```


### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


السماح بالطباعة، التعديل، واستخراج البيانات.


### DENY_PRINTING {#DENY-PRINTING}
```
public static final int DENY_PRINTING
```


منع الطباعة.


### DENY_MODIFICATION {#DENY-MODIFICATION}
```
public static final int DENY_MODIFICATION
```


منع تعديل المحتوى، تعبئة النماذج، إضافة أو تعديل التعليقات التوضيحية.


### DENY_DATA_EXTRACTION {#DENY-DATA-EXTRACTION}
```
public static final int DENY_DATA_EXTRACTION
```


منع استخراج النص والرسومات.


### DENY_ALL {#DENY-ALL}
```
public static final int DENY_ALL
```


منع الطباعة، التعديل، واستخراج البيانات.


