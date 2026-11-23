---
title: "PdfViewInfo クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "PDF ドキュメントのビュー情報を表します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/pdfviewinfo/
is_root: false
weight: 140
---


## PdfViewInfo class

PDF ドキュメントのビュー情報を表します。

PdfViewInfo 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/) | PdfViewInfo の新しいインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/#file_type-pages-printing_allowed) | PdfViewInfo の新しいインスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | 現在のオブジェクトを表す文字列を返します。( [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) から継承) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [printing_allowed](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/printing_allowed/) | printing_allowed プロパティは、ドキュメントの印刷が許可されているかどうかを示します。 |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | ファイルの種類です。( [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) から継承) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | 表示するページのリストです。 ( [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) から継承) |

### 例

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import PdfViewInfo

def get_pdf_info():
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        pdf_info = cast(PdfViewInfo, info)

        print("File type:", pdf_info.file_type)
        print("Pages count:", len(pdf_info.pages))
        print("Printing allowed:", pdf_info.printing_allowed)

if __name__ == "__main__":
    get_pdf_info()
```

### Guides
`PdfViewInfo` を使用するタスク ガイド：

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### 参照
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
