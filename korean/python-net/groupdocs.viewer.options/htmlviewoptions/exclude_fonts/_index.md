---
title: "exclude_fonts 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이 속성은 HTML 문서에 폰트를 추가하는 것을 비활성화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/
is_root: false
weight: 2010
---


## exclude_fonts property

이 속성은 HTML 문서에 폰트를 추가하는 것을 비활성화합니다.

기본적으로 GroupDocs.Viewer는 문서에 사용된 글꼴을 HTML 마크업에 포함시키며, 이 속성은 `False` 값을 가집니다. 글꼴 포함을 방지하려면 이 속성을 `True` 로 설정하십시오.

자세한 내용과 코드 예제는 문서를 참조하십시오.

### Definition:
```python
@property
def exclude_fonts(self):
    ...
@exclude_fonts.setter
def exclude_fonts(self, value):
    ...
```

### 참고
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
