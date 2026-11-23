---
title: "release_resource_stream メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "IResourceStreamFactory.createresourcestream メソッドで作成されたストリームを解放します。"
type: docs
url: /ja/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/release_resource_stream/
is_root: false
weight: 1050
---


## release_resource_stream {#page_number-resource-resource_stream}

[`IResourceStreamFactory.create_resource_stream`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/) メソッドによって作成されたストリームを解放します。

```python
def release_resource_stream(self, page_number, resource, resource_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| page_number | `int` | ページの番号。 |
| resource | `Resource` | フォント、スタイル、画像、またはグラフィックなどの HTML リソース。 |
| resource_stream | `io.RawIOBase` | `IResourceStreamFactory.create_resource_stream` メソッドで作成されたストリーム。 |

**Returns:** None.

### 参照
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
