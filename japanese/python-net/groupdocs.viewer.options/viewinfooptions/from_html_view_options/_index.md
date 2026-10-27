---
title: "from_html_view_options メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "HtmlViewOptions オブジェクトに基づいて ViewInfoOptions クラスのインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/
is_root: false
weight: 1080
---


## from_html_view_options {#options}

HtmlViewOptions オブジェクトに基づいて ViewInfoOptions クラスのインスタンスを初期化します。

```python
def from_html_view_options(cls, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | `HtmlViewOptions` | HTML ビュー オプション。 |

**Returns:** A new ViewInfoOptions instance.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `options` が None の場合。 |

### 例

```python
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions

html_opts = HtmlViewOptions()
view_info_opts = ViewInfoOptions.from_html_view_options(html_opts)
```

### 参照
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
