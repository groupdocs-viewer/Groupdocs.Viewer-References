---
title: "méthode rotate_page"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Applique la rotation horaire à une page."
type: docs
url: /fr/python-net/groupdocs.viewer.options/viewoptions/rotate_page/
is_root: false
weight: 1010
---


## rotate_page {#page_number-rotation}

Applique la rotation horaire à une page.

Pour plus de détails, consultez la documentation à l'adresse https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/.

```python
def rotate_page(self, page_number, rotation):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| page_number | `int` | Le numéro de page doit être strictement supérieur à 0. |
| rotation | `Rotation` | La valeur de rotation. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si la rotation pour la page numéro `page_number` a déjà été ajoutée. |

### Voir aussi
* class [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)
