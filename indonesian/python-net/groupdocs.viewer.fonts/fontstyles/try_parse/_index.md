---
title: "metode try_parse"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mencoba mengurai string mentah yang ditentukan sebagai nama gaya font."
type: docs
url: /id/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/
is_root: false
weight: 1060
---


## try_parse {#style-parsed}

Mencoba mengurai string mentah yang ditentukan sebagai nama gaya font.

```python
def try_parse(cls, style, parsed):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| style | `str` | String yang harus diparse sebagai gaya font. |
| parsed | `FontStyles` | Gaya font yang diparse pada keberhasilan atau `FontStyles.Regular` pada kegagalan. |

**Returns:** bool: True if string was successfully parsed as a correct font style; False otherwise.

### Lihat Juga
* class [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/)
