---
title: "serialize_to_css メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "フォント情報を @font-face の at-rule としてシリアライズし、指定されたテキストライターに書き込みます。"
type: docs
url: /ja/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/
is_root: false
weight: 1010
---


## serialize_to_css {#output}

フォント情報を @font-face の at-rule としてシリアライズし、指定されたテキストライターに書き込みます。

```python
def serialize_to_css(self, output):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| output | `System.IO.TextWriter` | シリアライズされたテキストデータを書き込むべき、ファイルライクオブジェクト（例: `io.TextIOBase`）です。 |

**Returns:** None.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `output` が `None` の場合。 |

### 参照
* class [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/)
