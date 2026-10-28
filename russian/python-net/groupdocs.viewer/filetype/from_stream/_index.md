---
title: "Метод from_stream"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Определяет тип файла, читая сигнатуру файла."
type: docs
url: /ru/python-net/groupdocs.viewer/filetype/from_stream/
is_root: false
weight: 1120
---


## from_stream {#stream}

Определяет тип файла, читая сигнатуру файла.

```python
def from_stream(cls, stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | `io.RawIOBase` | Поток файла. |

## from_stream {#stream-password}

Определяет тип файла, читая сигнатуру файла.

```python
def from_stream(cls, stream, password):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | `io.RawIOBase` | Поток файла. |
| password | `str` | Пароль для открытия файла. |

## from_stream {#stream-logger}

Определяет тип файла, читая сигнатуру файла.

```python
def from_stream(cls, stream, logger):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | `io.RawIOBase` | Поток файла. |
| logger | `ILogger` | Логгер. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

## from_stream {#stream-password-logger}

Определяет тип файла, читая сигнатуру файла.

```python
def from_stream(cls, stream, password, logger):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | `io.RawIOBase` | Поток файла. |
| password | `str` | Пароль для открытия файла. |
| logger | `ILogger` | Логгер. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

### См. также
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
