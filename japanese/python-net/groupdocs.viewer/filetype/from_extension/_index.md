---
title: "from_extension メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ファイル拡張子をファイルタイプにマッピングします。"
type: docs
url: /ja/python-net/groupdocs.viewer/filetype/from_extension/
is_root: false
weight: 1090
---


## from_extension {#extension}

ファイル拡張子をファイルタイプにマッピングします。

```python
def from_extension(cls, extension):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| extension | `str` | ピリオド '.' の有無にかかわらずファイル拡張子です。 |

**Returns:** FileType: The corresponding file type if supported; otherwise `FileType.unknown`.

### 参照
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
