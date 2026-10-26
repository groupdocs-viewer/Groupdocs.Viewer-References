---
title: "ImageQuality"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "جودة الصور في HTML الناتج المضمن في مستندات PDF."
type: docs
weight: 41
url: /ar/nodejs-java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

جودة الصور في HTML الناتج المضمن في مستندات PDF.

تُمثل تعداد ImageQuality جودة الصور في ملف HTML الناتج الموجود داخل مستندات PDF في مكوّن GroupDocs.Viewer. يوفر مستويات مختلفة من جودة الصورة يمكن استخدامها للتحكم في عرض وضغط الصور في مخرجات HTML المُولدة.

مثال على الاستخدام:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## الحقول

| حقل | الوصف |
| --- | --- |
| [LOW](#LOW) | الجودة المقبولة وأفضل أداء. |
| [MEDIUM](#MEDIUM) | جودة أفضل وأداء أبطأ. |
| [HIGH](#HIGH) | أفضل جودة لكن أداء بطيء. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


الجودة المقبولة وأفضل أداء. هذا الإعداد يعطي الأولوية لسرعة العرض على جودة الصورة.

### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


جودة أفضل وأداء أبطأ. هذا الإعداد يوفر توازناً بين جودة الصورة وسرعة العرض.

### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


أفضل جودة لكن أداء بطيء. هذا الإعداد يعطي الأولوية لجودة الصورة على سرعة العرض.

### values() {#values--}
```
public static ImageQuality[] values()
```




**Returns:**
com.groupdocs.viewer.options.ImageQuality[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ImageQuality valueOf(String name)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality)
