---
title: "from_media_type メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ファイルのメディアタイプを FileType にマッピングします（例: 'application/pdf' は FileType.pdf にマッピングされます）。"
type: docs
url: /ja/python-net/groupdocs.viewer/filetype/from_media_type/
is_root: false
weight: 1110
---


## from_media_type {#media_type}

ファイルのメディアタイプを [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) にマッピングします（例: 'application/pdf' は [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/) にマップされます）。

```python
def from_media_type(cls, media_type):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| media_type | `str` | ファイルメディアタイプ、例: ``application/pdf``。 |

**Returns:** FileType: Corresponding file type when found; otherwise returns the default `FileType.unknown`.

### 参照
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
