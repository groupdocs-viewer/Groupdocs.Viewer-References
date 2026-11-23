---
title: "from_stream 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "通过读取文件签名检测文件类型。"
type: docs
url: /zh/python-net/groupdocs.viewer/filetype/from_stream/
is_root: false
weight: 1120
---


## from_stream {#stream}

通过读取文件签名检测文件类型。

```python
def from_stream(cls, stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 文件流。 |

## from_stream {#stream-password}

通过读取文件签名检测文件类型。

```python
def from_stream(cls, stream, password):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 文件流。 |
| password | `str` | 打开文件的密码。 |

## from_stream {#stream-logger}

通过读取文件签名检测文件类型。

```python
def from_stream(cls, stream, logger):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 文件流。 |
| logger | `ILogger` | 日志记录器。 |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

## from_stream {#stream-password-logger}

通过读取文件签名检测文件类型。

```python
def from_stream(cls, stream, password, logger):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | `io.RawIOBase` | 文件流。 |
| password | `str` | 打开文件的密码。 |
| logger | `ILogger` | 日志记录器。 |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

### 另见
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
