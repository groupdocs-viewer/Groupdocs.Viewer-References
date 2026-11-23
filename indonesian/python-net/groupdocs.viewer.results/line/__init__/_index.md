---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi instance baru dari Line."
type: docs
url: /id/python-net/groupdocs.viewer.results/line/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari [`Line`](/viewer/python-net/groupdocs.viewer.results/line/).

```python
def __init__(self):
    ...
```

## __init__ {#line-x-y-width-height-words}

Menginisialisasi instance baru dari kelas [`Line`](/viewer/python-net/groupdocs.viewer.results/line/).

```python
def __init__(self, line, x, y, width, height, words):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| line | `str` | Baris. |
| x | `float` | Koordinat X dari titik kiri atas tertinggi pada tata letak halaman tempat persegi panjang yang berisi baris dimulai. |
| y | `float` | Koordinat Y dari titik kiri atas tertinggi pada tata letak halaman tempat persegi panjang yang berisi baris dimulai. |
| width | `float` | Lebar persegi panjang yang berisi baris (dalam piksel). |
| height | `float` | Tinggi persegi panjang yang berisi baris (dalam piksel). |
| words | `List[Word]` | Kata-kata yang terkandung dalam baris. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Dilempar ketika `line` bernilai null atau kosong, atau ketika `words` bernilai null. |

### Lihat Juga
* class [`Line`](/viewer/python-net/groupdocs.viewer.results/line/)
