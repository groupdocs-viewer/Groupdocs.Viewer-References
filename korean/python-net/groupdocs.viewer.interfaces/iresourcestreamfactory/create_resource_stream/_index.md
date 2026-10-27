---
title: "create_resource_stream 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "출력 HTML 리소스 데이터를 쓰는 데 사용되는 스트림을 생성합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/
is_root: false
weight: 1010
---


## create_resource_stream {#page_number-resource}

출력 HTML 리소스 데이터를 쓰는 데 사용되는 스트림을 생성합니다.

```python
def create_resource_stream(self, page_number, resource):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| page_number | `int` | 페이지 번호. |
| resource | `Resource` | 글꼴, 스타일, 이미지 또는 그래픽과 같은 HTML 리소스. |

**Returns:** io.RawIOBase: Stream used to write output resource data.

### 예시

```python
from groupdocs.viewer import Viewer

viewer = Viewer()
factory = viewer.resource_stream_factory

# 페이지 1의 CSS 리소스를 위한 스트림을 생성합니다.
stream = factory.create_resource_stream(pageNumber=1, resource="style.css")
with stream:
    stream.write(b"body { font-family: Arial; }")
```

### 참고
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
