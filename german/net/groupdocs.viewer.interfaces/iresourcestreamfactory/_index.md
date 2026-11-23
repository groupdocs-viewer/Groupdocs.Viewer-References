---
title: "IResourceStreamFactory"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Definiert die Methoden, die für das Erstellen von Ressourcen-URLs, das Instanziieren und Freigeben des Ausgabestreams für HTML-Ressourcen erforderlich sind."
type: docs
weight: 770
url: /de/net/groupdocs.viewer.interfaces/iresourcestreamfactory/
---

## IResourceStreamFactory interface

Definiert die Methoden, die zum Erstellen der Ressourcen-URL, zum Instanziieren und Freigeben des Ausgabestreams für HTML-Ressourcen erforderlich sind.

```csharp
public interface IResourceStreamFactory
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream)(int, Resource) | Erstellt den Stream, der zum Schreiben von Ausgabedaten der HTML-Ressource verwendet wird. |
| [CreateResourceUrl](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourceurl)(int, Resource) | Erstellt die URL für die HTML-Ressource. |
| [ReleaseResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream)(int, Resource, Stream) | Gibt den von der Methode [`CreateResourceStream`](./createresourcestream) erstellten Stream frei. |

### Siehe auch

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
