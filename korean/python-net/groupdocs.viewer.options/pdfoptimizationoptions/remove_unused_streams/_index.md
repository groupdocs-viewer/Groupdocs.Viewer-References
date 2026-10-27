---
title: "remove_unused_streams 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이 속성은 페이지 리소스 사전에 참조되지만 페이지 내용에서는 사용되지 않은 PDF 파일의 사용되지 않은(고아) 스트림을 제거합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/
is_root: false
weight: 2100
---


## remove_unused_streams property

이 속성은 페이지 리소스 사전에서 참조되지만 페이지 내용에서는 사용되지 않은 PDF 파일의 사용되지 않는(고아) 스트림을 제거합니다. 기본적으로 비활성화(`False`)되어 있으며, `True`로 설정하면 출력 PDF 크기가 감소합니다.

### Definition:
```python
@property
def remove_unused_streams(self):
    ...
@remove_unused_streams.setter
def remove_unused_streams(self, value):
    ...
```

### 참고
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
