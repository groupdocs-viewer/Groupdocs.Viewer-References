---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "스프레드시트 문서를 HTML로 렌더링할 때 텍스트 오버플로우 모드를 정의합니다."
type: docs
weight: 46
url: /ko/java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

스프레드시트 문서를 HTML로 렌더링할 때 텍스트 오버플로우 모드를 정의합니다.


TextOverflowMode 열거형은 GroupDocs.Viewer 구성 요소에서 텍스트 오버플로를 처리하는 다양한 모드를 나타냅니다.
이 열거형은 텍스트가 사용 가능한 범위를 초과했을 때 표시 방식을 제어하는 데 사용할 수 있는 미리 정의된 옵션 집합을 제공합니다.
스프레드시트 문서를 HTML로 렌더링하는 동안 셀 내 공간을 처리합니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow)을(를) 참조하십시오.


사용 예시:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 필드

| 필드 | 설명 |
| --- | --- |
|  | [OVERLAY](#OVERLAY) | 비어 있지 않은 경우에도 다음 셀을 겹칩니다. |
|
|  | [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | 셀을 비어 있는 경우에만 다음 셀을 겹칩니다. |
|
|  | [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | 텍스트에 맞게 열을 확장합니다. |
|
|  | [HIDE_TEXT](#HIDE-TEXT) | 오버플로 텍스트를 숨깁니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


비어 있지 않은 경우에도 다음 셀을 겹칩니다.
이 모드는 셀 내용에 관계없이 텍스트가 인접 셀로 오버플로하도록 허용합니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow)을(를) 참조하십시오.


### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


셀을 비어 있는 경우에만 다음 셀을 겹칩니다.
이 모드는 해당 셀이 비어 있는 경우에만 텍스트가 인접 셀로 오버플로하도록 허용합니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow)을(를) 참조하십시오.


### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


텍스트에 맞게 열을 확장합니다.
이 모드는 오버플로 텍스트를 수용하도록 열 너비를 자동으로 조정합니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow)을(를) 참조하십시오.


### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


오버플로 텍스트를 숨깁니다.
이 모드는 오버플로 텍스트를 숨겨 표시되지 않도록 합니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow)을(를) 참조하십시오.


### values() {#values--}
```
public static TextOverflowMode[] values()
```




**Returns:**
com.groupdocs.viewer.options.TextOverflowMode[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TextOverflowMode valueOf(String name)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode)
