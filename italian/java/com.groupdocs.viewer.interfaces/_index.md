---
title: "com.groupdocs.viewer.interfaces"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Il pacchetto fornisce interfacce per istanziare e rilasciare il documento di output e le sue risorse."
type: docs
weight: 17
url: /it/java/com.groupdocs.viewer.interfaces/
---

Il pacchetto fornisce interfacce per istanziare e rilasciare il documento di output e le sue risorse.


Queste interfacce sono usate per gestire la creazione e il rilascio di stream e URL associati al file di output, alle pagine e alle risorse HTML.

Le principali interfacce in questo pacchetto sono:

* [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) - Represents an interface for instantiating a stream used to write output file data.
* [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) - Defines methods for instantiating and releasing the output file stream.
* [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) - Releases a stream that was instantiated by a method associated with the CreatePageStream interface.


Per ulteriori dettagli su come lavorare con queste interfacce e personalizzare il documento di output e la gestione delle risorse in GroupDocs.Viewer,
Si prega di fare riferimento alla [GroupDocs.Viewer Documentation](../https://docs.groupdocs.com/viewer/java/).



## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [CreateFileStream](../com.groupdocs.viewer.interfaces/createfilestream) | Rappresenta un'interfaccia che istanzia uno stream utilizzato per scrivere i dati del file di output. |
| [CreatePageStream](../com.groupdocs.viewer.interfaces/createpagestream) | Rappresenta un'interfaccia che istanzia uno stream utilizzato per scrivere i dati della pagina di output. |
| [CreateResourceStream](../com.groupdocs.viewer.interfaces/createresourcestream) | Rappresenta un'interfaccia che istanzia uno stream utilizzato per scrivere i dati della risorsa HTML di output. |
| [CreateResourceUrl](../com.groupdocs.viewer.interfaces/createresourceurl) | Rappresenta un'interfaccia che crea un URL per una risorsa HTML. |
| [FileReader](../com.groupdocs.viewer.interfaces/filereader) | Dichiara un'interfaccia per la lettura di uno stream di file. |
| [FileStreamFactory](../com.groupdocs.viewer.interfaces/filestreamfactory) | Definisce i metodi richiesti per istanziare e rilasciare uno stream di file di output. |
| [PageStreamFactory](../com.groupdocs.viewer.interfaces/pagestreamfactory) | Definisce i metodi richiesti per istanziare e rilasciare uno stream di pagina di output. |
| [ReleaseFileStream](../com.groupdocs.viewer.interfaces/releasefilestream) | Rilascia un'interfaccia che è stata istanziata dal metodo associato all'interfaccia CreateFileStream. |
| [ReleasePageStream](../com.groupdocs.viewer.interfaces/releasepagestream) | Rilascia uno stream che è stato istanziato dal metodo associato all'interfaccia CreatePageStream. |
| [ReleaseResourceStream](../com.groupdocs.viewer.interfaces/releaseresourcestream) | Rilascia uno stream che è stato istanziato dal metodo associato all'interfaccia CreateResourceStream. |
| [ResourceStreamFactory](../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Definisce i metodi richiesti per creare un URL di risorsa, istanziare e rilasciare uno stream di risorsa HTML di output. |
