---
title: "Word"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "단일 단어를 포함하는 상대적으로 배치된 사각형을 나타냅니다."
type: docs
weight: 28
url: /ko/java/com.groupdocs.viewer.results/word/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Word extends TextElement<String>, Serializable
```

단일 단어를 포함하는 상대적으로 배치된 사각형을 나타냅니다.


Word 인터페이스는 GroupDocs.Viewer 구성 요소에서 상대적으로 배치된 사각형 내의 단어를 나타냅니다.
TextElement 인터페이스를 확장하고 단어 내용을 액세스하고 조작하기 위한 추가 메서드를 제공합니다.


사용 예시:

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

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getCharacters()](#getCharacters--) | 단어에 포함된 문자를 검색합니다. |
|
|  | [setCharacters(List<Character> characters)](#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--) | 단어에 포함된 문자를 설정합니다. |
|
### getCharacters() {#getCharacters--}
```
public abstract List<Character> getCharacters()
```


단어에 포함된 문자를 검색합니다.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Character> - 문자 목록.

### setCharacters(List<Character> characters) {#setCharacters-java.util.List-com.groupdocs.viewer.results.Character--}
```
public abstract void setCharacters(List<Character> characters)
```


단어에 포함된 문자를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 문자 | java.util.List<com.groupdocs.viewer.results.Character> | 설정할 문자 목록. |
|

