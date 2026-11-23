---
title: "ForExternalResources"
second_title: "GroupDocs.Viewer per .NET API Reference"
description: "Inizializza un'istanza della classe HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions per il rendering in HTML con risorse esterne."
type: docs
weight: 20
url: /it/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Inizializza un'istanza della classe [`HtmlViewOptions`](../../htmlviewoptions) per il rendering in HTML con risorse esterne.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che istanzia lo stream utilizzato per scrivere i dati della pagina di output. |
| createResourceStream | CreateResourceStream | Il metodo che rilascia lo stream creato dal metodo *createPageStream*. |
| createResourceUrl | CreateResourceUrl | Il metodo che crea l'URL per la risorsa HTML. |

### Valore restituito

Nuova istanza della classe [`HtmlViewOptions`](../../htmlviewoptions) per il rendering in HTML con risorse esterne.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *createPageStream* è null. |
| ArgumentNullException | Generata quando *createResourceStream* è null. |
| ArgumentNullException | Generata quando *createResourceUrl* è null. |

### Osservazioni

Per l'esempio di codice, vedere la [documentazione](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Vedi anche

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Inizializza un'istanza della classe [`HtmlViewOptions`](../../htmlviewoptions) per il rendering in HTML con risorse esterne.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che istanzia lo stream utilizzato per scrivere i dati della pagina di output. |
| createResourceStream | CreateResourceStream | Il metodo che istanzia lo stream usato per scrivere i dati della risorsa HTML di output. |
| createResourceUrl | CreateResourceUrl | Il metodo che crea l'URL per la risorsa HTML. |
| releasePageStream | ReleasePageStream | Il metodo che rilascia lo stream creato dal metodo assegnato al delegato passato al parametro *createPageStream*. |
| releaseResourceStream | ReleaseResourceStream | Il metodo che rilascia lo stream creato dal metodo assegnato al delegato passato al parametro *createResourceStream*. |

### Valore restituito

Nuova istanza della classe [`HtmlViewOptions`](../../htmlviewoptions) per il rendering in HTML con risorse esterne.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *createPageStream* è null. |
| ArgumentNullException | Generata quando *createResourceStream* è null. |
| ArgumentNullException | Generata quando *createResourceUrl* è null. |
| ArgumentNullException | Generata quando *releasePageStream* è null. |
| ArgumentNullException | Generata quando *releaseResourceStream* è null. |

### Osservazioni

Per l'esempio di codice, vedere la [documentazione](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Vedi anche

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

Inizializza un'istanza della classe [`HtmlViewOptions`](../../htmlviewoptions) per il rendering in HTML con risorse esterne.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | La factory che implementa i metodi per creare e rilasciare lo stream della pagina di output. |
| resourceStreamFactory | IResourceStreamFactory | La factory che implementa i metodi necessari per creare l'URL della risorsa, istanziare e rilasciare lo stream della risorsa HTML di output. |

### Valore restituito

Nuova istanza della classe [`HtmlViewOptions`](../../htmlviewoptions) per il rendering in HTML con risorse esterne.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *pageStreamFactory* è null. |
| ArgumentNullException | Generata quando *resourceStreamFactory* è null. |

### Osservazioni

Per l'esempio di codice, vedere la [documentazione](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Vedi anche

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Inizializza un'istanza della classe [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Osservazioni

Questo costruttore inizializza un'istanza della classe [`HtmlViewOptions`](../../htmlviewoptions)

* with "p_{0}.html" as file path format for the output HTML files
* with "p_{0}_{1}" as file path format for the output HTML-resource files
* with "p_{0}_{1}" as URL format for HTML-resources

I file di output saranno collocati nella directory di lavoro corrente dell'applicazione.

Per l'esempio di codice, vedere la [documentazione](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Vedi anche

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Inizializza un'istanza della classe [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| filePathFormat | Stringa | Il formato del percorso file, ad es. 'page_{0}.html'. |
| resourceFilePathFormat | Stringa | Il formato del percorso del file di risorsa, ad es. 'page_{0}/resource_{1}'. |
| resourceUrlFormat | Stringa | Il formato dell'URL della risorsa, ad es. 'page_{0}/resource_{1}'. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato quando *filePathFormat* è nullo o vuoto. |
| ArgumentException | Generato quando *resourceFilePathFormat* è nullo o vuoto. |
| ArgumentException | Generato quando *resourceUrlFormat* è nullo o vuoto. |

### Osservazioni

Per l'esempio di codice, vedere la [documentazione](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Vedi anche

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
