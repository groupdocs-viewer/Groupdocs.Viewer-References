---
title: "com.groupdocs.viewer.interfaces"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Das Paket bietet Schnittstellen zum Instanziieren und Freigeben des Ausgabedokuments und seiner Ressourcen."
type: docs
weight: 17
url: /de/java/com.groupdocs.viewer.interfaces/
---

Das Paket bietet Schnittstellen zum Instanziieren und Freigeben des Ausgabedokuments und seiner Ressourcen.


Diese Schnittstellen werden verwendet, um die Erstellung und Freigabe von Streams und URLs zu verwalten, die mit der Ausgabedatei, den Seiten und HTML-Ressourcen verbunden sind.

Die wichtigsten Schnittstellen in diesem Paket sind:

* [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) - Represents an interface for instantiating a stream used to write output file data.
* [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) - Defines methods for instantiating and releasing the output file stream.
* [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) - Releases a stream that was instantiated by a method associated with the CreatePageStream interface.


Weitere Details zur Arbeit mit diesen Schnittstellen und zur Anpassung der Ausgabe des Dokuments sowie der Ressourcenverwaltung in GroupDocs.Viewer,
Bitte beziehen Sie sich auf die [GroupDocs.Viewer Documentation](../https://docs.groupdocs.com/viewer/java/).



## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [CreateFileStream](../com.groupdocs.viewer.interfaces/createfilestream) | Stellt eine Schnittstelle dar, die einen Stream erzeugt, der zum Schreiben von Ausgabedateidaten verwendet wird. |
| [CreatePageStream](../com.groupdocs.viewer.interfaces/createpagestream) | Stellt eine Schnittstelle dar, die einen Stream erzeugt, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| [CreateResourceStream](../com.groupdocs.viewer.interfaces/createresourcestream) | Stellt eine Schnittstelle dar, die einen Stream erzeugt, der zum Schreiben von Ausgabedaten für HTML-Ressourcen verwendet wird. |
| [CreateResourceUrl](../com.groupdocs.viewer.interfaces/createresourceurl) | Stellt eine Schnittstelle dar, die eine URL für eine HTML-Ressource erstellt. |
| [FileReader](../com.groupdocs.viewer.interfaces/filereader) | Deklariert eine Schnittstelle zum Lesen eines Dateistreams. |
| [FileStreamFactory](../com.groupdocs.viewer.interfaces/filestreamfactory) | Definiert Methoden, die für das Instanziieren und Freigeben eines Ausgabedateistreams erforderlich sind. |
| [PageStreamFactory](../com.groupdocs.viewer.interfaces/pagestreamfactory) | Definiert die Methoden, die für das Instanziieren und Freigeben eines Ausgabeseitestreams erforderlich sind. |
| [ReleaseFileStream](../com.groupdocs.viewer.interfaces/releasefilestream) | Gibt eine Schnittstelle frei, die durch die mit der CreateFileStream‑Schnittstelle verbundene Methode instanziiert wurde. |
| [ReleasePageStream](../com.groupdocs.viewer.interfaces/releasepagestream) | Gibt einen Stream frei, der durch die mit der CreatePageStream‑Schnittstelle verbundene Methode instanziiert wurde. |
| [ReleaseResourceStream](../com.groupdocs.viewer.interfaces/releaseresourcestream) | Gibt einen Stream frei, der durch die mit der CreateResourceStream‑Schnittstelle verbundene Methode instanziiert wurde. |
| [ResourceStreamFactory](../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Definiert die Methoden, die für das Erstellen einer Ressourcen‑URL, das Instanziieren und Freigeben eines Ausgabestreams für HTML‑Ressourcen erforderlich sind. |
