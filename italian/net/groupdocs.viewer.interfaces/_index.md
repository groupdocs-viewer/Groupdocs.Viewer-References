---
title: GroupDocs.Viewer.Interfaces
second_title: Riferimento API GroupDocs.Viewer per .NET
description: Lo spazio dei nomi fornisce le interfacce per istanziare e rilasciare il documento di output e le sue risorse.
type: docs
weight: 50
url: /it/net/groupdocs.viewer.interfaces/
---
Lo spazio dei nomi fornisce le interfacce per istanziare e rilasciare il documento di output e le sue risorse.

## Classi

| Classe | Descrizione |
| --- | --- |
| [CreateFileStream](./createfilestream) | Rappresenta il metodo che istanzia il flusso utilizzato per scrivere i dati del file di output. |
| [CreatePageStream](./createpagestream) | Rappresenta il metodo che istanzia il flusso utilizzato per scrivere i dati della pagina di output. |
| [CreateResourceStream](./createresourcestream) | Rappresenta il metodo che istanzia il flusso utilizzato per scrivere i dati della risorsa HTML di output. |
| [CreateResourceUrl](./createresourceurl) | Rappresenta il metodo che crea l'URL per la risorsa HTML. |
| [ReleaseFileStream](./releasefilestream) | Rilascia il flusso che è stato istanziato dal metodo associato a[`CreateFileStream`](../groupdocs.viewer.interfaces/createfilestream) delegato. |
| [ReleasePageStream](./releasepagestream) | Rilascia il flusso che è stato istanziato dal metodo associato a[`CreatePageStream`](../groupdocs.viewer.interfaces/createpagestream) delegato. |
| [ReleaseResourceStream](./releaseresourcestream) | Rilascia il flusso che è stato istanziato dal metodo associato a[`CreateResourceStream`](../groupdocs.viewer.interfaces/createresourcestream) delegato. |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IFileStreamFactory](./ifilestreamfactory) | Definisce i metodi richiesti per creare un'istanza e rilasciare il flusso di file di output. |
| [IPageStreamFactory](./ipagestreamfactory) | Definisce i metodi richiesti per creare un'istanza e rilasciare il flusso della pagina di output. |
| [IResourceStreamFactory](./iresourcestreamfactory) | Definisce i metodi richiesti per creare l'URL della risorsa, istanziare e rilasciare il flusso di risorse HTML di output. |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->