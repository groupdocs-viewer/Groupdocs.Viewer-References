---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يحدد وضع تجاوز النص لتصيير مستندات جداول البيانات إلى HTML."
type: docs
weight: 46
url: /ar/nodejs-java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

يحدد وضع تجاوز النص لتصيير مستندات جداول البيانات إلى HTML.

يمثل تعداد TextOverflowMode أوضاعًا مختلفة للتعامل مع تجاوز النص في مكوّن GroupDocs.Viewer. يوفر مجموعة من الخيارات المحددة مسبقًا التي يمكن استخدامها للتحكم في كيفية عرض النص عندما يتجاوز المساحة المتاحة في الخلايا أثناء تحويل مستندات الجداول إلى HTML. للحصول على تفاصيل، راجع [documentation][].

مثال على الاستخدام:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow
## الحقول

| حقل | الوصف |
| --- | --- |
| [OVERLAY](#OVERLAY) | تغطية الخلايا التالية حتى وإن لم تكن فارغة. |
| [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | تغطية الخلايا التالية فقط إذا كانت فارغة. |
| [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | توسيع الأعمدة لتناسب النص. |
| [HIDE_TEXT](#HIDE-TEXT) | إخفاء النص المتجاوز. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


تغطية الخلايا التالية حتى وإن لم تكن فارغة. يتيح هذا الوضع للنص أن يتجاوز إلى الخلايا المجاورة بغض النظر عن محتواها.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


تغطية الخلايا التالية فقط إذا كانت فارغة. يتيح هذا الوضع للنص أن يتجاوز إلى الخلايا المجاورة فقط إذا كانت تلك الخلايا فارغة.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


توسيع الأعمدة لتناسب النص. يضبط هذا الوضع عرض الأعمدة تلقائيًا لاستيعاب النص المتجاوز.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


إخفاء النص المتجاوز. يخفى هذا الوضع النص المتجاوز، مما يمنع عرضه.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

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
| الاسم | java.lang.String |  |

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode)
