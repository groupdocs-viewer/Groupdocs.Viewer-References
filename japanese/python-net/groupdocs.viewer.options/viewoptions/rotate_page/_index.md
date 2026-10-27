---
title: "rotate_page メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ページに時計回りの回転を適用します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/viewoptions/rotate_page/
is_root: false
weight: 1010
---


## rotate_page {#page_number-rotation}

ページに時計回りの回転を適用します。

詳細については、https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/ のドキュメントをご覧ください。

```python
def rotate_page(self, page_number, rotation):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| page_number | `int` | ページ番号は、0 より大きくなければなりません。 |
| rotation | `Rotation` | 回転値。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | ページ番号 `page_number` の回転がすでに追加されている場合。 |

### 参照
* class [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)
