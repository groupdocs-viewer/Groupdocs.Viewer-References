---
title: "proprietà fonts_to_exclude"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "L'elenco dei nomi dei font da escludere dal documento HTML."
type: docs
url: /it/python-net/groupdocs.viewer.options/htmlviewoptions/fonts_to_exclude/
is_root: false
weight: 2020
---


## fonts_to_exclude property

L'elenco dei nomi dei font da escludere dal documento HTML.

I font aggiunti al documento HTML migliorano la stabilità della visualizzazione di output, ma allo stesso tempo aumentano le dimensioni del risultato del rendering. Questa opzione consente di bilanciare tra stabilità e dimensione dell'output. Includi i nomi dei font che sono popolari e installati nella maggior parte dei sistemi.

Si prega di notare, questa proprietà è attiva solo quando l'opzione [`HtmlViewOptions.ExcludeFonts`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/) è disabilitata.

Per dettagli e esempio di codice, vedere la documentazione.

### Definition:
```python
@property
def fonts_to_exclude(self):
    ...
@fonts_to_exclude.setter
def fonts_to_exclude(self, value):
    ...
```

### Vedi anche
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
