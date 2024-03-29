---
title: ForEmbeddedResources
second_title: Riferimento API GroupDocs.Viewer per .NET
description: Inizializza una nuova istanza diHtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions classe per il rendering in HTML con risorse incorporate.
type: docs
weight: 10
url: /it/net/groupdocs.viewer.options/htmlviewoptions/forembeddedresources/
---
## ForEmbeddedResources(CreatePageStream) {#forembeddedresources_1}

Inizializza una nuova istanza di[`HtmlViewOptions`](../../htmlviewoptions) classe per il rendering in HTML con risorse incorporate.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati della pagina di output. |

### Valore di ritorno

Nuova istanza di[`HtmlViewOptions`](../../htmlviewoptions) classe per il rendering in HTML con risorse incorporate.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*createPageStream* è zero. |

### Guarda anche

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../htmlviewoptions)
* assemblea [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(CreatePageStream, ReleasePageStream) {#forembeddedresources_2}

Inizializza una nuova istanza di[`HtmlViewOptions`](../../htmlviewoptions) classe per il rendering in HTML con risorse incorporate.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati della pagina di output. |
| releasePageStream | ReleasePageStream | Il metodo che rilascia il flusso creato dal metodo assegnato al delegato passato a*createPageStream* parametro. |

### Valore di ritorno

Nuova istanza di[`HtmlViewOptions`](../../htmlviewoptions) classe per il rendering in HTML con risorse incorporate.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*createPageStream* è zero. |
| ArgumentNullException | Lanciato quando*releasePageStream* è zero. |

### Guarda anche

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../htmlviewoptions)
* assemblea [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(IPageStreamFactory) {#forembeddedresources_3}

Inizializza una nuova istanza di[`HtmlViewOptions`](../../htmlviewoptions) classe per il rendering in HTML con risorse incorporate.

```csharp
public static HtmlViewOptions ForEmbeddedResources(IPageStreamFactory pageStreamFactory)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | La factory che implementa i metodi per la creazione e il rilascio del flusso della pagina di output. |

### Valore di ritorno

Nuova istanza di[`HtmlViewOptions`](../../htmlviewoptions) classe per il rendering in HTML con risorse incorporate.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*pageStreamFactory* è zero. |

### Guarda anche

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../htmlviewoptions)
* assemblea [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources() {#forembeddedresources}

Inizializza una nuova istanza di[`HtmlViewOptions`](../../htmlviewoptions) classe.

```csharp
public static HtmlViewOptions ForEmbeddedResources()
```

### Guarda anche

* class [HtmlViewOptions](../../htmlviewoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../htmlviewoptions)
* assemblea [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(string) {#forembeddedresources_4}

Inizializza una nuova istanza di[`HtmlViewOptions`](../../htmlviewoptions) classe.

```csharp
public static HtmlViewOptions ForEmbeddedResources(string filePathFormat)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | String | Il formato del percorso del file, ad esempio "pagina_{0}.html". |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Lanciato quando*filePathFormat* è nullo o vuoto. |

### Guarda anche

* class [HtmlViewOptions](../../htmlviewoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../htmlviewoptions)
* assemblea [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
