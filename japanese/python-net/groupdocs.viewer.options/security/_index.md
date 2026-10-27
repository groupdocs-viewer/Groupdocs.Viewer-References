---
title: "Security クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "PDF ドキュメントのセキュリティオプション。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/security/
is_root: false
weight: 260
---


## Security class

PDF ドキュメントのセキュリティオプション。

詳細については、ドキュメントをご覧ください。

Security 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/security/__init__/) | [`Security`](/viewer/python-net/groupdocs.viewer.options/security/) クラスのインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [document_open_password](/viewer/python-net/groupdocs.viewer.options/security/document_open_password/) | PDF ドキュメントを開くために必要なパスワード。 |
| [permissions](/viewer/python-net/groupdocs.viewer.options/security/permissions/) | 印刷、変更、データ抽出などの PDF ドキュメント権限。 |
| [permissions_password](/viewer/python-net/groupdocs.viewer.options/security/permissions_password/) | 権限設定を変更するために必要なパスワード。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

with Viewer("sample.docx") as viewer:
    security = Security()
    security.document_open_password = "o123"
    security.permissions_password = "p123"
    security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

    pdf_options = PdfViewOptions("protected_document.pdf")
    pdf_options.security = security
    viewer.view(pdf_options)
```

### Guides
`Security` を使用するタスクガイド：

* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)

### 参照
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
