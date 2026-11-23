---
title: "Word"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Представляет относительно позиционированный прямоугольник, содержащий одно слово."
type: docs
weight: 28
url: /ru/java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

Представляет относительно позиционированный прямоугольник, содержащий одно слово.


Интерфейс Word представляет слово внутри относительно позиционированного прямоугольника в компоненте GroupDocs.Viewer.
Он наследует интерфейс TextElement и предоставляет дополнительные методы для доступа и изменения содержимого слова.


Пример использования:

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

## Методы

| Метод | Описание |
| --- | --- |
|  | [getCharacters()](#getCharacters--) | Получает символы, содержащиеся в слове. |
|
|  | [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | Устанавливает символы, содержащиеся в слове. |
|
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


Получает символы, содержащиеся в слове.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - список символов.

### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


Устанавливает символы, содержащиеся в слове.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | символы | java.util.List<com.groupdocs.viewer.results.Character> | список символов для установки. |
|

