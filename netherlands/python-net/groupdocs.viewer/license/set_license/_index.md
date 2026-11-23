---
title: "set_license-methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Pas een licentie toe op het huidige proces."
type: docs
url: /nl/python-net/groupdocs.viewer/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Pas een licentie toe op het huidige proces.

```python
def set_license(self, license_source):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| license_source |  | Of een tekenreeks pad naar een ``.lic``-bestand of een leesbaar bestand-achtig object dat de licentiebits levert. Bestand-achtige invoer wordt naar een tijdelijk bestand geschreven voordat deze aan de bridge wordt doorgegeven. |

| Gooit | Beschrijving |
| :- | :- |
| `TypeError` | Als ``license_source`` noch een tekenreeks pad noch een leesbaar bestand-achtig object is. |

### Zie ook
* class [`License`](/viewer/python-net/groupdocs.viewer/license/)
