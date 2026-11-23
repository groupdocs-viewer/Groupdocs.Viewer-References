---
title: "TextOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "خيارات تقسيم ملفات النص إلى صفحات."
type: docs
weight: 32
url: /ar/java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

خيارات تقسيم ملفات النص إلى صفحات.


توفر فئة TextOptions خيارات لتقسيم ملفات النص إلى صفحات في مكوّن GroupDocs.Viewer.
تتيح لك التحكم في كيفية تقسيم ملفات النص إلى صفحات فردية لأغراض العرض والرؤية.


مثال على الاستخدام:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [TextOptions()](#TextOptions--) | ينشئ مثلاً جديداً من |
TextOptions
الفئة.
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getMaxCharsPerRow()](#getMaxCharsPerRow--) | يحصل على الحد الأقصى لعدد الأحرف في الصف الواحد على الصفحة. |
|
|  | [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | يضبط الحد الأقصى لعدد الأحرف في الصف الواحد على الصفحة. |
|
|  | [getMaxRowsPerPage()](#getMaxRowsPerPage--) | يحصل على الحد الأقصى لعدد الصفوف في الصفحة. |
|
|  | [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | يضبط الحد الأقصى لعدد الصفوف في الصفحة. |
|
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


ينشئ مثلاً جديداً من
TextOptions
الفئة.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


يحصل على الحد الأقصى لعدد الأحرف في الصف الواحد على الصفحة.


***Note:** The default value is 85.*
القيمة الافتراضية هي 85. للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Returns:**
int - الحد الأقصى لعدد الأحرف في الصف الواحد على الصفحة.

### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


يضبط الحد الأقصى لعدد الأحرف في الصف الواحد على الصفحة.


***Note:** The default value is 85.*
القيمة الافتراضية هي 85. للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | maxCharsPerRow | int | الحد الأقصى لعدد الأحرف في الصف الواحد على الصفحة. |
|

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


يحصل على الحد الأقصى لعدد الصفوف في الصفحة.


***Note:** The default value is 55.*
القيمة الافتراضية هي 55. للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Returns:**
int - الحد الأقصى لعدد الصفوف.

### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


يضبط الحد الأقصى لعدد الصفوف في الصفحة.


***Note:** The default value is 55.*
القيمة الافتراضية هي 55. للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | maxRowsPerPage | int | الحد الأقصى لعدد الصفوف. |
|

