---
title: "fonts_to_exclude‑Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Liste der Schriftartnamen, die vom HTML-Dokument ausgeschlossen werden sollen."
type: docs
url: /de/python-net/groupdocs.viewer.options/htmlviewoptions/fonts_to_exclude/
is_root: false
weight: 2020
---


## fonts_to_exclude property

Die Liste der Schriftartnamen, die vom HTML-Dokument ausgeschlossen werden sollen.

Die in das HTML‑Dokument eingebetteten Schriftarten verbessern die Stabilität der Ausgabedarstellung, erhöhen jedoch gleichzeitig die Größe des Rendering‑Ergebnisses. Diese Option ermöglicht es Ihnen, ein Gleichgewicht zwischen Stabilität und Ausgabengröße zu finden. Geben Sie die Schriftartnamen an, die verbreitet und auf den meisten Systemen installiert sind.

Bitte beachten Sie, dass diese Eigenschaft nur aktiv ist, wenn die Optionen [`HtmlViewOptions.ExcludeFonts`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/) deaktiviert sind.

Für Details und Codebeispiel siehe die Dokumentation.

### Definition:
```python
@property
def fonts_to_exclude(self):
    ...
@fonts_to_exclude.setter
def fonts_to_exclude(self, value):
    ...
```

### Siehe auch
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
