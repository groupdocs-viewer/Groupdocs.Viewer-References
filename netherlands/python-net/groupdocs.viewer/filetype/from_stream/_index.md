---
title: "from_stream-methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Detecteert bestandstype door de bestandssignatuur te lezen."
type: docs
url: /nl/python-net/groupdocs.viewer/filetype/from_stream/
is_root: false
weight: 1120
---


## from_stream {#stream}

Detecteert bestandstype door de bestandssignatuur te lezen.

```python
def from_stream(cls, stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | `io.RawIOBase` | De bestandsstroom. |

## from_stream {#stream-password}

Detecteert bestandstype door de bestandssignatuur te lezen.

```python
def from_stream(cls, stream, password):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | `io.RawIOBase` | De bestandsstroom. |
| password | `str` | Het wachtwoord om het bestand te openen. |

## from_stream {#stream-logger}

Detecteert bestandstype door de bestandssignatuur te lezen.

```python
def from_stream(cls, stream, logger):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | `io.RawIOBase` | De bestandsstroom. |
| logger | `ILogger` | De logger. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

## from_stream {#stream-password-logger}

Detecteert het bestandstype door de bestandssignatuur te lezen.

```python
def from_stream(cls, stream, password, logger):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | `io.RawIOBase` | De bestandsstroom. |
| password | `str` | Het wachtwoord om het bestand te openen. |
| logger | `ILogger` | De logger. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

### Zie ook
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
