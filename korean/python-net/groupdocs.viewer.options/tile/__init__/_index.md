---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Tile 클래스의 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/tile/__init__/
is_root: false
weight: 10
---


## __init__ {#start_point_x-start_point_y-width-height}

[`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/) 클래스의 인스턴스를 초기화합니다.

자세한 내용은 문서를 참조하십시오.

```python
def __init__(self, start_point_x, start_point_y, width, height):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| start_point_x | `int` | 타일이 시작되는 도면의 가장 왼쪽 하단 점의 X 좌표. |
| start_point_y | `int` | 타일이 시작되는 도면의 가장 왼쪽 하단 점의 Y 좌표. |
| width | `int` | 타일의 너비(픽셀 단위). |
| height | `int` | 타일의 높이(픽셀 단위). |

### 예시

```python
from groupdocs.viewer.options import Tile

# 타일 매개변수를 정의합니다.
start_x = 0
start_y = 0
tile_width = 500
tile_height = 400

# 그림의 일부를 나타내는 타일을 생성합니다.
tile = Tile(start_x, start_y, tile_width, tile_height)
```

### 참고
* class [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/)
