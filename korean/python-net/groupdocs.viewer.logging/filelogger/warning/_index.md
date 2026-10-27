---
title: "warning 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "콘솔에 경고 메시지를 기록합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.logging/filelogger/warning/
is_root: false
weight: 1070
---


## warning {#message}

콘솔에 경고 메시지를 기록합니다.

Warning 로그 메시지는 애플리케이션 흐름에서 예상치 못한 및 복구 가능한 이벤트에 대한 정보를 제공합니다.

```python
def warning(self, message):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| message | `str` | 경고 메시지. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `message`가 None일 때 발생합니다. |

### 참고
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
