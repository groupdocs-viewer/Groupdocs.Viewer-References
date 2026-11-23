---
title: "release_page_stream 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "IPageStreamFactory.createpagestream 메서드가 만든 스트림을 해제합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream/
is_root: false
weight: 1030
---


## release_page_stream {#page_number-page_stream}

`[IPageStreamFactory.create_page_stream](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/)` 메서드에 의해 생성된 스트림을 해제합니다.

```python
def release_page_stream(self, page_number, page_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| page_number | `int` | 페이지 번호. |
| page_stream | `io.RawIOBase` | `IPageStreamFactory.create_page_stream` 메서드가 만든 스트림. |

### 참고
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
