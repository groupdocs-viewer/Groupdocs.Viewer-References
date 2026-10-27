---
title: "for_jpg_view メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "JPG にレンダリングする際のビュー情報を取得するために ViewInfoOptions インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/
is_root: false
weight: 1030
---


## for_jpg_view

JPG にレンダリングする際にビュー情報を取得するための [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) インスタンスを初期化します。

```python
def for_jpg_view(cls):
    ...
```

**Returns:** A new `ViewInfoOptions` instance.

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

def get_jpg_view_info():
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_jpg_view())
        print("Document type:", info.file_type)
        print("Pages count:", len(info.pages))

if __name__ == "__main__":
    get_jpg_view_info()
```

## for_jpg_view {#extract_text}

JPG にレンダリングする際にビュー情報を取得するための ViewInfoOptions インスタンスを初期化します。

```python
def for_jpg_view(cls, extract_text):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| extract_text | `bool` | テキスト抽出を有効にします。 |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### 参照
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
