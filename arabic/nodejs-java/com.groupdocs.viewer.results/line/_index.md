---
title: "خط"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يمثل مستطيلًا موضعًا نسبيًا يحتوي سطرًا واحدًا."
type: docs
weight: 18
url: /ar/nodejs-java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

يمثل مستطيلًا موضعًا نسبيًا يحتوي سطرًا واحدًا.

واجهة Line تحدد العقد للوصول إلى خط ممثل بمستطيل في مكوّن GroupDocs.Viewer وتعديله. توفر طرقًا لاسترجاع معلومات مثل نص الخط، الموقع، وحجم المستطيل.

مثال على الاستخدام:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List lines = viewInfo.getPages().get(0).getLines();
     for (Line line : lines) {
         // Use the line object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LineImpl.*
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getWords()](#getWords--) | يسترجع الكلمات الموجودة في الخط. |
| [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | يضبط الكلمات الموجودة في الخط. |
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


يسترجع الكلمات الموجودة في الخط.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - الكلمات الموجودة في الخط.
### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


يضبط الكلمات الموجودة في الخط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| wordList | java.util.List<com.groupdocs.viewer.results.Word> | الكلمات الموجودة في الخط. |

