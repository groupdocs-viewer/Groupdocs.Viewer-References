---
title: IPageStreamFactory
second_title: Riferimento API GroupDocs.Viewer per .NET
description: Definisce i metodi richiesti per creare unistanza e rilasciare il flusso della pagina di output.
type: docs
weight: 170
url: /it/net/groupdocs.viewer.interfaces/ipagestreamfactory/
---
## IPageStreamFactory interface

Definisce i metodi richiesti per creare un'istanza e rilasciare il flusso della pagina di output.

```csharp
public interface IPageStreamFactory
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CreatePageStream](../../groupdocs.viewer.interfaces/ipagestreamfactory/createpagestream)(int) | Crea il flusso utilizzato per scrivere i dati della pagina di output. |
| [ReleasePageStream](../../groupdocs.viewer.interfaces/ipagestreamfactory/releasepagestream)(int, Stream) | Rilascia il flusso creato da[`CreatePageStream`](./createpagestream) metodo. |

### Guarda anche

* spazio dei nomi [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assemblea [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->