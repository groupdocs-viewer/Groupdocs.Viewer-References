---
title: from_stream method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Detects file type by reading the file signature."
type: docs
url: /python-net/groupdocs.viewer/filetype/from_stream/
is_root: false
weight: 1120
---


## from_stream {#stream}

Detects file type by reading the file signature.

```python
def from_stream(cls, stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | The file stream. |

## from_stream {#stream-password}

Detects file type by reading the file signature.

```python
def from_stream(cls, stream, password):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | The file stream. |
| password | `str` | The password to open the file. |

## from_stream {#stream-logger}

Detects file type by reading the file signature.

```python
def from_stream(cls, stream, logger):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | The file stream. |
| logger | `ILogger` | The logger. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

## from_stream {#stream-password-logger}

Detects the file type by reading the file signature.

```python
def from_stream(cls, stream, password, logger):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | The file stream. |
| password | `str` | The password to open the file. |
| logger | `ILogger` | The logger. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

### See Also
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
