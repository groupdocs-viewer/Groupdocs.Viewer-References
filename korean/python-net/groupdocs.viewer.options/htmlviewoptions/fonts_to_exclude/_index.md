---
title: "fonts_to_exclude 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "HTML 문서에서 제외할 폰트 이름 목록입니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/htmlviewoptions/fonts_to_exclude/
is_root: false
weight: 2020
---


## fonts_to_exclude property

HTML 문서에서 제외할 폰트 이름 목록입니다.

HTML 문서에 추가되는 글꼴은 출력 뷰의 안정성을 향상시키지만, 동시에 렌더링 결과의 크기를 증가시킵니다. 이 옵션을 사용하면 안정성과 출력 크기 사이의 균형을 맞출 수 있습니다. 대부분의 시스템에 설치되어 있고 널리 사용되는 글꼴 이름을 포함하십시오.

참고로, 이 속성은 [`HtmlViewOptions.ExcludeFonts`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/) 옵션이 비활성화된 경우에만 활성화됩니다.

자세한 내용 및 코드 예제는 문서를 참조하십시오.

### Definition:
```python
@property
def fonts_to_exclude(self):
    ...
@fonts_to_exclude.setter
def fonts_to_exclude(self, value):
    ...
```

### 참고
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
