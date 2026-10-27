---
title: "remove_unused_objects 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이 속성은 PDF 파일에서 사용되지 않는(고아) 객체를 제거합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/
is_root: false
weight: 2090
---


## remove_unused_objects property

이 속성은 PDF 파일에서 사용되지 않는(고아) 객체를 제거합니다.

이러한 객체는 PDF 문서에 배치되지만 어떤 페이지의 리소스 사전에서도 참조되지 않아 전혀 사용되지 않습니다. 이 속성을 활성화(`True`)하면 출력 PDF 문서 크기가 감소합니다. 기본값은 비활성화(`False`)입니다.

### Definition:
```python
@property
def remove_unused_objects(self):
    ...
@remove_unused_objects.setter
def remove_unused_objects(self, value):
    ...
```

### 참고
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
