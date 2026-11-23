---
title: "render_notes 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이 속성은 일부 형식에 대한 노트와 주석의 렌더링을 가능하게 합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/
is_root: false
weight: 2130
---


## render_notes property

이 속성은 일부 형식에 대한 노트와 주석의 렌더링을 가능하게 합니다.

프레젠테이션이나 Microsoft Project 파일과 같은 일부 형식에는 노트가 포함될 수 있습니다. 또한 PDF 파일에는 기본적으로 숨겨져 있으며 마우스 커서를 올려놓을 때만 PDF 뷰어에서 보이는 팝업 주석(풍선 힌트)이 있을 수 있습니다. 기본적으로 GroupDocs.Viewer는 이러한 노트와 주석을 렌더링하지 않습니다(`False`). 이를 위해 이 속성을 `True`로 설정하십시오.

코드 예제는 문서를 참조하십시오.

### Definition:
```python
@property
def render_notes(self):
    ...
@render_notes.setter
def render_notes(self, value):
    ...
```

### 참고
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
