---
title: PngViewOptions
second_title: Riferimento API GroupDocs.Viewer per .NET
description: Inizializza la nuova istanza diPngViewOptionsgroupdocs.viewer.options/pngviewoptions classe.
type: docs
weight: 10
url: /it/net/groupdocs.viewer.options/pngviewoptions/pngviewoptions/
---
## PngViewOptions(CreatePageStream) {#constructor_1}

Inizializza la nuova istanza di[`PngViewOptions`](../../pngviewoptions) classe.

```csharp
public PngViewOptions(CreatePageStream createPageStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati della pagina di output. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*createPageStream* è zero. |

### Guarda anche

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [PngViewOptions](../../pngviewoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../pngviewoptions)
* assemblea [GroupDocs.Viewer](../../../)

---

## PngViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

Inizializza la nuova istanza di[`PngViewOptions`](../../pngviewoptions) classe.

```csharp
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| createPageStream | CreatePageStream | Il metodo che crea un'istanza del flusso utilizzato per scrivere i dati della pagina di output. |
| releasePageStream | ReleasePageStream | Il metodo che rilascia il flusso creato dal metodo assegnato al delegato a cui è passato*createPageStream* parametro. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*createPageStream* è zero. |
| ArgumentNullException | Lanciato quando*releasePageStream* è zero. |

### Guarda anche

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [PngViewOptions](../../pngviewoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../pngviewoptions)
* assemblea [GroupDocs.Viewer](../../../)

---

## PngViewOptions(IPageStreamFactory) {#constructor_3}

Inizializza la nuova istanza di[`PngViewOptions`](../../pngviewoptions) classe.

```csharp
public PngViewOptions(IPageStreamFactory pageStreamFactory)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | La factory che implementa i metodi per creare e rilasciare il flusso di pagine di output. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*pageStreamFactory* è zero. |

### Guarda anche

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [PngViewOptions](../../pngviewoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../pngviewoptions)
* assemblea [GroupDocs.Viewer](../../../)

---

## PngViewOptions() {#constructor}

Inizializza la nuova istanza di[`PngViewOptions`](../../pngviewoptions) classe.

```csharp
public PngViewOptions()
```

### Osservazioni

Questo costruttore inizializza una nuova istanza di[`PngViewOptions`](../../pngviewoptions) con "p_{0}.png" come formato del percorso file per i file di output. I file di output verranno inseriti nella directory di lavoro corrente dell'applicazione.

### Guarda anche

* class [PngViewOptions](../../pngviewoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../pngviewoptions)
* assemblea [GroupDocs.Viewer](../../../)

---

## PngViewOptions(string) {#constructor_4}

Inizializza la nuova istanza di[`PngViewOptions`](../../pngviewoptions) classe.

```csharp
public PngViewOptions(string filePathFormat)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | String | Il formato del percorso del file, ad esempio 'page_{0}.png'. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Lanciato quando*filePathFormat* è nullo o vuoto. |

### Guarda anche

* class [PngViewOptions](../../pngviewoptions)
* spazio dei nomi [GroupDocs.Viewer.Options](../../pngviewoptions)
* assemblea [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->