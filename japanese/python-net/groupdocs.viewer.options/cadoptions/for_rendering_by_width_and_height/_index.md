---
title: "for_rendering_by_width_and_height メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "幅と高さでレンダリングするための CadOptions クラスのインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/
is_root: false
weight: 1040
---


## for_rendering_by_width_and_height {#width-height}

幅と高さでレンダリングするための CadOptions クラスのインスタンスを初期化します。

コード例については、ドキュメントをご覧ください。

```python
def for_rendering_by_width_and_height(cls, width, height):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| width | `int` | 出力結果の幅（ピクセル単位）。 |
| height | `int` | 出力結果の高さ（ピクセル単位）です。 |

**Returns:** CadOptions: New instance of CadOptions class for rendering by width and height.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `height` が 0 以下の場合。 |

### 参照
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
