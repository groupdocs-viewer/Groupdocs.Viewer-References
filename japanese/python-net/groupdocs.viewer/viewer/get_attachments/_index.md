---
title: "get_attachments メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ドキュメントに含まれる添付ファイルを返します。"
type: docs
url: /ja/python-net/groupdocs.viewer/viewer/get_attachments/
is_root: false
weight: 1030
---


## get_attachments

ドキュメントに含まれる添付ファイルを返します。

詳しく読む:
- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def get_attachments(self):
    ...
```

**Returns:** Attachments contained by the document.

| 例外 | 説明 |
| :- | :- |
| `PasswordRequiredException` | ドキュメントを開くのにパスワードが必要な場合にスローされます。 |
| `IncorrectPasswordException` | 指定されたパスワードが正しくない場合にスローされます。 |

### 例

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # 各添付ファイルをファイルに保存する
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### 参照
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
