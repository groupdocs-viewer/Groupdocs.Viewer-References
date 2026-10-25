---
title: "ForEmbeddedResources"
second_title: "GroupDocs.Viewer per .NET API Reference"
description: "Inizializza un'istanza della classe HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions per il rendering in HTML con risorse incorporate."
type: docs
weight: 10
url: /it/net/groupdocs.viewer.options/htmlviewoptions/forembeddedresources/
---

## ForEmbeddedResources(CreatePageStream) {#forembeddedresources_1}

Inizializza un'istanza della classe [`HtmlViewOptions`](../../htmlviewoptions) per il rendering in HTML con risorse incorporate.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che istanzia lo stream utilizzato per scrivere i dati della pagina di output. |

### Valore restituito

Nuova istanza della classe [`HtmlViewOptions`](../../htmlviewoptions) per il rendering in HTML con risorse incorporate.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *createPageStream* è null. |

### Osservazioni

Per l'esempio di codice, vedere la [documentazione](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Vedi anche

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(CreatePageStream, ReleasePageStream) {#forembeddedresources_2}

Inizializza un'istanza della classe [`HtmlViewOptions`](../../htmlviewoptions) per il rendering in HTML con risorse incorporate.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che istanzia lo stream utilizzato per scrivere i dati della pagina di output. |
| releasePageStream | ReleasePageStream | Il metodo che rilascia lo stream creato dal metodo assegnato al delegato passato al parametro *createPageStream*. |

### Valore restituito

Nuova istanza della classe [`HtmlViewOptions`](../../htmlviewoptions) per il rendering in HTML con risorse incorporate.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *createPageStream* è null. |
| ArgumentNullException | Generata quando *releasePageStream* è null. |

### Osservazioni

Per l'esempio di codice, vedere la [documentazione](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Vedi anche

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(IPageStreamFactory) {#forembeddedresources_3}

Inizializza un'istanza della classe [`HtmlViewOptions`](../../htmlviewoptions) per il rendering in HTML con risorse incorporate.

```csharp
public static HtmlViewOptions ForEmbeddedResources(IPageStreamFactory pageStreamFactory)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | La factory che implementa i metodi per creare e rilasciare lo stream della pagina di output. |

### Valore restituito

Nuova istanza della classe [`HtmlViewOptions`](../../htmlviewoptions) per il rendering in HTML con risorse incorporate.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *pageStreamFactory* è null. |

### Osservazioni

Per l'esempio di codice, vedere la [documentazione](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Vedi anche

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources() {#forembeddedresources}

Inizializza un'istanza della classe [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForEmbeddedResources()
```

### Osservazioni

Per l'esempio di codice, vedere la [documentazione](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Vedi anche

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(string) {#forembeddedresources_4}

Inizializza un'istanza della classe [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForEmbeddedResources(string filePathFormat)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| filePathFormat | Stringa | Il formato del percorso file, ad es. 'page_{0}.html'. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato quando *filePathFormat* è nullo o vuoto. |

### Osservazioni

Per l'esempio di codice, vedere la [documentazione](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Vedi anche

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
