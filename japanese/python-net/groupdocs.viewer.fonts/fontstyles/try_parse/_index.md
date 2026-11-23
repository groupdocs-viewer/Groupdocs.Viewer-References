---
title: "try_parse メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "指定された生文字列をフォントスタイル名として解析しようとします。"
type: docs
url: /ja/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/
is_root: false
weight: 1060
---


## try_parse {#style-parsed}

指定された生文字列をフォントスタイル名として解析しようとします。

```python
def try_parse(cls, style, parsed):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| style | `str` | フォントスタイルとして解析すべき文字列です。 |
| parsed | `FontStyles` | 成功した場合は解析されたフォントスタイル、失敗した場合は `FontStyles.Regular` が返されます。 |

**Returns:** bool: True if string was successfully parsed as a correct font style; False otherwise.

### 参照
* class [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/)
