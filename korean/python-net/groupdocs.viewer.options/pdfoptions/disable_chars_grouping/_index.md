---
title: "disable_chars_grouping 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이 속성은 페이지 렌더링 중 정밀한 기호 위치 지정을 위해 기호 그룹화를 비활성화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/
is_root: false
weight: 2010
---


## disable_chars_grouping property

이 속성은 페이지 렌더링 중 정밀한 기호 위치 지정을 위해 기호 그룹화를 비활성화합니다.

PDF 파일을 변환할 때 GroupDocs.Viewer는 렌더링 성능 향상을 위해 개별 문자를 단어로 그룹화합니다. 문서에 상형문자나 특수 기호가 포함된 경우 보다 정밀한 레이아웃을 위해 문자 그룹화를 금지하고 싶을 수 있습니다. 기본값은 False입니다.

코드 예제는 문서를 참조하십시오.

### Definition:
```python
@property
def disable_chars_grouping(self):
    ...
@disable_chars_grouping.setter
def disable_chars_grouping(self, value):
    ...
```

### 참고
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
