---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise les options pour le rendu des documents de traitement de texte."
type: docs
url: /fr/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise les options pour le rendu des documents de traitement de texte.

```python
def __init__(self):
    ...
```

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("document.docx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Activer le rendu des modifications suivies.
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### Voir aussi
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
