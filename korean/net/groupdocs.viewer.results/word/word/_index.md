---
title: Word
second_title: .NET API 참조용 GroupDocs.Viewer
description: 의 새 인스턴스를 초기화합니다.Wordgroupdocs.viewer.results/word 클래스.
type: docs
weight: 10
url: /ko/net/groupdocs.viewer.results/word/word/
---
## Word() {#constructor}

의 새 인스턴스를 초기화합니다.[`Word`](../../word) 클래스.

```csharp
public Word()
```

### 또한보십시오

* class [Word](../../word)
* 네임스페이스 [GroupDocs.Viewer.Results](../../word)
* 집회 [GroupDocs.Viewer](../../../)

---

## Word(string, double, double, double, double, List&lt;Character&gt;) {#constructor_1}

의 새 인스턴스를 초기화합니다.[`Word`](../../word) 클래스.

```csharp
public Word(string word, double x, double y, double width, double height, 
    List<Character> characters)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| word | String | 단어. |
| x | Double | 단어가 포함된 사각형이 시작되는 페이지 레이아웃에서 가장 높은 왼쪽 지점의 X 좌표입니다. |
| y | Double | 단어가 포함된 사각형이 시작되는 페이지 레이아웃에서 가장 높은 왼쪽 지점의 Y 좌표입니다. |
| width | Double | 단어가 포함된 사각형의 너비입니다. |
| height | Double | 단어가 포함된 사각형의 높이입니다. |
| characters | List`1 | 단어에 포함된 문자입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 언제 던져*word* null이거나 비어 있습니다. |
| ArgumentNullException | 언제 던져*characters* null입니다. |

### 또한보십시오

* class [Character](../../character)
* class [Word](../../word)
* 네임스페이스 [GroupDocs.Viewer.Results](../../word)
* 집회 [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->