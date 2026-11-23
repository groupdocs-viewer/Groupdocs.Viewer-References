---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化一个新的 Attachment 实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/attachment/__init__/
is_root: false
weight: 10
---


## __init__

初始化一个新的 [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/) 实例。

```python
def __init__(self):
    ...
```

## __init__ {#file_name-file_path}

初始化一个新的 Attachment 实例。

```python
def __init__(self, file_name, file_path):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_name | `str` | 附件文件名。 |
| file_path | `str` | 附件相对路径，例如 "folder/file.docx"，或当文件位于归档根目录、电子邮件或数据文件中时的文件名。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `file_path` 为 None 或为空。 |

## __init__ {#id-file_name-file_path-size}

初始化 Attachment 类的一个新实例。

```python
def __init__(self, id, file_name, file_path, size):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| id | `str` | 在单文件上下文中唯一的附件标识符。 |
| file_name | `str` | 附件文件名。 |
| file_path | `str` | 附件相对路径，例如 `folder/file.docx`，或当文件位于归档根目录、电子邮件或数据文件中时的文件名。 |
| size | `int` | 附件文件大小（字节）。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `file_path` 为 null 或为空。 |

## __init__ {#id-file_name-file_path-file_type-size}

初始化 Attachment 类的一个新实例。

```python
def __init__(self, id, file_name, file_path, file_type, size):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| id | `str` | 在单文件上下文中唯一的附件标识符。 |
| file_name | `str` | 附件文件名。 |
| file_path | `str` | 附件相对路径，例如 `folder/file.docx`，或当文件位于归档根目录、电子邮件或数据文件中时的文件名。 |
| file_type | `FileType` | 附件文件类型。 |
| size | `int` | 附件文件大小（字节）。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `file_type` 为 null 时。 |

### 另见
* class [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/)
