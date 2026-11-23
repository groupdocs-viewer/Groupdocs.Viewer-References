---
title: "vertical_resolution 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "생성된 이미지의 세로 해상도(인치당 도트 수)입니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/
is_root: false
weight: 2160
---


## vertical_resolution property

생성된 이미지의 세로 해상도(인치당 도트 수). 이 옵션은 스프레드시트를 PNG 또는 JPEG 형식으로 렌더링할 때만 사용됩니다.

기본값은 96 DPI입니다. 최소값은 72 DPI이며, 최대값은 600 DPI입니다. 사용자가 지정한 값이 이 범위를 벗어나면 가장 가까운 경계값이 적용됩니다.

### Definition:
```python
@property
def vertical_resolution(self):
    ...
@vertical_resolution.setter
def vertical_resolution(self, value):
    ...
```

### 참고
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
