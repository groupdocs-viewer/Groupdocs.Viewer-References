---
title: "Word"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يمثل مستطيلًا موضعًا نسبيًا يحتوي على كلمة واحدة."
type: docs
weight: 26
url: /ar/nodejs-java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

يمثل مستطيلًا موضعًا نسبيًا يحتوي على كلمة واحدة.

واجهة Word تمثّل كلمة داخل مستطيل موضعه نسبيًا في مكوّن GroupDocs.Viewer. تمتد من واجهة TextElement وتوفر طرقًا إضافية للوصول إلى محتوى الكلمة ومعالجته.

مثال على الاستخدام:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     PdfViewInfo viewInfo = (PdfViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List words = viewInfo.getPages().get(0).getLines().get(0).getWords();
     for (Word word : words) {
         // Use the word object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is WordImpl.*
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCharacters()](#getCharacters--) | يسترجع الأحرف الموجودة في الكلمة. |
| [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | يضبط الأحرف الموجودة في الكلمة. |
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


يسترجع الأحرف الموجودة في الكلمة.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - قائمة الأحرف.
### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


يضبط الأحرف الموجودة في الكلمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| حروف | java.util.List<com.groupdocs.viewer.results.Character> | قائمة الأحرف التي سيتم تعيينها. |

