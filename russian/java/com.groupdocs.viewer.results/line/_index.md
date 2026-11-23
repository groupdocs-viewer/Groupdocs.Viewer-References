---
title: "Line"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Представляет относительно позиционированный прямоугольник, содержащий одну строку."
type: docs
weight: 18
url: /ru/java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

Представляет относительно позиционированный прямоугольник, содержащий одну строку.


Интерфейс Line определяет контракт для доступа и изменения линии, представленной прямоугольником
в компоненте GroupDocs.Viewer. Он предоставляет методы для получения информации, такой как текст строки,
позиция и размер прямоугольника.


Пример использования:

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

## Методы

| Метод | Описание |
| --- | --- |
|  | [getWords()](#getWords--) | Получает слова, содержащиеся в строке. |
|
|  | [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | Устанавливает слова, содержащиеся в строке. |
|
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


Получает слова, содержащиеся в строке.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - слова, содержащиеся в строке.

### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


Устанавливает слова, содержащиеся в строке.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | wordList | java.util.List<com.groupdocs.viewer.results.Word> | слова, содержащиеся в строке. |
|

