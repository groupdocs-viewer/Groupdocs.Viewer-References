---
title: "create_resource_stream メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "出力 HTML リソースデータを書き込むために使用されるストリームを作成します。"
type: docs
url: /ja/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/create_resource_stream/
is_root: false
weight: 1010
---


## create_resource_stream {#page_number-resource}

出力 HTML リソースデータを書き込むために使用されるストリームを作成します。

```python
def create_resource_stream(self, page_number, resource):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| page_number | `int` | ページの番号。 |
| resource | `Resource` | フォント、スタイル、画像、またはグラフィックなどの HTML リソース。 |

**Returns:** io.RawIOBase: Stream used to write output resource data.

### 例

```python
from groupdocs.viewer import Viewer

viewer = Viewer()
factory = viewer.resource_stream_factory

# ページ 1 の CSS リソース用にストリームを作成します
stream = factory.create_resource_stream(pageNumber=1, resource="style.css")
with stream:
    stream.write(b"body { font-family: Arial; }")
```

### 参照
* class [`IResourceStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/iresourcestreamfactory/)
