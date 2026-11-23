---
title: "set_font_sources メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ドキュメントをレンダリングする際に TrueType フォントを検索するソースを設定します。"
type: docs
url: /ja/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/
is_root: false
weight: 1020
---


## set_font_sources {#font_sources}

ドキュメントをレンダリングする際に TrueType フォントを検索するソースを設定します。

このメソッドは、個々の[`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/)オブジェクト、これらのリスト、またはその両方の混合の任意の組み合わせを受け入れます。すべての入力は適用される前に単一のリストにフラット化されます。文字列パスはそのまま渡され、文字に分割されません。

```python
def set_font_sources(cls, font_sources):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| font_sources | `list[IFontSource]` | フォント ソースです。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `font_sources` が None のとき。 |

### 例

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# 可変長引数
FontSettings.set_font_sources(src1, src2)
# 単一リスト
FontSettings.set_font_sources([src1, src2])
# 複数リスト（フラット化）
FontSettings.set_font_sources([src1], [src2])
# 混合 — こちらもフラット化
FontSettings.set_font_sources([src1, src2], src2)
```

### 参照
* class [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/)
