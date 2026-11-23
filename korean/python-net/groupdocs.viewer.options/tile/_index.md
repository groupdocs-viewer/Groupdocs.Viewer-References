---
title: "타일 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "그리기 영역을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/tile/
is_root: false
weight: 310
---


## Tile class

그리기 영역을 나타냅니다.

자세한 내용은 https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#split-a-drawing-into-tiles 문서를 참조하십시오.

Tile 유형은 다음 멤버를 제공합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/tile/__init__/#start_point_x-start_point_y-width-height) | [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/) 클래스의 인스턴스를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [get_end_point_x](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_x/) | 타일이 끝나는 도면의 가장 오른쪽 상단 점의 X 좌표를 반환합니다. |
| [get_end_point_y](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_y/) | 타일이 끝나는 도면의 가장 오른쪽 상단 점의 Y 좌표를 반환합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [height](/viewer/python-net/groupdocs.viewer.options/tile/height/) | 타일의 높이(픽셀 단위). |
| [start_point_x](/viewer/python-net/groupdocs.viewer.options/tile/start_point_x/) | 타일이 시작되는 도면의 가장 왼쪽 하단 점의 X 좌표. |
| [start_point_y](/viewer/python-net/groupdocs.viewer.options/tile/start_point_y/) | 타일이 시작되는 도면의 가장 왼쪽 하단 점의 Y 좌표. |
| [width](/viewer/python-net/groupdocs.viewer.options/tile/width/) | 타일의 너비(픽셀 단위). |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions, Tile

with Viewer("sample.dwg") as viewer:
    view_info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    width = view_info.pages[0].width
    height = view_info.pages[0].height

    columns, rows = 2, 2
    tile_width = width / columns
    tile_height = height / rows

    view_options = HtmlViewOptions.for_embedded_resources(
        "output/drawing_tile_{0}.html"
    )
    for i in range(columns):
        for j in range(rows):
            tile = Tile(i * tile_width, j * tile_height, tile_width, tile_height)
            view_options.cad_options.tiles.append(tile)
```

### 참고
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
