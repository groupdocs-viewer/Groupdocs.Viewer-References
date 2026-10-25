---
title: "GroupDocs.Viewer.Interfaces"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Der Namespace stellt Schnittstellen bereit, um Ausgabedokumente und deren Ressourcen zu instanziieren und freizugeben."
type: docs
weight: 60
url: /de/net/groupdocs.viewer.interfaces/
---

Der Namespace stellt Schnittstellen bereit, um Ausgabedokumente und deren Ressourcen zu instanziieren und freizugeben.

## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [CreateFileStream](./createfilestream) | Stellt die Methode dar, die den Stream erzeugt, der zum Schreiben von Ausgabedateidaten verwendet wird. |
| [CreatePageStream](./createpagestream) | Stellt die Methode dar, die den Stream erzeugt, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| [CreateResourceStream](./createresourcestream) | Stellt die Methode dar, die den Stream erzeugt, der zum Schreiben von HTML-Ressourcendaten der Ausgabe verwendet wird. |
| [CreateResourceUrl](./createresourceurl) | Stellt die Methode dar, die eine URL für die HTML-Ressource erstellt. |
| [ReleaseFileStream](./releasefilestream) | Gibt den Stream frei, der von der mit dem Delegaten [`CreateFileStream`](../groupdocs.viewer.interfaces/createfilestream) verknüpften Methode instanziiert wurde. |
| [ReleasePageStream](./releasepagestream) | Gibt den Stream frei, der von der mit dem Delegaten [`CreatePageStream`](../groupdocs.viewer.interfaces/createpagestream) verknüpften Methode instanziiert wurde. |
| [ReleaseResourceStream](./releaseresourcestream) | Gibt den Stream frei, der von der mit dem Delegaten [`CreateResourceStream`](../groupdocs.viewer.interfaces/createresourcestream) verknüpften Methode instanziiert wurde. |
## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IFileStreamFactory](./ifilestreamfactory) | Definiert die Methoden, die zum Instanziieren und Freigeben des Ausgabedateistreams erforderlich sind. |
| [IPageStreamFactory](./ipagestreamfactory) | Definiert die Methoden, die zum Instanziieren und Freigeben des Ausgabeseitestreams erforderlich sind. |
| [IResourceStreamFactory](./iresourcestreamfactory) | Definiert die Methoden, die zum Erstellen der Ressourcen-URL, zum Instanziieren und Freigeben des Ausgabestreams für HTML-Ressourcen erforderlich sind. |

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
