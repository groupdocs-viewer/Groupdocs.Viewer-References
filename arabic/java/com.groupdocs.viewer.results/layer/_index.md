---
title: "الطبقة"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يمثل طبقة موجودة في تصميم CAD."
type: docs
weight: 16
url: /ar/java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

يمثل طبقة موجودة في تصميم CAD.


واجهة Layer تحدد العقد للوصول إلى طبقة داخل رسم CAD وتعديلها.
في مكوّن GroupDocs.Viewer. يوفر طرقًا لاسترجاع المعلومات مثل اسم الطبقة،
الظهور، وخصائص أخرى.


مثال على الاستخدام:

````

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layers = viewInfo.getLayers();
     for (Layer layer : layers) {
         // Use the layer object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LayerImpl.*

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getName()](#getName--) | يسترجع اسم الطبقة. |
|
|  | [setName(String name)](#setName-java.lang.String-) | يضبط اسم الطبقة. |
|
|  | [isVisible()](#isVisible--) | يتحقق من ظهور الطبقة. |
|
|  | [setVisible(boolean isVisible)](#setVisible-boolean-) | يضبط ظهور الطبقة. |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | يتحقق مما إذا كان هذا الكائن مساويًا للكائن المقدم. |
|
### getName() {#getName--}
```
public abstract String getName()
```


يسترجع اسم الطبقة.


**Note:** Layer names are case sensitive.


**Returns:**
java.lang.String - اسم الطبقة.

### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


يضبط اسم الطبقة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | name | java.lang.String | الاسم الجديد للطبقة. |
|

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


يتحقق من ظهور الطبقة.


طبقات رسومات CAD التي تم إيقاف تشغيلها أو تجميدها غير مرئية.
لرسم الطبقات غير المرئية، استخدم خيار [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions#setLayers-List-).


**Returns:**
boolean -  true  إذا كانت الطبقة مرئية،  false  غير ذلك.

### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


يضبط ظهور الطبقة.


إذا
true
، ستكون الطبقة مرئية؛ إذا
false
، ستُخفى.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | isVisible | boolean | ما إذا كان يجب أن تكون الطبقة مرئية أم لا. |
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

