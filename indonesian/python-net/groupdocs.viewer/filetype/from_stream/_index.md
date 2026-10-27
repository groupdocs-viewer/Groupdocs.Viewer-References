---
title: "metode from_stream"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mendeteksi tipe file dengan membaca tanda tangan file."
type: docs
url: /id/python-net/groupdocs.viewer/filetype/from_stream/
is_root: false
weight: 1120
---


## from_stream {#stream}

Mendeteksi tipe file dengan membaca tanda tangan file.

```python
def from_stream(cls, stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | `io.RawIOBase` | Aliran file. |

## from_stream {#stream-password}

Mendeteksi tipe file dengan membaca tanda tangan file.

```python
def from_stream(cls, stream, password):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | `io.RawIOBase` | Aliran file. |
| password | `str` | Kata sandi untuk membuka file. |

## from_stream {#stream-logger}

Mendeteksi tipe file dengan membaca tanda tangan file.

```python
def from_stream(cls, stream, logger):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | `io.RawIOBase` | Aliran file. |
| logger | `ILogger` | Logger. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

## from_stream {#stream-password-logger}

Mendeteksi tipe file dengan membaca tanda tangan file.

```python
def from_stream(cls, stream, password, logger):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | `io.RawIOBase` | Aliran file. |
| password | `str` | Kata sandi untuk membuka file. |
| logger | `ILogger` | Logger. |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

### Lihat Juga
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
