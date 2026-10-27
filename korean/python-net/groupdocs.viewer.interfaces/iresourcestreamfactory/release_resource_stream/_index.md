---
title: "release_resource_stream 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "IResourceStreamFactory.createresourcestream 메서드가 만든 스트림을 해제합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/release_resource_stream/
is_root: false
weight: 1050
---


## release_resource_stream {#page_number-resource-resource_stream}

`[IResourceStreamFactory.create_resource_stream](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/)` 메서드에 의해 생성된 스트림을 해제합니다.

```python
def release_resource_stream(self, page_number, resource, resource_stream):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| page_number | `int` | 페이지 번호. |
| resource | `Resource` | 글꼴, 스타일, 이미지 또는 그래픽과 같은 HTML 리소스. |
| resource_stream | `io.RawIOBase` | `IResourceStreamFactory.create_resource_stream` 메서드가 만든 스트림. |

**Returns:** None.

### 참고
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
