---
title: "error 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "콘솔에 오류 메시지를 기록합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.logging/filelogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

콘솔에 오류 메시지를 기록합니다. 오류 로그 메시지는 애플리케이션 흐름에서 복구할 수 없는 이벤트에 대한 정보를 제공합니다.

```python
def error(self, message, exception):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| message | `str` | Error 메시지. |
| exception | `Exception` | 예외. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `exception`이 None일 때. |

### 참고
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
