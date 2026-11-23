---
title: "max_items_in_folder-egenskap"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Det maximala antalet meddelanden eller objekt som kan renderas från en mapp."
type: docs
url: /sv/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/
is_root: false
weight: 2030
---


## max_items_in_folder property

Det maximala antalet meddelanden eller objekt som kan renderas från en mapp.

Outlook-datafiler kan vara stora och att hämta alla meddelanden kan ta betydande tid. Denna egenskap begränsar det maximala antalet meddelanden eller objekt som renderas. Standardvärdet är `50`. För att rendera alla meddelanden, sätt värdet till `0`.

För ett kodexempel, se dokumentationen.

### Definition:
```python
@property
def max_items_in_folder(self):
    ...
@max_items_in_folder.setter
def max_items_in_folder(self, value):
    ...
```

### Se även
* class [`OutlookOptions`](/viewer/python-net/groupdocs.viewer.options/outlookoptions/)
