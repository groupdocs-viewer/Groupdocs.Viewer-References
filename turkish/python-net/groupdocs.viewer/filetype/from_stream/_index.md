---
title: "from_stream yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Dosya imzasını okuyarak dosya türünü algılar."
type: docs
url: /tr/python-net/groupdocs.viewer/filetype/from_stream/
is_root: false
weight: 1120
---


## from_stream {#stream}

Dosya imzasını okuyarak dosya türünü algılar.

```python
def from_stream(cls, stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | `io.RawIOBase` | Dosya akışı. |

## from_stream {#stream-password}

Dosya imzasını okuyarak dosya türünü algılar.

```python
def from_stream(cls, stream, password):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | `io.RawIOBase` | Dosya akışı. |
| password | `str` | Dosyayı açmak için şifre. |

## from_stream {#stream-logger}

Dosya imzasını okuyarak dosya türünü algılar.

```python
def from_stream(cls, stream, logger):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | `io.RawIOBase` | Dosya akışı. |
| logger | `ILogger` | Günlükleyici. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

## from_stream {#stream-password-logger}

Dosya imzasını okuyarak dosya türünü algılar.

```python
def from_stream(cls, stream, password, logger):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | `io.RawIOBase` | Dosya akışı. |
| password | `str` | Dosyayı açmak için şifre. |
| logger | `ILogger` | Günlükleyici. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

### Ayrıca Bakınız
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
