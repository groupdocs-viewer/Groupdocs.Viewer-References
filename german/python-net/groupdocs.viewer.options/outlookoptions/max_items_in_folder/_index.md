---
title: "max_items_in_folder Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die maximale Anzahl von Nachrichten oder Elementen, die aus einem Ordner gerendert werden können."
type: docs
url: /de/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/
is_root: false
weight: 2030
---


## max_items_in_folder property

Die maximale Anzahl von Nachrichten oder Elementen, die aus einem Ordner gerendert werden können.

Outlook‑Datendateien können groß sein und das Abrufen aller Nachrichten kann erhebliche Zeit in Anspruch nehmen. Diese Eigenschaft begrenzt die maximale Anzahl von Nachrichten oder Elementen, die gerendert werden. Der Standardwert ist `50`. Um alle Nachrichten zu rendern, setzen Sie den Wert auf `0`.

Für ein Codebeispiel siehe die Dokumentation.

### Definition:
```python
@property
def max_items_in_folder(self):
    ...
@max_items_in_folder.setter
def max_items_in_folder(self, value):
    ...
```

### Siehe auch
* class [`OutlookOptions`](/viewer/python-net/groupdocs.viewer.options/outlookoptions/)
