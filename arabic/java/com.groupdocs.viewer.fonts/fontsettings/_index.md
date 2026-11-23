---
title: "FontSettings"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يوفر طرقًا للعمل مع المصادر للبحث عن خطوط TrueType."
type: docs
weight: 12
url: /ar/java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

يوفر طرقًا للعمل مع المصادر للبحث عن خطوط TrueType.


يتم استخدام فئة FontSettings لتحديد وإدارة المصادر لتحديد مواقع خطوط TrueType.
توفر طرقًا لإضافة وإعادة تعيين مصادر الخطوط لواجهة برمجة تطبيقات GroupDocs.Viewer.


مثال على الاستخدام:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | يضبط المصادر للبحث عن خطوط TrueType عند عرض المستندات. |
|
|  | [resetFontSources()](#resetFontSources--) | يعيد تعيين مصادر الخطوط التي تم ضبطها مسبقًا. |
|
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


يضبط المصادر للبحث عن خطوط TrueType عند عرض المستندات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | مصادر الخطوط التي سيتم ضبطها. |
|

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


يعيد تعيين مصادر الخطوط التي تم ضبطها مسبقًا.


