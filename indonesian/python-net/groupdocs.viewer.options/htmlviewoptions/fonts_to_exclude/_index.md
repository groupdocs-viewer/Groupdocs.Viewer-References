---
title: "properti fonts_to_exclude"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Daftar nama font yang akan dikecualikan dari dokumen HTML."
type: docs
url: /id/python-net/groupdocs.viewer.options/htmlviewoptions/fonts_to_exclude/
is_root: false
weight: 2020
---


## fonts_to_exclude property

Daftar nama font yang akan dikecualikan dari dokumen HTML.

Font yang ditambahkan ke dalam dokumen HTML meningkatkan stabilitas tampilan output, sekaligus meningkatkan ukuran hasil rendering. Opsi ini memungkinkan Anda menyeimbangkan antara stabilitas dan ukuran output. Sertakan nama font yang populer dan terpasang pada kebanyakan sistem.

Harap perhatikan, properti ini aktif hanya ketika opsi [`HtmlViewOptions.ExcludeFonts`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/) dinonaktifkan.

Untuk detail dan contoh kode, lihat dokumentasi.

### Definition:
```python
@property
def fonts_to_exclude(self):
    ...
@fonts_to_exclude.setter
def fonts_to_exclude(self, value):
    ...
```

### Lihat Juga
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
