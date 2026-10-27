---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "新しい Attachment インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/attachment/__init__/
is_root: false
weight: 10
---


## __init__

新しい [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/) インスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#file_name-file_path}

新しい Attachment インスタンスを初期化します。

```python
def __init__(self, file_name, file_path):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file_name | `str` | 添付ファイル名です。 |
| file_path | `str` | 添付ファイルの相対パス（例: "folder/file.docx"）または、ファイルがアーカイブのルート、メールメッセージ、またはデータファイルにある場合のファイル名。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `file_path` が None または空の場合。 |

## __init__ {#id-file_name-file_path-size}

Attachment クラスの新しいインスタンスを初期化します。

```python
def __init__(self, id, file_name, file_path, size):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| id | `str` | 添付ファイルの（単一ファイルのコンテキストにおける）一意の識別子。 |
| file_name | `str` | 添付ファイル名です。 |
| file_path | `str` | 添付ファイルの相対パス（例: `folder/file.docx`）または、ファイルがアーカイブのルート、メールメッセージ、またはデータファイルにある場合のファイル名。 |
| size | `int` | 添付ファイルのサイズ（バイト単位）。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `file_path` が null または空の場合。 |

## __init__ {#id-file_name-file_path-file_type-size}

Attachment クラスの新しいインスタンスを初期化します。

```python
def __init__(self, id, file_name, file_path, file_type, size):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| id | `str` | 添付ファイルの（単一ファイルのコンテキストにおける）一意の識別子。 |
| file_name | `str` | 添付ファイル名です。 |
| file_path | `str` | 添付ファイルの相対パス（例: `folder/file.docx`）または、ファイルがアーカイブのルート、メールメッセージ、またはデータファイルにある場合のファイル名。 |
| file_type | `FileType` | 添付ファイルの種類。 |
| size | `int` | 添付ファイルのサイズ（バイト単位）。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `file_type` が null のとき。 |

### 参照
* class [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/)
