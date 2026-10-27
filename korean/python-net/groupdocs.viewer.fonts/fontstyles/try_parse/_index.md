---
title: "try_parse 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "지정된 원시 문자열을 폰트 스타일 이름으로 구문 분석하려고 시도합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/
is_root: false
weight: 1060
---


## try_parse {#style-parsed}

지정된 원시 문자열을 폰트 스타일 이름으로 구문 분석하려고 시도합니다.

```python
def try_parse(cls, style, parsed):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| style | `str` | 글꼴 스타일로 구문 분석되어야 하는 문자열. |
| parsed | `FontStyles` | 성공 시 구문 분석된 글꼴 스타일, 실패 시 `FontStyles.Regular`. |

**Returns:** bool: True if string was successfully parsed as a correct font style; False otherwise.

### 참고
* class [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/)
