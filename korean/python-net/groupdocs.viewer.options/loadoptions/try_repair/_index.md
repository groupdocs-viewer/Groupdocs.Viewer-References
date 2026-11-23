---
title: "try_repair 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이 속성은 GroupDocs.Viewer가 PDF 문서의 구조적 손상을 복구하려고 시도하도록 합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/loadoptions/try_repair/
is_root: false
weight: 2070
---


## try_repair property

이 속성은 GroupDocs.Viewer가 PDF 문서의 구조적 손상을 복구하려고 시도하도록 활성화합니다. 기본값은 False입니다.

이 기능은 PDF 문서의 다음 문제들을 해결합니다:

- Broken references within the document (incorrect object offsets in the Cross-reference list).
- Missing critical elements like root object, page object, or page content.
- Circular references (Form X-object referencing itself).

### Definition:
```python
@property
def try_repair(self):
    ...
@try_repair.setter
def try_repair(self, value):
    ...
```

### 참고
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
