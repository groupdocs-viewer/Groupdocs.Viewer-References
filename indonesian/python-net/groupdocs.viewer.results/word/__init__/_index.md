---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi instance baru dari Word."
type: docs
url: /id/python-net/groupdocs.viewer.results/word/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self):
    ...
```

## __init__ {#word-x-y-width-height-characters}

Menginisialisasi instance baru dari [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self, word, x, y, width, height, characters):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| word | `str` | Kata. |
| x | `float` | Koordinat X dari titik kiri atas tertinggi pada tata letak halaman tempat persegi panjang yang berisi kata dimulai. |
| y | `float` | Koordinat Y dari titik kiri atas tertinggi pada tata letak halaman tempat persegi panjang yang berisi kata dimulai. |
| width | `float` | Lebar persegi panjang yang berisi kata. |
| height | `float` | Tinggi persegi panjang yang berisi kata. |
| characters | `List[Character]` | Karakter yang terkandung dalam kata. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `characters` bernilai null. |

### Lihat Juga
* class [`Word`](/viewer/python-net/groupdocs.viewer.results/word/)
