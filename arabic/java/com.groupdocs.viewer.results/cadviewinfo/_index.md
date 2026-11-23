---
title: "CadViewInfo"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يمثل معلومات العرض لتصميم CAD."
type: docs
weight: 13
url: /ar/java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

يمثل معلومات العرض لتصميم CAD.


تحدد واجهة CadViewInfo العقد لاسترجاع معلومات العرض الخاصة برسم CAD
في مكوّن GroupDocs.Viewer. يوفر طرقًا للوصول إلى طبقات رسومات CAD.


مثال على الاستخدام:

````

 try (Viewer viewer = new Viewer("document.plt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is CadViewInfoImpl.*

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getLayers()](#getLayers--) | يسترجع قائمة الطبقات في رسم CAD. |
|
|  | [setLayers(List<Layer> layers)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | يضبط قائمة الطبقات في رسم CAD. |
|
|  | [getLayouts()](#getLayouts--) | يسترجع قائمة التخطيطات الموجودة داخل رسم CAD. |
|
|  | [setLayouts(List<Layout> layouts)](#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--) | يضبط قائمة التخطيطات الموجودة داخل رسم CAD. |
|
### getLayers() {#getLayers--}
```
public abstract List<Layer> getLayers()
```


يسترجع قائمة الطبقات في رسم CAD.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - الطبقات في رسم CAD.

### setLayers(List<Layer> layers) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public abstract void setLayers(List<Layer> layers)
```


يضبط قائمة الطبقات في رسم CAD.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الطبقات | java.util.List<com.groupdocs.viewer.results.Layer> | الطبقات التي سيتم ضبطها لرسم CAD. |
|

### getLayouts() {#getLayouts--}
```
public abstract List<Layout> getLayouts()
```


يسترجع قائمة التخطيطات الموجودة داخل رسم CAD.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layout> - التخطيطات في رسم CAD.

### setLayouts(List<Layout> layouts) {#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--}
```
public abstract void setLayouts(List<Layout> layouts)
```


يضبط قائمة التخطيطات الموجودة داخل رسم CAD.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | التخطيطات | java.util.List<com.groupdocs.viewer.results.Layout> | التخطيطات التي سيتم ضبطها لرسم CAD. |
|

