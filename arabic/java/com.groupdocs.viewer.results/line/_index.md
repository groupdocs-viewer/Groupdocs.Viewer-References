---
title: "Line"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يمثل مستطيلًا موضعًا نسبيًا يحتوي على سطر واحد."
type: docs
weight: 18
url: /ar/java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

يمثل مستطيلًا موضعًا نسبيًا يحتوي على سطر واحد.


واجهة Line تحدد العقد للوصول إلى خط ممثل بمستطيل ومعالجته
في مكوّن GroupDocs.Viewer. يوفر طرقًا لاسترجاع المعلومات مثل نص السطر،
الموضع، وحجم المستطيل.


مثال على الاستخدام:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List lines = viewInfo.getPages().get(0).getLines();
     for (Line line : lines) {
         // Use the line object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is LineImpl.*

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWords()](#getWords--) | يسترجع الكلمات الموجودة في السطر. |
|
|  | [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | يضبط الكلمات الموجودة في السطر. |
|
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


يسترجع الكلمات الموجودة في السطر.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - الكلمات الموجودة في السطر.

### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


يضبط الكلمات الموجودة في السطر.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | wordList | java.util.List<com.groupdocs.viewer.results.Word> | الكلمات الموجودة في السطر. |
|

