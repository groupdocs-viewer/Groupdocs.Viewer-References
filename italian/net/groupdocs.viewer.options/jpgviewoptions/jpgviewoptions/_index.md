---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer per .NET API Reference"
description: "Inizializza un'istanza della classe JpgViewOptionsgroupdocs.viewer.options/jpgviewoptions."
type: docs
weight: 10
url: /it/net/groupdocs.viewer.options/jpgviewoptions/jpgviewoptions/
---

## JpgViewOptions(CreatePageStream) {#constructor_1}

Inizializza un'istanza della classe [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(CreatePageStream createPageStream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che istanzia uno stream utilizzato per scrivere i dati della pagina di output. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *createPageStream* è null. |

### Osservazioni

Per l'esempio di codice, vedere la [documentazione](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Vedi anche

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

Inizializza un'istanza della classe [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che istanzia uno stream utilizzato per scrivere i dati della pagina di output. |
| releasePageStream | ReleasePageStream | Il metodo che rilascia uno stream creato dal metodo assegnato al delegato passato al parametro *createPageStream*. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *createPageStream* è null. |
| ArgumentNullException | Generata quando *releasePageStream* è null. |

### Osservazioni

Per l'esempio di codice, vedere la [documentazione](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Vedi anche

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(IPageStreamFactory) {#constructor_3}

Inizializza un'istanza della classe [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(IPageStreamFactory pageStreamFactory)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | La factory che implementa i metodi per creare e rilasciare lo stream della pagina di output. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generata quando *pageStreamFactory* è null. |

### Osservazioni

Per l'esempio di codice, vedere la [documentazione](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Vedi anche

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions() {#constructor}

Inizializza un'istanza della classe [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions()
```

### Osservazioni

Questo costruttore inizializza un'istanza di [`JpgViewOptions`](../../jpgviewoptions) con "p_{0}.jpg" come formato del percorso file per i file di output. I file di output vengono collocati nella directory di lavoro corrente dell'applicazione.

Per l'esempio di codice, vedere la [documentazione](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Vedi anche

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(string) {#constructor_4}

Inizializza un'istanza della classe [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(string filePathFormat)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| filePathFormat | Stringa | Il formato del percorso file, ad es. 'page_{0}.jpg'. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato quando *filePathFormat* è nullo o vuoto. |

### Osservazioni

Per l'esempio di codice, vedere la [documentazione](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Vedi anche

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
