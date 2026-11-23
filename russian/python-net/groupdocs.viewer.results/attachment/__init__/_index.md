---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует новый экземпляр Attachment."
type: docs
url: /ru/python-net/groupdocs.viewer.results/attachment/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/).

```python
def __init__(self):
    ...
```

## __init__ {#file_name-file_path}

Инициализирует новый экземпляр Attachment.

```python
def __init__(self, file_name, file_path):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_name | `str` | Имя файла вложения. |
| file_path | `str` | Относительный путь вложения, например "folder/file.docx" или имя файла, когда файл находится в корне архива, в электронном письме или файле данных. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `file_path` равно None или пустой. |

## __init__ {#id-file_name-file_path-size}

Инициализирует новый экземпляр класса Attachment.

```python
def __init__(self, id, file_name, file_path, size):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| id | `str` | Уникальный (в контексте одного файла) идентификатор вложения. |
| file_name | `str` | Имя файла вложения. |
| file_path | `str` | Относительный путь вложения, например `folder/file.docx` или имя файла, когда файл находится в корне архива, в электронном письме или файле данных. |
| size | `int` | Размер файла вложения в байтах. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `file_path` равен null или пустой. |

## __init__ {#id-file_name-file_path-file_type-size}

Инициализирует новый экземпляр класса Attachment.

```python
def __init__(self, id, file_name, file_path, file_type, size):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| id | `str` | Уникальный (в контексте одного файла) идентификатор вложения. |
| file_name | `str` | Имя файла вложения. |
| file_path | `str` | Относительный путь вложения, например `folder/file.docx` или имя файла, когда файл находится в корне архива, в электронном письме или файле данных. |
| file_type | `FileType` | Тип файла вложения. |
| size | `int` | Размер файла вложения в байтах. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `file_type` равен null. |

### См. также
* class [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/)
