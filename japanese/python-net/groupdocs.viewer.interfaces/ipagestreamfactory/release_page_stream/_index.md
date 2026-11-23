---
title: "release_page_stream メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "IPageStreamFactory.createpagestream メソッドで作成されたストリームを解放します。"
type: docs
url: /ja/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/release_page_stream/
is_root: false
weight: 1030
---


## release_page_stream {#page_number-page_stream}

[`IPageStreamFactory.create_page_stream`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/) メソッドによって作成されたストリームを解放します。

```python
def release_page_stream(self, page_number, page_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| page_number | `int` | ページの番号。 |
| page_stream | `io.RawIOBase` | `IPageStreamFactory.create_page_stream` メソッドで作成されたストリーム。 |

### 参照
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
