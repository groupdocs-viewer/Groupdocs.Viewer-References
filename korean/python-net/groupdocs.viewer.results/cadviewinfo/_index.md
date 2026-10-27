---
title: "CadViewInfo 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "CAD 도면에 대한 보기 정보를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.viewer.results/cadviewinfo/
is_root: false
weight: 30
---


## CadViewInfo class

CAD 도면에 대한 보기 정보를 나타냅니다.

CadViewInfo 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/__init__/#file_type-pages-layers-layouts) | 새 CadViewInfo 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | 현재 객체를 나타내는 문자열을 반환합니다. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)에서 상속됨) |

### 속성
| 속성 | 설명 |
| :- | :- |
| [layers](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layers/) | CAD 도면에 포함된 레이어 목록입니다. |
| [layouts](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layouts/) | CAD 도면에 포함된 레이아웃 목록입니다. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | 파일의 유형입니다. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)에서 상속됨) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | 볼 페이지 목록입니다. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)에서 상속됨) |

### 예시

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import CadViewInfo

def get_cad_info():
    with Viewer("sample.dwg") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        cad_info = cast(CadViewInfo, info)

        print("File type:", cad_info.file_type)
        print("Pages count:", len(cad_info.pages))
        print("Layers:")
        for layer in cad_info.layers:
            print(f"  {layer.name} (visible={layer.visible})")
        print("Layouts:")
        for layout in cad_info.layouts:
            print(f"  {layout.name} ({layout.width}x{layout.height})")

if __name__ == "__main__":
    get_cad_info()
```

### Guides
`CadViewInfo`를 사용하는 작업 가이드:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### 참고
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
