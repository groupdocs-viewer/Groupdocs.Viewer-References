---
title: "search-Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Führt eine Textsuche durch und hebt den gefundenen Text im geladenen Dokument gemäß den angegebenen Optionen hervor."
type: docs
url: /de/python-net/groupdocs.viewer/viewer/search/
is_root: false
weight: 1110
---


## search {#options}

Führt eine Textsuche durch und hebt den gefundenen Text im geladenen Dokument gemäß den angegebenen Optionen hervor.

```python
def search(self, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | `SearchHighlightOptions` | Such- und Hervorhebungsoptionen, einschließlich der zu suchenden Textphrase. Darf nicht None sein. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `options` None ist. |

### Siehe auch
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
