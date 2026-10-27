---
title: "for_pdf_view 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "PDF로 렌더링할 때 보기 정보를 검색하기 위해 ViewInfoOptions 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/viewinfooptions/for_pdf_view/
is_root: false
weight: 1050
---


## for_pdf_view

PDF로 렌더링할 때 보기 정보를 검색하기 위해 ViewInfoOptions 인스턴스를 초기화합니다.

```python
def for_pdf_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### 예시

```python
    from groupdocs.viewer.options import ViewInfoOptions

    # PDF 형식용 보기 정보 옵션 만들기
    view_info_options_pdf = ViewInfoOptions.for_pdf_view()
    ```

### 참고
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
