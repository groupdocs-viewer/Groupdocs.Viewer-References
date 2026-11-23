---
title: "proprietà disable_font_license_verifications"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "La proprietà disabilita qualsiasi restrizione di licenza per tutti i caratteri nel documento XPS/OXPS corrente."
type: docs
url: /it/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/
is_root: false
weight: 2030
---


## disable_font_license_verifications property

La proprietà disabilita qualsiasi restrizione di licenza per tutti i caratteri nel documento XPS/OXPS corrente.

Molte operazioni con i caratteri non possono essere eseguite se sono proibite dalla licenza del carattere. Ad esempio, alcuni caratteri non possono essere incorporati in un documento PDF se le regole della licenza disabilitano l'incorporamento per quel carattere. Questa opzione consente di saltare la verifica di queste regole.

Fai attenzione quando usi questo flag. Quando è impostato, significa che la persona che lo imposta si assume tutta la responsabilità per eventuali violazioni di licenza o di legge. Si raccomanda vivamente di utilizzare questo flag solo quando sei completamente sicuro di non violare il diritto d'autore. Il valore predefinito è `False`.

Per un esempio di codice, vedere la documentazione all'indirizzo https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

### Definition:
```python
@property
def disable_font_license_verifications(self):
    ...
@disable_font_license_verifications.setter
def disable_font_license_verifications(self, value):
    ...
```

### Vedi anche
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
