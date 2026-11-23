---
title: "rotate_page 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "페이지에 시계 방향 회전을 적용합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/viewoptions/rotate_page/
is_root: false
weight: 1010
---


## rotate_page {#page_number-rotation}

페이지에 시계 방향 회전을 적용합니다.

자세한 내용은 https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/ 문서를 참조하십시오.

```python
def rotate_page(self, page_number, rotation):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| page_number | `int` | 페이지 번호는 0보다 크게 엄격히 지정되어야 합니다. |
| rotation | `Rotation` | 회전 값. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `page_number` 번호 페이지에 대한 회전이 이미 추가된 경우. |

### 참고
* class [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)
