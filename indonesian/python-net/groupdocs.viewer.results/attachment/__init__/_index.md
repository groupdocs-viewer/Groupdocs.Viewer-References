---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance Attachment baru."
type: docs
url: /id/python-net/groupdocs.viewer.results/attachment/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi sebuah instance baru dari [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/).

```python
def __init__(self):
    ...
```

## __init__ {#file_name-file_path}

Menginisialisasi sebuah instance Attachment baru.

```python
def __init__(self, file_name, file_path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_name | `str` | Nama file lampiran. |
| file_path | `str` | Path relatif lampiran misalnya "folder/file.docx" atau nama file ketika file berada di root arsip, dalam pesan e‑mail atau file data. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `file_path` bernilai None atau kosong. |

## __init__ {#id-file_name-file_path-size}

Menginisialisasi sebuah instance baru dari kelas Attachment.

```python
def __init__(self, id, file_name, file_path, size):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| id | `str` | Pengidentifikasi unik (dalam konteks satu berkas) dari lampiran. |
| file_name | `str` | Nama file lampiran. |
| file_path | `str` | Path relatif lampiran misalnya `folder/file.docx` atau nama file ketika file berada di root arsip, dalam pesan e‑mail atau file data. |
| size | `int` | Ukuran file lampiran dalam byte. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `file_path` bernilai null atau kosong. |

## __init__ {#id-file_name-file_path-file_type-size}

Menginisialisasi sebuah instance baru dari kelas Attachment.

```python
def __init__(self, id, file_name, file_path, file_type, size):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| id | `str` | Pengidentifikasi unik (dalam konteks satu berkas) dari lampiran. |
| file_name | `str` | Nama file lampiran. |
| file_path | `str` | Path relatif lampiran misalnya `folder/file.docx` atau nama file ketika file berada di root arsip, dalam pesan e‑mail atau file data. |
| file_type | `FileType` | Tipe file lampiran. |
| size | `int` | Ukuran file lampiran dalam byte. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `file_type` bernilai null. |

### Lihat Juga
* class [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/)
