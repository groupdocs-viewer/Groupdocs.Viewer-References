---
title: "for_png_view メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "PNG にレンダリングする際にビュー情報を取得するための ViewInfoOptions クラスのインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/
is_root: false
weight: 1060
---


## for_png_view

PNG にレンダリングする際にビュー情報を取得するための [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) クラスのインスタンスを初期化します。

```python
def for_png_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the `ViewInfoOptions` class.

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# PNG 形式用のビュー情報オプションを作成する
view_info_options_png = ViewInfoOptions.for_png_view()

# ドキュメントを読み込み、PNG 用のビュー情報を取得する
with Viewer("sample.xml") as viewer:
    result_png = viewer.get_view_info(view_info_options_png)
```

## for_png_view {#extract_text}

PNG にレンダリングする際にビュー情報を取得するための ViewInfoOptions クラスのインスタンスを初期化します。

```python
def for_png_view(cls, extract_text):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| extract_text | `bool` | テキスト抽出を有効にします。 |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### 例

```python
from groupdocs.viewer.options import ViewInfoOptions

# テキスト抽出が有効な PNG 形式用のビュー情報オプションを作成する
options = ViewInfoOptions.for_png_view(extractText=True)
```

### 参照
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
