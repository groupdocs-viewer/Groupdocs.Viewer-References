---
title: "Attachment クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "メールメッセージ、アーカイブ、PDF ドキュメント、または Outlook データファイルに含まれる添付ファイルを表します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/attachment/
is_root: false
weight: 20
---


## Attachment class

メールメッセージ、アーカイブ、PDF ドキュメント、または Outlook データファイルに含まれる添付ファイルを表します。

Attachment 型は、次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/) | 新しい [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/) インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#file_name-file_path) | 新しい Attachment インスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-size) | Attachment クラスの新しいインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-file_type-size) | Attachment クラスの新しいインスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/attachment/to_string/) | 現在のオブジェクトを表す文字列を返します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.results/attachment/file_name/) | 添付ファイルの名前です。 |
| [file_path](/viewer/python-net/groupdocs.viewer.results/attachment/file_path/) | 添付ファイルの相対パス（例: `folder/file.docx`）または、ファイルがアーカイブのルート、メール メッセージ、またはデータ ファイルにある場合のファイル名です。 |
| [file_type](/viewer/python-net/groupdocs.viewer.results/attachment/file_type/) | 添付ファイルの種類です。 |
| [id](/viewer/python-net/groupdocs.viewer.results/attachment/id/) | この添付ファイルを含む単一ファイルのコンテキスト内における添付ファイルの一意の識別子です。 |
| [size](/viewer/python-net/groupdocs.viewer.results/attachment/size/) | 添付ファイルのサイズ（バイト）です。 |

### 例

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # 添付プロパティにアクセスします（例：ファイル名）
        print(attachment.file_name)
        # 添付ファイルをファイルパスに保存します
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### 参照
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
