---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance FileCache baru."
type: docs
url: /id/python-net/groupdocs.viewer.caching/filecache/__init__/
is_root: false
weight: 10
---


## __init__ {#cache_path}

Menginisialisasi sebuah instance FileCache baru.

```python
def __init__(self, cache_path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cache_path | `str` | Jalur relatif atau absolut tempat cache dokumen akan disimpan. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `cache_path` bernilai None. |

## __init__ {#cache_path-cache_sub_folder}

Menginisialisasi sebuah instance baru dari kelas FileCache.

```python
def __init__(self, cache_path, cache_sub_folder):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cache_path | `str` | Jalur relatif atau absolut tempat cache dokumen akan disimpan. |
| cache_sub_folder | `str` | Sub-folder yang akan ditambahkan ke `cache_path`. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `cache_sub_folder` bernilai None. |

### Lihat Juga
* class [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache/)
