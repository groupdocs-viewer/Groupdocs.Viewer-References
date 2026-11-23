---
title: "méthode create_page_stream"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Crée le flux utilisé pour écrire les données de page de sortie."
type: docs
url: /fr/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/create_page_stream/
is_root: false
weight: 1010
---


## create_page_stream {#page_number}

Crée le flux utilisé pour écrire les données de page de sortie.

```python
def create_page_stream(self, page_number):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| page_number | `int` | Le numéro d'une page. |

**Returns:** io.RawIOBase: Stream used to write output page data.

### Exemple

```python
    import io
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import PngViewOptions

    page_buffers = {}

    def create_page_stream(page_number):
        buf = io.BytesIO()
        page_buffers[page_number] = buf
        return buf

    with Viewer("input.docx") as viewer:
        viewer.view(PngViewOptions(create_page_stream))
    ```

### Voir aussi
* class [`IPageStreamFactory`](/viewer/python-net/groupdocs.viewer.interfaces/ipagestreamfactory/)
