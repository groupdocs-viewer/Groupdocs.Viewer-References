---
title: "release_file_stream メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "IFileStreamFactory.createfilestream メソッドで作成されたストリームを解放します。"
type: docs
url: /ja/python-net/groupdocs.viewer.interfaces/ifilestreamfactory/release_file_stream/
is_root: false
weight: 1020
---


## release_file_stream {#file_stream}

[`IFileStreamFactory.create_file_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ifilestreamfactory/create_file_stream/) メソッドによって作成されたストリームを解放します。

```python
def release_file_stream(self, file_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_stream | `io.RawIOBase` | `IFileStreamFactory.create_file_stream` メソッドで作成されたストリーム。 |

**Returns:** None.

### 参照
* class [`IFileStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ifilestreamfactory/)
