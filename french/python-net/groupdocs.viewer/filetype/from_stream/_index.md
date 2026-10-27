---
title: "Méthode from_stream"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Détecte le type de fichier en lisant la signature du fichier."
type: docs
url: /fr/python-net/groupdocs.viewer/filetype/from_stream/
is_root: false
weight: 1120
---


## from_stream {#stream}

Détecte le type de fichier en lisant la signature du fichier.

```python
def from_stream(cls, stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | Le flux de fichier. |

## from_stream {#stream-password}

Détecte le type de fichier en lisant la signature du fichier.

```python
def from_stream(cls, stream, password):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | Le flux de fichier. |
| password | `str` | Le mot de passe pour ouvrir le fichier. |

## from_stream {#stream-logger}

Détecte le type de fichier en lisant la signature du fichier.

```python
def from_stream(cls, stream, logger):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | Le flux de fichier. |
| logger | `ILogger` | Le logger. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

## from_stream {#stream-password-logger}

Détecte le type de fichier en lisant la signature du fichier.

```python
def from_stream(cls, stream, password, logger):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | `io.RawIOBase` | Le flux de fichier. |
| password | `str` | Le mot de passe pour ouvrir le fichier. |
| logger | `ILogger` | Le logger. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

### Voir aussi
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
