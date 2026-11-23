---
title: "serialize_to_css 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "글꼴 정보를 @font-face 규칙으로 직렬화하고 지정된 텍스트 라이터에 씁니다."
type: docs
url: /ko/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/
is_root: false
weight: 1010
---


## serialize_to_css {#output}

글꼴 정보를 @font-face 규칙으로 직렬화하고 지정된 텍스트 라이터에 씁니다.

```python
def serialize_to_css(self, output):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| output | `System.IO.TextWriter` | 직렬화된 텍스트 데이터를 기록해야 하는 파일과 유사한 객체(`io.TextIOBase` 등)입니다. |

**Returns:** None.

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `output`이 None인 경우. |

### 참고
* class [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/)
