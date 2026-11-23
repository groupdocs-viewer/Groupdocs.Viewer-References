---
title: "proprietà max_items_in_folder"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Il numero massimo di messaggi o elementi che possono essere renderizzati da una cartella."
type: docs
url: /it/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/
is_root: false
weight: 2030
---


## max_items_in_folder property

Il numero massimo di messaggi o elementi che possono essere renderizzati da una cartella.

I file di dati Outlook possono essere grandi e il recupero di tutti i messaggi può richiedere molto tempo. Questa proprietà limita il numero massimo di messaggi o elementi visualizzati. Il valore predefinito è `50`. Per visualizzare tutti i messaggi, imposta il valore a `0`.

Per un esempio di codice, vedere la documentazione.

### Definition:
```python
@property
def max_items_in_folder(self):
    ...
@max_items_in_folder.setter
def max_items_in_folder(self, value):
    ...
```

### Vedi anche
* class [`OutlookOptions`](/viewer/python-net/groupdocs.viewer.options/outlookoptions/)
