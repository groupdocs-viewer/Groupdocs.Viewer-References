---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يحدد وضع تجاوز النص عند تحويل مستندات الجداول إلى HTML."
type: docs
weight: 46
url: /ar/java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

يحدد وضع تجاوز النص عند تحويل مستندات الجداول إلى HTML.


يمثل تعداد TextOverflowMode أوضاعًا مختلفة لمعالجة تجاوز النص في مكوّن GroupDocs.Viewer.
يوفر مجموعة من الخيارات المحددة مسبقًا التي يمكن استخدامها للتحكم في طريقة عرض النص عندما يتجاوز المتاح
المساحة في الخلايا أثناء تحويل مستندات الجداول إلى HTML.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


مثال على الاستخدام:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [OVERLAY](#OVERLAY) | تغطية الخلايا التالية حتى وإن لم تكن فارغة. |
|
|  | [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | تغطية الخلايا التالية فقط إذا كانت فارغة. |
|
|  | [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | توسيع الأعمدة لتناسب النص. |
|
|  | [HIDE_TEXT](#HIDE-TEXT) | إخفاء النص المتجاوز. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


تغطية الخلايا التالية حتى وإن لم تكن فارغة.
هذا الوضع يسمح للنص بالتجاوز إلى الخلايا المجاورة، بغض النظر عن محتواها.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


تغطية الخلايا التالية فقط إذا كانت فارغة.
هذا الوضع يسمح للنص بالتجاوز إلى الخلايا المجاورة فقط إذا كانت تلك الخلايا فارغة.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


توسيع الأعمدة لتناسب النص.
هذا الوضع يضبط عرض الأعمدة تلقائيًا لاستيعاب النص المتجاوز.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


إخفاء النص المتجاوز.
هذا الوضع يخفي النص المتجاوز، مما يمنعه من العرض.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### values() {#values--}
```
public static TextOverflowMode[] values()
```




**Returns:**
com.groupdocs.viewer.options.TextOverflowMode[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TextOverflowMode valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode)
