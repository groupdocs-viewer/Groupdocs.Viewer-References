---
title: "Layer"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "CAD 도면에 포함된 레이어를 나타냅니다."
type: docs
weight: 16
url: /ko/nodejs-java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

CAD 도면에 포함된 레이어를 나타냅니다.

Layer 인터페이스는 GroupDocs.Viewer 구성 요소의 CAD 도면 내 레이어에 접근하고 조작하기 위한 계약을 정의합니다. 레이어 이름, 가시성 및 기타 속성과 같은 정보를 검색하는 메서드를 제공합니다.

예시 사용법:

```

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layers = viewInfo.getLayers();
     for (Layer layer : layers) {
         // Use the layer object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LayerImpl.*
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getName()](#getName--) | 레이어의 이름을 검색합니다. |
| [setName(String name)](#setName-java.lang.String-) | 레이어의 이름을 설정합니다. |
| [isVisible()](#isVisible--) | 레이어의 가시성을 확인합니다. |
| [setVisible(boolean isVisible)](#setVisible-boolean-) | 레이어의 가시성을 설정합니다. |
| [equals(Object other)](#equals-java.lang.Object-) | 이 객체가 제공된 객체와 같은지 확인합니다. |
### getName() {#getName--}
```
public abstract String getName()
```


레이어의 이름을 검색합니다.

**Note:** Layer names are case sensitive.

**Returns:**
java.lang.String - 레이어의 이름.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


레이어의 이름을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 레이어의 새 이름. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


레이어의 가시성을 확인합니다.

꺼져 있거나 고정된 CAD 도면 레이어는 보이지 않습니다. 보이지 않는 레이어를 렌더링하려면 [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions\#setLayers-List-) 옵션을 사용하십시오.

**Returns:**
boolean - 레이어가 보이면 true, 그렇지 않으면 false.
### setVisible(boolean isVisible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean isVisible)
```


레이어의 가시성을 설정합니다.

true이면 레이어가 보이며, false이면 레이어가 숨겨집니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| isVisible | boolean | 레이어를 표시할지 여부. |

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


이 객체가 제공된 객체와 같은지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 기타 | java.lang.Object | 비교할 객체. |

**Returns:**
boolean - 객체가 동일하면 true, 그렇지 않으면 false.
