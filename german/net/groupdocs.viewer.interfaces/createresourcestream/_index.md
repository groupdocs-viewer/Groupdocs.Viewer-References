---
title: "CreateResourceStream"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Stellt die Methode dar, die den Stream erzeugt, der zum Schreiben von HTML-Ressourcendaten der Ausgabe verwendet wird."
type: docs
weight: 720
url: /de/net/groupdocs.viewer.interfaces/createresourcestream/
---

## CreateResourceStream delegate

Stellt die Methode dar, die den Stream erzeugt, der zum Schreiben von HTML-Ressourcendaten der Ausgabe verwendet wird.

```csharp
public delegate Stream CreateResourceStream(int pageNumber, Resource resource);
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Nummer der Seite. |
| Ressource | Resource | HTML-Ressource wie Schriftart, Stil, Bild oder Grafik. |

### Rückgabewert

Der Stream, der zum Schreiben der Ausgabedaten der HTML-Ressource verwendet wird.

### Siehe auch

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
