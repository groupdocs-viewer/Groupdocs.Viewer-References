---
title: "صفحة"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يمثل صفحة واحدة يمكن عرضها."
type: docs
weight: 21
url: /ar/nodejs-java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

يمثل صفحة واحدة يمكن عرضها.

تحدد واجهة Page العقد للوصول إلى صفحة واحدة يمكن عرضها في مكوّن GroupDocs.Viewer ومعالجتها. توفر طرقًا لاسترجاع معلومات مثل رقم الصفحة، الحجم، وخصائص أخرى.

مثال على الاستخدام:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List pages = viewInfo.getPages();
     for (Page page : pages) {
         // Use the page object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is PageImpl.*
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getName()](#getName--) | يسترجع اسم ورقة العمل أو الصفحة. |
| [setName(String name)](#setName-java.lang.String-) | يضبط اسم ورقة العمل أو الصفحة. |
| [getNumber()](#getNumber--) | يسترجع رقم الصفحة. |
| [setNumber(int number)](#setNumber-int-) | يضبط رقم الصفحة. |
| [isVisible()](#isVisible--) | يسترجع مؤشر رؤية الصفحة. |
| [setVisible(boolean visible)](#setVisible-boolean-) | يضبط مؤشر رؤية الصفحة. |
| [getWidth()](#getWidth--) | يسترجع عرض الصفحة بالبكسل عند العرض كملف JPG أو PNG. |
| [setWidth(int width)](#setWidth-int-) | يضبط عرض الصفحة بالبكسل عند العرض كملف JPG أو PNG. |
| [getHeight()](#getHeight--) | يسترجع ارتفاع الصفحة بالبكسل عند العرض كملف JPG أو PNG. |
| [setHeight(int height)](#setHeight-int-) | يضبط ارتفاع الصفحة بالبكسل عند العرض كملف JPG أو PNG. |
| [getLines()](#getLines--) | يسترجع السطور الموجودة في الصفحة عند العرض كملف JPG أو PNG مع تمكين استخراج النص. |
| [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | يضبط السطور الموجودة في الصفحة عند العرض كملف JPG أو PNG مع تمكين استخراج النص. |
### getName() {#getName--}
```
public abstract String getName()
```


يسترجع اسم ورقة العمل أو الصفحة.

**Returns:**
java.lang.String - اسم ورقة العمل أو الصفحة.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


يضبط اسم ورقة العمل أو الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String | الاسم لتعيينه لورقة العمل أو الصفحة. |

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


يسترجع رقم الصفحة.

**Returns:**
int - رقم الصفحة.
### setNumber(int number) {#setNumber-int-}
```
public abstract void setNumber(int number)
```


يضبط رقم الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| number | int | رقم الصفحة لتعيينه. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


يسترجع مؤشر رؤية الصفحة.

**Returns:**
boolean - مؤشر رؤية الصفحة.
### setVisible(boolean visible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean visible)
```


يضبط مؤشر رؤية الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مرئي | boolean | true إذا كانت الصفحة مرئية، false خلاف ذلك. |

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


يسترجع عرض الصفحة بالبكسل عند العرض كملف JPG أو PNG.

**Returns:**
int - عرض الصفحة.
### setWidth(int width) {#setWidth-int-}
```
public abstract void setWidth(int width)
```


يضبط عرض الصفحة بالبكسل عند العرض كملف JPG أو PNG.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | العرض لتعيينه للصفحة. |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


يسترجع ارتفاع الصفحة بالبكسل عند العرض كملف JPG أو PNG.

**Returns:**
int - ارتفاع الصفحة.
### setHeight(int height) {#setHeight-int-}
```
public abstract void setHeight(int height)
```


يضبط ارتفاع الصفحة بالبكسل عند العرض كملف JPG أو PNG.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| height | int | الارتفاع لتعيينه للصفحة. |

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


يسترجع السطور الموجودة في الصفحة عند العرض كملف JPG أو PNG مع تمكين استخراج النص.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - السطور الموجودة في الصفحة.
### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


يضبط السطور الموجودة في الصفحة عند العرض كملف JPG أو PNG مع تمكين استخراج النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lines | java.util.List<com.groupdocs.viewer.results.Line> | قائمة السطور لتعيينها للصفحة. |

