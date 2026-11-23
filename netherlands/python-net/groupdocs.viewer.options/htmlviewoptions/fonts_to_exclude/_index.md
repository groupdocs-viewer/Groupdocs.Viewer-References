---
title: "fonts_to_exclude-eigenschap"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De lijst met lettertype‑namen die uit het HTML‑document moeten worden uitgesloten."
type: docs
url: /nl/python-net/groupdocs.viewer.options/htmlviewoptions/fonts_to_exclude/
is_root: false
weight: 2020
---


## fonts_to_exclude property

De lijst met lettertype‑namen die uit het HTML‑document moeten worden uitgesloten.

De lettertypen die aan het HTML-document worden toegevoegd, verbeteren de stabiliteit van de uitvoerweergave, maar vergroten tegelijkertijd de grootte van het renderresultaat. Deze optie stelt u in staat een balans te vinden tussen stabiliteit en uitvoergrootte. Neem de lettertypenamen op die populair zijn en op de meeste systemen geïnstalleerd.

Let op, deze eigenschap is alleen actief wanneer de [`HtmlViewOptions.ExcludeFonts`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/) optie is uitgeschakeld.

Voor details en code‑voorbeeld, zie de documentatie.

### Definition:
```python
@property
def fonts_to_exclude(self):
    ...
@fonts_to_exclude.setter
def fonts_to_exclude(self, value):
    ...
```

### Zie ook
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
