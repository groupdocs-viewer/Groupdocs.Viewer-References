---
title: "page_size 속성"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "출력 페이지의 크기입니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/
is_root: false
weight: 2060
---


## page_size property

출력 페이지의 크기입니다.

기본값은 `PageSize.Unspecified`이며, 이는 페이지 설정(Page Setup)에서 지정된 페이지 크기가 사용된다는 의미입니다.

HTM 및 HTML 파일을 렌더링할 때 기본 페이지 크기는 Letter 792 x 612 포인트로 설정됩니다.

그 결과, 일부 콘텐츠가 페이지 프레임에 맞지 않을 수 있습니다.

`PageSize.A3`와 같이 더 큰 페이지 크기를 설정하여 내용을 맞추세요.

### Definition:
```python
@property
def page_size(self):
    ...
@page_size.setter
def page_size(self, value):
    ...
```

### 참고
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
