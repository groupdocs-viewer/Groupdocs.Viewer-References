---
title: "trace 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "추적 메시지를 기록합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.logging/ilogger/trace/
is_root: false
weight: 1040
---


## trace {#message}

추적 메시지를 기록합니다.

Trace 로그 메시지는 애플리케이션 흐름에 대한 일반적으로 유용한 정보를 제공합니다.

```python
def trace(self, message):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| message | `str` | Trace 메시지. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `message`가 None일 때 발생합니다. |

### 참고
* class [`ILogger`](/viewer/python-net/groupdocs.viewer.logging/ilogger/)
