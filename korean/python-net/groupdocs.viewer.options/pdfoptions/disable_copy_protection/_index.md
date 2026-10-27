---
title: "disable_copy_protection 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이 속성은 HTML로 렌더링할 때 콘텐츠 복사 방지를 비활성화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/
is_root: false
weight: 2020
---


## disable_copy_protection property

이 속성은 HTML로 렌더링할 때 콘텐츠 복사 방지를 비활성화합니다.

텍스트와 이미지를 HTML로 복사하는 것을 방지하는 보호가 적용된 PDF 파일을 렌더링할 때 GroupDocs.Viewer는 HTML BODY 태그에 `inert` HTML 속성을 추가합니다. 기본값은 `False`이며, 이는 PDF 문서가 보호된 경우에만 `inert` 속성이 추가된다는 의미입니다.

코드 예제는 문서를 참조하십시오.

### Definition:
```python
@property
def disable_copy_protection(self):
    ...
@disable_copy_protection.setter
def disable_copy_protection(self, value):
    ...
```

### 참고
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
