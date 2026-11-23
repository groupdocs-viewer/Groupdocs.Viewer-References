---
title: "set_license 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "현재 프로세스에 라이선스를 적용합니다."
type: docs
url: /ko/python-net/groupdocs.viewer/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

현재 프로세스에 라이선스를 적용합니다.

```python
def set_license(self, license_source):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| license_source |  | ``.lic`` 파일에 대한 문자열 경로나 라이선스 바이트를 반환하는 읽을 수 있는 파일과 같은 객체 중 하나입니다. 파일과 같은 객체 입력은 브리지에 전달되기 전에 임시 파일에 기록됩니다. |

| 예외 발생 | 설명 |
| :- | :- |
| `TypeError` | ``license_source``가 문자열 경로나 읽을 수 있는 파일과 같은 객체가 아닌 경우. |

### 참고
* class [`License`](/viewer/python-net/groupdocs.viewer/license/)
