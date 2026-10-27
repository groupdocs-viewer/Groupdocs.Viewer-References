---
title: "from_stream μέθοδος"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Ανιχνεύει τον τύπο αρχείου διαβάζοντας την υπογραφή του αρχείου."
type: docs
url: /el/python-net/groupdocs.viewer/filetype/from_stream/
is_root: false
weight: 1120
---


## from_stream {#stream}

Ανιχνεύει τον τύπο αρχείου διαβάζοντας την υπογραφή του αρχείου.

```python
def from_stream(cls, stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | `io.RawIOBase` | Η ροή αρχείου. |

## from_stream {#stream-password}

Ανιχνεύει τον τύπο αρχείου διαβάζοντας την υπογραφή του αρχείου.

```python
def from_stream(cls, stream, password):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | `io.RawIOBase` | Η ροή αρχείου. |
| password | `str` | Ο κωδικός πρόσβασης για το άνοιγμα του αρχείου. |

## from_stream {#stream-logger}

Ανιχνεύει τον τύπο αρχείου διαβάζοντας την υπογραφή του αρχείου.

```python
def from_stream(cls, stream, logger):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | `io.RawIOBase` | Η ροή αρχείου. |
| logger | `ILogger` | Ο logger. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

## from_stream {#stream-password-logger}

Ανιχνεύει τον τύπο αρχείου διαβάζοντας την υπογραφή του αρχείου.

```python
def from_stream(cls, stream, password, logger):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | `io.RawIOBase` | Η ροή αρχείου. |
| password | `str` | Ο κωδικός πρόσβασης για το άνοιγμα του αρχείου. |
| logger | `ILogger` | Ο logger. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

### Δείτε επίσης
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
