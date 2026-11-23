---
title: "CadViewInfo クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "CAD 図面のビュー情報を表します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/cadviewinfo/
is_root: false
weight: 30
---


## CadViewInfo class

CAD 図面のビュー情報を表します。

CadViewInfo 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/__init__/#file_type-pages-layers-layouts) | CadViewInfo の新しいインスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | 現在のオブジェクトを表す文字列を返します。( [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) から継承) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [layers](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layers/) | CAD 図面に含まれるレイヤーの一覧です。 |
| [layouts](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layouts/) | CAD 図面に含まれるレイアウトの一覧です。 |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | ファイルの種類です。( [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) から継承) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | 表示するページのリストです。 ( [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) から継承) |

### 例

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import CadViewInfo

def get_cad_info():
    with Viewer("sample.dwg") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        cad_info = cast(CadViewInfo, info)

        print("File type:", cad_info.file_type)
        print("Pages count:", len(cad_info.pages))
        print("Layers:")
        for layer in cad_info.layers:
            print(f"  {layer.name} (visible={layer.visible})")
        print("Layouts:")
        for layout in cad_info.layouts:
            print(f"  {layout.name} ({layout.width}x{layout.height})")

if __name__ == "__main__":
    get_cad_info()
```

### Guides
`CadViewInfo` を使用するタスク ガイド:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### 参照
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
