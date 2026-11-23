---
title: "Método from_stream"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Detecta el tipo de archivo leyendo la firma del archivo."
type: docs
url: /es/python-net/groupdocs.viewer/filetype/from_stream/
is_root: false
weight: 1120
---


## from_stream {#stream}

Detecta el tipo de archivo leyendo la firma del archivo.

```python
def from_stream(cls, stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | `io.RawIOBase` | El flujo del archivo. |

## from_stream {#stream-password}

Detecta el tipo de archivo leyendo la firma del archivo.

```python
def from_stream(cls, stream, password):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | `io.RawIOBase` | El flujo del archivo. |
| password | `str` | La contraseña para abrir el archivo. |

## from_stream {#stream-logger}

Detecta el tipo de archivo leyendo la firma del archivo.

```python
def from_stream(cls, stream, logger):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | `io.RawIOBase` | El flujo del archivo. |
| logger | `ILogger` | El logger. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

## from_stream {#stream-password-logger}

Detecta el tipo de archivo leyendo la firma del archivo.

```python
def from_stream(cls, stream, password, logger):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | `io.RawIOBase` | El flujo del archivo. |
| password | `str` | La contraseña para abrir el archivo. |
| logger | `ILogger` | El logger. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

### Ver también
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
