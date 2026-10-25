---
title: "Line"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "단일 라인을 포함하는 상대적으로 배치된 사각형을 나타냅니다."
type: docs
weight: 18
url: /ko/java/com.groupdocs.viewer.results/line/
---
**All Implemented Interfaces:**
com.groupdocs.viewer.results.TextElement, java.io.Serializable
```
public interface Line extends TextElement<String>, Serializable
```

단일 라인을 포함하는 상대적으로 배치된 사각형을 나타냅니다.


Line 인터페이스는 사각형으로 표시된 선에 접근하고 조작하기 위한 계약을 정의합니다.
GroupDocs.Viewer 구성 요소에서. 라인 텍스트와 같은 정보를 검색하는 메서드를 제공합니다,
위치 및 사각형의 크기.


사용 예시:

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

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWords()](#getWords--) | 라인에 포함된 단어를 검색합니다. |
|
|  | [setWords(List<Word> wordList)](#setWords-java.util.List-com.groupdocs.viewer.results.Word--) | 라인에 포함된 단어를 설정합니다. |
|
### getWords() {#getWords--}
```
public abstract List<Word> getWords()
```


라인에 포함된 단어를 검색합니다.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Word> - 라인에 포함된 단어.

### setWords(List<Word> wordList) {#setWords-java.util.List-com.groupdocs.viewer.results.Word--}
```
public abstract void setWords(List<Word> wordList)
```


라인에 포함된 단어를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | wordList | java.util.List<com.groupdocs.viewer.results.Word> | 라인에 포함된 단어. |
|

