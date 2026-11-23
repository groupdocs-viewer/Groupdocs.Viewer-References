---
title: "IPageStreamFactory"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Definiert die Methoden, die zum Instanziieren und Freigeben des Ausgabeseitestreams erforderlich sind."
type: docs
weight: 760
url: /de/net/groupdocs.viewer.interfaces/ipagestreamfactory/
---

## IPageStreamFactory interface

Definiert die Methoden, die zum Instanziieren und Freigeben des Ausgabeseitestreams erforderlich sind.

```csharp
public interface IPageStreamFactory
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreatePageStream](../../groupdocs.viewer.interfaces/ipagestreamfactory/createpagestream)(int) | Erstellt den Stream, der zum Schreiben der Ausgabedaten der Seite verwendet wird. |
| [ReleasePageStream](../../groupdocs.viewer.interfaces/ipagestreamfactory/releasepagestream)(int, Stream) | Gibt den von [`CreatePageStream`](./createpagestream) Methode erstellten Stream frei. |

### Siehe auch

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
