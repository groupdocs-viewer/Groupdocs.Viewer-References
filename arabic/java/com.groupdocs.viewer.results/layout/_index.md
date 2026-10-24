---
title: "Layout"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يمثل تخطيطًا موجودًا في تصميم CAD."
type: docs
weight: 17
url: /ar/java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

يمثل تخطيطًا موجودًا في تصميم CAD.


تحدد واجهة Layout العقد للوصول إلى تخطيط داخل رسم CAD ومعالجته
في مكوّن GroupDocs.Viewer. يوفر طرقًا لاسترجاع المعلومات مثل اسم التخطيط،
الأبعاد، وغيرها من الخصائص.


مثال على الاستخدام:

````

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layouts = viewInfo.getLayouts();
     for (Layout layout : layouts) {
         // Use the layout object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LayoutImpl.*

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getName()](#getName--) | يسترجع اسم التخطيط. |
|
|  | [setName(String name)](#setName-java.lang.String-) | يضبط اسم التخطيط. |
|
|  | [getWidth()](#getWidth--) | يسترجع عرض التخطيط. |
|
|  | [setWidth(double width)](#setWidth-double-) | يضبط عرض التخطيط. |
|
|  | [getHeight()](#getHeight--) | يسترجع ارتفاع التخطيط. |
|
|  | [setHeight(double height)](#setHeight-double-) | يضبط ارتفاع التخطيط. |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | يتحقق مما إذا كان هذا الكائن مساويًا للكائن المقدم. |
|
### getName() {#getName--}
```
public abstract String getName()
```


يسترجع اسم التخطيط.


**Returns:**
java.lang.String - اسم التخطيط.

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


يضبط اسم التخطيط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | name | java.lang.String | الاسم لتعيينه للتخطيط. |
|

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


يسترجع عرض التخطيط.


**Returns:**
double - عرض التخطيط.

### setWidth(double width) {#setWidth-double-}
```
public abstract void setWidth(double width)
```


يضبط عرض التخطيط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | width | double | العرض لتعيينه للتخطيط. |
|

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


يسترجع ارتفاع التخطيط.


**Returns:**
double - ارتفاع التخطيط.

### setHeight(double height) {#setHeight-double-}
```
public abstract void setHeight(double height)
```


يضبط ارتفاع التخطيط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | ارتفاع | double | الارتفاع لتعيينه للتخطيط. |
|

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


يتحقق مما إذا كان هذا الكائن مساويًا للكائن المقدم.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | أخرى | java.lang.Object | الكائن للمقارنة. |
|

**Returns:**
منطقي -  true  إذا كانت الكائنات متساوية،  false  وإلا.

