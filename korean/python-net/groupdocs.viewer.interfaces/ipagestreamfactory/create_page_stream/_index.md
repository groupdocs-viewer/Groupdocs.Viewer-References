---
title: "create_page_stream 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "출력 페이지 데이터를 쓰는 데 사용되는 스트림을 생성합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/
is_root: false
weight: 1010
---


## create_page_stream {#page_number}

출력 페이지 데이터를 쓰는 데 사용되는 스트림을 생성합니다.

```python
def create_page_stream(self, page_number):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| page_number | `int` | 페이지 번호. |

**Returns:** io.RawIOBase: Stream used to write output page data.

### 예시

```python
    import io
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import PngViewOptions

    page_buffers = {}

    def create_page_stream(page_number):
        buf = io.BytesIO()
        page_buffers[page_number] = buf
        return buf

    with Viewer("input.docx") as viewer:
        viewer.view(PngViewOptions(create_page_stream))
    ```

### 참고
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
