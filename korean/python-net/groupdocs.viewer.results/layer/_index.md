---
title: "Layer 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "CAD 도면에 포함된 레이어를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/layer/
is_root: false
weight: 60
---


## Layer class

CAD 도면에 포함된 레이어를 나타냅니다.

Layer 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/) | 새로운 [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) 클래스 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name) | 새로운 Layer 인스턴스를 초기화합니다. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name-visible) | 새로운 Layer 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#other) | 현재 Layer가 지정된 Layer 객체와 동일한지 확인합니다. |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#obj) | 현재 [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/)가 지정된 객체와 같은지 확인합니다. |
| [equals_layer](/viewer/python-net/groupdocs.viewer.results/layer/equals_layer/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.results/layer/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.results/layer/get_hash_code/) | 현재 Layer 객체의 해시 코드를 반환합니다. |
| [to_string](/viewer/python-net/groupdocs.viewer.results/layer/to_string/) | 현재 객체를 나타내는 문자열을 반환합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [name](/viewer/python-net/groupdocs.viewer.results/layer/name/) | 레이어의 이름. |
| [visible](/viewer/python-net/groupdocs.viewer.results/layer/visible/) | 레이어 가시성 표시기. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("output.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### 참고
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
