---
title: from_stream method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Detects file type by reading the file signature."
type: docs
url: /python-net/groupdocs.viewer/filetype/from_stream/
is_root: false
weight: 1060
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

### Aliases

These names call `from_stream` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `from_stream_stream` | `from_stream_stream(stream, password, logger)`<br>`from_stream_stream(stream, password)`<br>`from_stream_stream(stream, logger)`<br>`from_stream_stream(stream)` |
| `from_stream_streams` | `from_stream_streams(stream, password, logger)`<br>`from_stream_streams(stream, password)`<br>`from_stream_streams(stream, logger)`<br>`from_stream_streams(stream)` |
| `from_stream_file` | `from_stream_file(stream, password, logger)`<br>`from_stream_file(stream, password)` |
| `from_stream_string` | `from_stream_string(stream, password, logger)`<br>`from_stream_string(stream, password)` |

### See Also
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
