---
title: "is_embedded 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이 속성은 폰트가 문서에 내장되어 Viewer 인스턴스로 로드되었는지(True) 또는 시스템 폰트인지(False)를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/
is_root: false
weight: 2040
---


## is_embedded property

이 속성은 글꼴이 문서에 포함되어 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 인스턴스에 로드되었는지(`True`), 혹은 시스템 글꼴인지(`False`)를 나타냅니다.

스프레드시트 문서는 내장 폰트를 보유할 수 없으므로 이 속성은 항상 `False`를 반환합니다.

### Definition:
```python
@property
def is_embedded(self):
    ...
```

### 참고
* class [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/)
