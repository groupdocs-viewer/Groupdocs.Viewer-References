---
title: "Layer"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يمثل طبقة موجودة في رسم CAD."
type: docs
weight: 16
url: /ar/nodejs-java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

يمثل طبقة موجودة في رسم CAD.

واجهة Layer تحدد العقدة للوصول إلى طبقة ومعالجتها داخل رسم CAD في مكوّن GroupDocs.Viewer. توفر طرقًا لاسترجاع معلومات مثل اسم الطبقة، والظهور، وغيرها من الخصائص.

مثال على الاستخدام:

```

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layers = viewInfo.getLayers();
     for (Layer layer : layers) {
         // Use the layer object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LayerImpl.*
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getName()](#getName--) | يسترجع اسم الطبقة. |
| [setName(String name)](#setName-java.lang.String-) | يضبط اسم الطبقة. |
| [isVisible()](#isVisible--) | يتحقق من ظهور الطبقة. |
| [setVisible(boolean isVisible)](#setVisible-boolean-) | يضبط ظهور الطبقة. |
| [equals(Object other)](#equals-java.lang.Object-) | يتحقق مما إذا كان هذا الكائن مساويًا للكائن المقدم. |
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
| الاسم | java.lang.String | الاسم الجديد للطبقة. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


يتحقق من ظهور الطبقة.

طبقات الرسم CAD التي تم إيقاف تشغيلها أو تجميدها تكون غير مرئية. لعرض الطبقات غير المرئية، استخدم خيار [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions\#setLayers-List-).

**Returns:**
boolean -  true إذا كانت الطبقة مرئية،  false خلاف ذلك.
### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


يضبط ظهور الطبقة.

إذا  true ، ستكون الطبقة مرئية؛ إذا  false ، ستكون مخفية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| isVisible | boolean | ما إذا كان يجب أن تكون الطبقة مرئية أم لا. |

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


يتحقق مما إذا كان هذا الكائن مساويًا للكائن المقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| أخرى | java.lang.Object | الكائن للمقارنة. |

**Returns:**
boolean -  true  إذا كان الكائنان متساويين،  false  خلاف ذلك.
