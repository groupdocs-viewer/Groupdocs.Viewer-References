---
title: "proprietà disable_chars_grouping"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "La proprietà disabilita il raggruppamento dei simboli per un posizionamento preciso dei simboli durante il rendering della pagina."
type: docs
url: /it/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/
is_root: false
weight: 2010
---


## disable_chars_grouping property

La proprietà disabilita il raggruppamento dei simboli per un posizionamento preciso dei simboli durante il rendering della pagina.

Durante la conversione di file PDF, GroupDocs.Viewer raggruppa i singoli caratteri in parole per migliorare le prestazioni di rendering. Se il documento contiene geroglifici o simboli speciali, potresti voler proibire il raggruppamento dei caratteri per garantire un layout più preciso. Il valore predefinito è False.

Per un esempio di codice, vedere la documentazione.

### Definition:
```python
@property
def disable_chars_grouping(self):
    ...
@disable_chars_grouping.setter
def disable_chars_grouping(self, value):
    ...
```

### Vedi anche
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
