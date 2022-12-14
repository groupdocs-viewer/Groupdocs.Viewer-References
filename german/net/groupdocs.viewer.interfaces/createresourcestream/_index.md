---
title: CreateResourceStream
second_title: GroupDocs.Viewer für .NET-API-Referenz
description: Stellt die Methode dar die den Stream instanziiert der zum Schreiben von AusgabeHTMLRessourcendaten verwendet wird.
type: docs
weight: 140
url: /de/net/groupdocs.viewer.interfaces/createresourcestream/
---
## CreateResourceStream delegate

Stellt die Methode dar, die den Stream instanziiert, der zum Schreiben von Ausgabe-HTML-Ressourcendaten verwendet wird.

```csharp
public delegate Stream CreateResourceStream(int pageNumber, Resource resource);
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Nummer der Seite. |
| resource | Resource | HTML-Ressource wie Schriftart, Stil, Bild oder Grafik. |

### Rückgabewert

Der Stream, der zum Schreiben von Ausgabe-HTML-Ressourcendaten verwendet wird.

### Siehe auch

* class [Resource](../../groupdocs.viewer.results/resource)
* namensraum [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* Montage [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
