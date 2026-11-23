---
title: "OutlookOptions クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Outlook データファイルのレンダリングオプションを含みます。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/outlookoptions/
is_root: false
weight: 130
---


## OutlookOptions class

Outlook データファイルのレンダリングオプションを含みます。

詳細については、GroupDocs のドキュメントをご覧ください。

OutlookOptions 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/outlookoptions/__init__/) |  |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [address_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/address_filter/) | 送信者または受信者でメッセージをフィルタリングするために使用されるメールアドレス。 |
| [folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/folder/) | レンダリングするフォルダーの名前（例: Inbox、Sent Item、Deleted Items）。 |
| [max_items_in_folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/) | 1つのフォルダーからレンダリングできるメッセージまたはアイテムの最大数。 |
| [text_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/text_filter/) | メッセージをフィルタリングするために使用されるキーワード。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_outlook():
    with Viewer("sample.pst") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "outlook.html"
        )
        # フォルダーごとにレンダリングされるアイテム数を制限します。
        view_options.outlook_options.max_items_in_folder = 30
        viewer.view(view_options)
```

### 参照
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
