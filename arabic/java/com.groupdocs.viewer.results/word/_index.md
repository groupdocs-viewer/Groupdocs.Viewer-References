---
title: "Word"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يمثل مستطيلًا موضعًا نسبيًا يحتوي على كلمة واحدة."
type: docs
weight: 28
url: /ar/java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

يمثل مستطيلًا موضعًا نسبيًا يحتوي على كلمة واحدة.


واجهة Word تمثل كلمة داخل مستطيل موضعه نسبيًا في مكوّن GroupDocs.Viewer.
تُوسّع واجهة TextElement وتوفر طرقًا إضافية للوصول إلى محتوى الكلمة ومعالجته.


مثال على الاستخدام:

````

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List words = viewInfo.getPages().get(0).getLines().get(0).getWords();
     for (Word word : words) {
         // Use the word object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is WordImpl.*

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getCharacters()](#getCharacters--) | يسترجع الأحرف التي تحتويها الكلمة. |
|
|  | [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | يضبط الأحرف التي تحتويها الكلمة. |
|
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


يسترجع الأحرف التي تحتويها الكلمة.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - قائمة الأحرف.

### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


يضبط الأحرف التي تحتويها الكلمة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الأحرف | java.util.List<com.groupdocs.viewer.results.Character> | قائمة الأحرف التي سيتم ضبطها. |
|

