---
title: ForExternalResources
second_title: Riferimento API GroupDocs.Viewer per .NET
description: Inizializza la nuova istanza diHtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions classe per il rendering in HTML con risorse esterne.
type: docs
weight: 20
url: /it/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---
## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Inizializza la nuova istanza di[`HtmlViewOptions`](../../htmlviewoptions) classe per il rendering in HTML con risorse esterne.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati della pagina di output. |
| createResourceStream | CreateResourceStream | Il metodo che rilascia il flusso creato da*createPageStream* metodo. |
| createResourceUrl | CreateResourceUrl | Il metodo che crea l'URL per la risorsa HTML. |

### Valore di ritorno

Nuova istanza di[`HtmlViewOptions`](../../htmlviewoptions) classe per il rendering in HTML con risorse esterne.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*createPageStream* è zero. |
| ArgumentNullException | Lanciato quando*createResourceStream* è zero. |
| ArgumentNullException | Lanciato quando*createResourceUrl* è zero. |

### Guarda anche

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../htmlviewoptions)
* assemblea [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Inizializza la nuova istanza di[`HtmlViewOptions`](../../htmlviewoptions) classe per il rendering in HTML con risorse esterne.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati della pagina di output. |
| createResourceStream | CreateResourceStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati della risorsa HTML di output. |
| createResourceUrl | CreateResourceUrl | Il metodo che crea l'URL per la risorsa HTML. |
| releasePageStream | ReleasePageStream | Il metodo che rilascia il flusso creato dal metodo assegnato al delegato a cui è passato*createPageStream* parametro. |
| releaseResourceStream | ReleaseResourceStream | Il metodo che rilascia il flusso creato dal metodo assegnato al delegato a cui è passato*createResourceStream* parametro. |

### Valore di ritorno

Nuova istanza di[`HtmlViewOptions`](../../htmlviewoptions) classe per il rendering in HTML con risorse esterne.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*createPageStream* è zero. |
| ArgumentNullException | Lanciato quando*createResourceStream* è zero. |
| ArgumentNullException | Lanciato quando*createResourceUrl* è zero. |
| ArgumentNullException | Lanciato quando*releasePageStream* è zero. |
| ArgumentNullException | Lanciato quando*releaseResourceStream* è zero. |

### Guarda anche

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../htmlviewoptions)
* assemblea [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

Inizializza la nuova istanza di[`HtmlViewOptions`](../../htmlviewoptions) classe per il rendering in HTML con risorse esterne.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | La factory che implementa i metodi per creare e rilasciare il flusso di pagine di output. |
| resourceStreamFactory | IResourceStreamFactory | La factory che implementa i metodi richiesti per la creazione dell'URL della risorsa, l'istanziazione e il rilascio del flusso di risorse HTML di output. |

### Valore di ritorno

Nuova istanza di[`HtmlViewOptions`](../../htmlviewoptions) classe per il rendering in HTML con risorse esterne.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*pageStreamFactory* è zero. |
| ArgumentNullException | Lanciato quando*resourceStreamFactory* è zero. |

### Guarda anche

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../htmlviewoptions)
* assemblea [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Inizializza la nuova istanza di[`HtmlViewOptions`](../../htmlviewoptions) classe.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Osservazioni

Questo costruttore inizializza una nuova istanza di[`HtmlViewOptions`](../../htmlviewoptions) - con "p_{0}.html" come formato del percorso file per i file HTML di output; - con "p_{0}_{1}" come formato del percorso file per i file di risorse HTML di output; - con " p_{0}_{1}" come formato URL per le risorse HTML; I file di output verranno inseriti nella directory di lavoro corrente dell'applicazione.

### Guarda anche

* class [HtmlViewOptions](../../htmlviewoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../htmlviewoptions)
* assemblea [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Inizializza la nuova istanza di[`HtmlViewOptions`](../../htmlviewoptions) classe.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | String | Il formato del percorso del file, ad esempio "pagina_{0}.html". |
| resourceFilePathFormat | String | Il formato del percorso del file della risorsa, ad esempio "pagina_{0}/risorsa_{1}". |
| resourceUrlFormat | String | Il formato dell'URL della risorsa, ad esempio "pagina_{0}/risorsa_{1}". |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Lanciato quando*filePathFormat* è nullo o vuoto. |
| ArgumentException | Lanciato quando*resourceFilePathFormat* è nullo o vuoto. |
| ArgumentException | Lanciato quando*resourceUrlFormat* è nullo o vuoto. |

### Guarda anche

* class [HtmlViewOptions](../../htmlviewoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../htmlviewoptions)
* assemblea [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
