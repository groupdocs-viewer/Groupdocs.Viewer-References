---
title: "save_attachment メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "添付ファイルを宛先ストリームに保存します。"
type: docs
url: /ja/python-net/groupdocs.viewer/viewer/save_attachment/
is_root: false
weight: 1070
---


## save_attachment {#attachment-destination}

`destination` ストリームに添付ファイルを保存します。

- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def save_attachment(self, attachment, destination):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| attachment | `Attachment` | 添付ファイル。 |
| destination | `io.RawIOBase` | 書き込み可能なストリーム。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `destination` が None の場合。 |
| `PasswordRequiredException` | ドキュメントを開くのにパスワードが必要な場合。 |
| `IncorrectPasswordException` | 指定されたパスワードが正しくない場合。 |
| `GroupDocsViewerException` | 添付ファイルが見つからなかった場合。 |

### 例

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### 参照
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
