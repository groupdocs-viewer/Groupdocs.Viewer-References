---
title: "properti render_notes"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Properti ini mengaktifkan rendering catatan dan anotasi untuk beberapa format."
type: docs
url: /id/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/
is_root: false
weight: 2130
---


## render_notes property

Properti ini mengaktifkan rendering catatan dan anotasi untuk beberapa format.

Beberapa format, seperti presentasi atau file Microsoft Project, mungkin berisi catatan. Selain itu, file PDF dapat memiliki anotasi popup (petunjuk balon) yang secara default disembunyikan dan hanya terlihat di penampil PDF ketika mengarahkan kursor mouse ke mereka. Secara default, GroupDocs.Viewer tidak merender catatan dan anotasi tersebut (`False`). Untuk melakukannya, set properti ini ke `True`.

Untuk contoh kode, lihat dokumentasi.

### Definition:
```python
@property
def render_notes(self):
    ...
@render_notes.setter
def render_notes(self, value):
    ...
```

### Lihat Juga
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
