---
title: "méthode try_parse"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Tente d'analyser la chaîne brute spécifiée comme nom de style de police."
type: docs
url: /fr/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/
is_root: false
weight: 1060
---


## try_parse {#style-parsed}

Tente d'analyser la chaîne brute spécifiée comme nom de style de police.

```python
def try_parse(cls, style, parsed):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| style | `str` | Chaîne qui doit être analysée comme un style de police. |
| parsed | `FontStyles` | Style de police analysé en cas de succès ou `FontStyles.Regular` en cas d'échec. |

**Returns:** bool: True if string was successfully parsed as a correct font style; False otherwise.

### Voir aussi
* class [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/)
