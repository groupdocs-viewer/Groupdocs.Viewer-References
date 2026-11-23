---
title: "remove_comments 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이 속성을 True로 설정하면 주석 렌더링을 비활성화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/
is_root: false
weight: 2100
---


## remove_comments property

속성을 True로 설정하면 주석 렌더링이 비활성화됩니다. 기본값은 False이며, 따라서 모든 주석이 표시됩니다.

PDF 및 WordProcessing과 같은 일부 문서 형식에는 주석이 포함될 수 있습니다. 기본적으로 GroupDocs.Viewer는 주석을 렌더링합니다. 이 옵션을 True로 설정하면 결과 문서에서 주석이 제외될 수 있습니다.

이 옵션은 오래된 `RenderComments` 속성을 대체합니다.

### Definition:
```python
@property
def remove_comments(self):
    ...
@remove_comments.setter
def remove_comments(self, value):
    ...
```

### 참고
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
