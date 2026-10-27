---
title: "create_page_stream メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "出力ページデータを書き込むために使用されるストリームを作成します。"
type: docs
url: /ja/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/
is_root: false
weight: 1010
---


## create_page_stream {#page_number}

出力ページデータを書き込むために使用されるストリームを作成します。

```python
def create_page_stream(self, page_number):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| page_number | `int` | ページの番号。 |

**Returns:** io.RawIOBase: Stream used to write output page data.

### 例

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

### 参照
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
