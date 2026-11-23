---
title: "properti remove_comments"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Properti ini menonaktifkan perenderan komentar ketika diatur ke True."
type: docs
url: /id/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/
is_root: false
weight: 2100
---


## remove_comments property

Properti ini menonaktifkan rendering komentar ketika diatur ke True. Secara default nilainya False, sehingga semua komentar ditampilkan.

Beberapa format dokumen seperti PDF dan WordProcessing dapat berisi komentar. Secara default GroupDocs.Viewer merendernya. Dengan opsi ini diatur ke True, komentar dapat dikecualikan dari dokumen hasil.

Opsi ini menggantikan properti `RenderComments` yang usang.

### Definition:
```python
@property
def remove_comments(self):
    ...
@remove_comments.setter
def remove_comments(self, value):
    ...
```

### Lihat Juga
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
