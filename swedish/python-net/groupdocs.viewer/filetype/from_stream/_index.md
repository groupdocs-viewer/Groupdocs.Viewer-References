---
title: "from_stream‑metoden"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Detekterar filtyp genom att läsa filens signatur."
type: docs
url: /sv/python-net/groupdocs.viewer/filetype/from_stream/
is_root: false
weight: 1120
---


## from_stream {#stream}

Detekterar filtyp genom att läsa filens signatur.

```python
def from_stream(cls, stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | `io.RawIOBase` | Filströmmen. |

## from_stream {#stream-password}

Detekterar filtyp genom att läsa filens signatur.

```python
def from_stream(cls, stream, password):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | `io.RawIOBase` | Filströmmen. |
| password | `str` | Lösenordet för att öppna filen. |

## from_stream {#stream-logger}

Detekterar filtyp genom att läsa filens signatur.

```python
def from_stream(cls, stream, logger):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | `io.RawIOBase` | Filströmmen. |
| logger | `ILogger` | Loggaren. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

## from_stream {#stream-password-logger}

Detekterar filtypen genom att läsa filens signatur.

```python
def from_stream(cls, stream, password, logger):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | `io.RawIOBase` | Filströmmen. |
| password | `str` | Lösenordet för att öppna filen. |
| logger | `ILogger` | Loggaren. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

### Se även
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
