---
title: "from_stream Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Erkennt den Dateityp durch Lesen der Dateisignatur."
type: docs
url: /de/python-net/groupdocs.viewer/filetype/from_stream/
is_root: false
weight: 1120
---


## from_stream {#stream}

Erkennt den Dateityp durch Lesen der Dateisignatur.

```python
def from_stream(cls, stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | `io.RawIOBase` | Der Dateistream. |

## from_stream {#stream-password}

Erkennt den Dateityp durch Lesen der Dateisignatur.

```python
def from_stream(cls, stream, password):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | `io.RawIOBase` | Der Dateistream. |
| password | `str` | Das Passwort, um die Datei zu öffnen. |

## from_stream {#stream-logger}

Erkennt den Dateityp durch Lesen der Dateisignatur.

```python
def from_stream(cls, stream, logger):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | `io.RawIOBase` | Der Dateistream. |
| logger | `ILogger` | Der Logger. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

## from_stream {#stream-password-logger}

Erkennt den Dateityp durch Lesen der Dateisignatur.

```python
def from_stream(cls, stream, password, logger):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | `io.RawIOBase` | Der Dateistream. |
| password | `str` | Das Passwort, um die Datei zu öffnen. |
| logger | `ILogger` | Der Logger. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

### Siehe auch
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
