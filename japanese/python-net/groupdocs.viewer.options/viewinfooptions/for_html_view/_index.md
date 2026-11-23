---
title: "for_html_view メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "HTML にレンダリングする際にビュー情報を取得するための ViewInfoOptions インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/
is_root: false
weight: 1010
---


## for_html_view

HTML にレンダリングする際にビュー情報を取得するための ViewInfoOptions インスタンスを初期化します。

```python
def for_html_view(cls):
    ...
```

**Returns:** ViewInfoOptions: A new ViewInfoOptions instance.

### 例

```python
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import ViewInfoOptions

    # HTML 形式（単一ページ）用のビュー情報オプションを作成する
    options = ViewInfoOptions.for_html_view(True)

    # ドキュメントを読み込み、ビュー情報を取得する
    with Viewer("sample.xml") as viewer:
        info = viewer.get_view_info(options)
    ```

## for_html_view {#render_single_page}

HTML にレンダリングする際にビュー情報を取得するための ViewInfoOptions インスタンスを初期化します。

```python
def for_html_view(cls, render_single_page):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| render_single_page | `bool` | HTML コンテンツを単一ページにレンダリングできるようにします。 |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# 単一ページの HTML 用ビュー情報を取得する
options = ViewInfoOptions.for_html_view(True)

with Viewer("sample.xml") as viewer:
    info = viewer.get_view_info(options)
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### 参照
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
