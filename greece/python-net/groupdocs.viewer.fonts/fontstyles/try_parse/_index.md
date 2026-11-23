---
title: "μέθοδος try_parse"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Προσπαθεί να αναλύσει την καθορισμένη ακατέργαστη συμβολοσειρά ως όνομα στυλ γραμματοσειράς."
type: docs
url: /el/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/
is_root: false
weight: 1060
---


## try_parse {#style-parsed}

Προσπαθεί να αναλύσει την καθορισμένη ακατέργαστη συμβολοσειρά ως όνομα στυλ γραμματοσειράς.

```python
def try_parse(cls, style, parsed):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| style | `str` | Συμβολοσειρά που πρέπει να αναλυθεί ως στυλ γραμματοσειράς. |
| parsed | `FontStyles` | Αναλυμένο στυλ γραμματοσειράς σε περίπτωση επιτυχίας ή `FontStyles.Regular` σε περίπτωση αποτυχίας. |

**Returns:** bool: True if string was successfully parsed as a correct font style; False otherwise.

### Δείτε επίσης
* class [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/)
