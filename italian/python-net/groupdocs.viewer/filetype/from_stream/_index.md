---
title: "metodo from_stream"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rileva il tipo di file leggendo la firma del file."
type: docs
url: /it/python-net/groupdocs.viewer/filetype/from_stream/
is_root: false
weight: 1120
---


## from_stream {#stream}

Rileva il tipo di file leggendo la firma del file.

```python
def from_stream(cls, stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | `io.RawIOBase` | Il flusso del file. |

## from_stream {#stream-password}

Rileva il tipo di file leggendo la firma del file.

```python
def from_stream(cls, stream, password):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | `io.RawIOBase` | Il flusso del file. |
| password | `str` | La password per aprire il file. |

## from_stream {#stream-logger}

Rileva il tipo di file leggendo la firma del file.

```python
def from_stream(cls, stream, logger):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | `io.RawIOBase` | Il flusso del file. |
| logger | `ILogger` | Il logger. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

## from_stream {#stream-password-logger}

Rileva il tipo di file leggendo la firma del file.

```python
def from_stream(cls, stream, password, logger):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | `io.RawIOBase` | Il flusso del file. |
| password | `str` | La password per aprire il file. |
| logger | `ILogger` | Il logger. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

### Vedi anche
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
