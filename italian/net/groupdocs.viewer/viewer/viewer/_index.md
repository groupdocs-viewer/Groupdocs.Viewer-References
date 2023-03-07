---
title: Viewer
second_title: Riferimento API GroupDocs.Viewer per .NET
description: Inizializza una nuova istanza diViewergroupdocs.viewer/viewer classe.
type: docs
weight: 10
url: /it/net/groupdocs.viewer/viewer/viewer/
---
## Viewer(Func&lt;Stream&gt;) {#constructor}

Inizializza una nuova istanza di[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| getFileStream | Func`1 | Il metodo che restituisce un flusso leggibile. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*getFileStream* è zero. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Viewer: [Formati di documenti supportati da GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Viewer per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Guarda anche

* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

Inizializza una nuova istanza di[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| getFileStream | Func`1 | Il metodo che restituisce un flusso leggibile. |
| getLoadOptions | Func`1 | I metodi che restituiscono le opzioni di caricamento del documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*getFileStream* è zero. |
| ArgumentNullException | Lanciato quando*getLoadOptions* è zero. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Viewer: [Formati di documenti supportati da GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Viewer per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Ulteriori informazioni sul caricamento di documenti crittografati e sulla visualizzazione di file da archivi di terze parti con GroupDocs.Viewer per .NET: [Come caricare e visualizzare il documento con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Guarda anche

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

Inizializza una nuova istanza di[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| getFileStream | Func`1 | Il metodo che restituisce un flusso leggibile. |
| settings | ViewerSettings | Le impostazioni del visualizzatore. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*getFileStream* è zero. |
| ArgumentNullException | Lanciato quando*settings* è zero. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Viewer: [Formati di documenti supportati da GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Viewer per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Guarda anche

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

Inizializza una nuova istanza di[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| getFileStream | Func`1 | Il metodo che restituisce un flusso leggibile. |
| getLoadOptions | Func`1 | I metodi che restituiscono le opzioni di caricamento del documento. |
| settings | ViewerSettings | Le impostazioni del visualizzatore. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*getFileStream* è zero. |
| ArgumentNullException | Lanciato quando*getLoadOptions* è zero. |
| ArgumentNullException | Lanciato quando*settings* è zero. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Viewer: [Formati di documenti supportati da GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Viewer per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Ulteriori informazioni sul caricamento di documenti crittografati e sulla visualizzazione di file da archivi di terze parti con GroupDocs.Viewer per .NET: [Come caricare e visualizzare il documento con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Guarda anche

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

Inizializza una nuova istanza di[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso di file. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*stream* è zero. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Viewer: [Formati di documenti supportati da GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Viewer per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Guarda anche

* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

Inizializza una nuova istanza di[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso di file. |
| leaveOpen | Boolean | VERO per lasciare il flusso aperto dopo l'eliminazione dell'oggetto Viewer; Altrimenti,falso. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*stream* è zero. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Viewer: [Formati di documenti supportati da GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Viewer per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Guarda anche

* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

Inizializza una nuova istanza di[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso di file. |
| loadOptions | LoadOptions | Le opzioni di caricamento del documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*stream* è zero. |
| ArgumentNullException | Lanciato quando*loadOptions* è zero. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Viewer: [Formati di documenti supportati da GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Viewer per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Ulteriori informazioni sul caricamento di documenti crittografati e sulla visualizzazione di file da archivi di terze parti con GroupDocs.Viewer per .NET: [Come caricare e visualizzare il documento con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Guarda anche

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

Inizializza una nuova istanza di[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso di file. |
| loadOptions | LoadOptions | Le opzioni di caricamento del documento. |
| leaveOpen | Boolean | VERO per lasciare il flusso aperto dopo l'eliminazione dell'oggetto Viewer; Altrimenti,falso. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*stream* è zero. |
| ArgumentNullException | Lanciato quando*loadOptions* è zero. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Viewer: [Formati di documenti supportati da GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Viewer per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Ulteriori informazioni sul caricamento di documenti crittografati e sulla visualizzazione di file da archivi di terze parti con GroupDocs.Viewer per .NET: [Come caricare e visualizzare il documento con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Guarda anche

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

Inizializza una nuova istanza di[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso di file. |
| settings | ViewerSettings | Le impostazioni del visualizzatore. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*stream* è zero. |
| ArgumentNullException | Lanciato quando*settings* è zero. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Viewer: [Formati di documenti supportati da GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Viewer per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Guarda anche

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

Inizializza una nuova istanza di[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso di file. |
| settings | ViewerSettings | Le impostazioni del visualizzatore. |
| leaveOpen | Boolean | VERO per lasciare il flusso aperto dopo l'eliminazione dell'oggetto Viewer; Altrimenti,falso. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*stream* è zero. |
| ArgumentNullException | Lanciato quando*settings* è zero. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Viewer: [Formati di documenti supportati da GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Viewer per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Guarda anche

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

Inizializza una nuova istanza di[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso di file. |
| loadOptions | LoadOptions | Le opzioni di caricamento del documento. |
| settings | ViewerSettings | Le impostazioni del visualizzatore. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*stream* è zero. |
| ArgumentNullException | Lanciato quando*loadOptions* è zero. |
| ArgumentNullException | Lanciato quando*settings* è zero. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Viewer: [Formati di documenti supportati da GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Viewer per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Ulteriori informazioni sul caricamento di documenti crittografati e sulla visualizzazione di file da archivi di terze parti con GroupDocs.Viewer per .NET: [Come caricare e visualizzare il documento con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Guarda anche

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

Inizializza una nuova istanza di[`Viewer`](../../viewer) classe.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Il flusso di file. |
| loadOptions | LoadOptions | Le opzioni di caricamento del documento. |
| settings | ViewerSettings | Le impostazioni del visualizzatore. |
| leaveOpen | Boolean | VERO per lasciare il flusso aperto dopo l'eliminazione dell'oggetto Viewer; Altrimenti,falso. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*stream* è zero. |
| ArgumentNullException | Lanciato quando*loadOptions* è zero. |
| ArgumentNullException | Lanciato quando*settings* è zero. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Viewer: [Formati di documenti supportati da GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Viewer per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Ulteriori informazioni sul caricamento di documenti crittografati e sulla visualizzazione di file da archivi di terze parti con GroupDocs.Viewer per .NET: [Come caricare e visualizzare il documento con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Guarda anche

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

Inizializza una nuova istanza di[`Viewer`](../../viewer) classe.

```csharp
public Viewer(string filePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Percorso del file di cui eseguire il rendering. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Lanciato quando*filePath* è nullo o vuoto. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Viewer: [Formati di documenti supportati da GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Viewer per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Guarda anche

* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

Inizializza una nuova istanza di[`Viewer`](../../viewer) classe.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Percorso del file di cui eseguire il rendering. |
| settings | ViewerSettings | Le impostazioni del visualizzatore. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Lanciato quando*filePath* è nullo o vuoto. |
| ArgumentNullException | Lanciato quando*settings* è zero. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Viewer: [Formati di documenti supportati da GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Viewer per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Guarda anche

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

Inizializza una nuova istanza di[`Viewer`](../../viewer) classe.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Percorso del file di cui eseguire il rendering. |
| loadOptions | LoadOptions | Le opzioni utilizzate per aprire il file. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Lanciato quando*filePath* è nullo o vuoto. |
| ArgumentNullException | Lanciato quando*loadOptions* è zero. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Viewer: [Formati di documenti supportati da GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Viewer per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Ulteriori informazioni sul caricamento di documenti crittografati e sulla visualizzazione di file da archivi di terze parti con GroupDocs.Viewer per .NET: [Come caricare e visualizzare il documento con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Guarda anche

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

Inizializza una nuova istanza di[`Viewer`](../../viewer) classe.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Percorso del file di cui eseguire il rendering. |
| loadOptions | LoadOptions | Le opzioni utilizzate per aprire il file. |
| settings | ViewerSettings | Le impostazioni del visualizzatore. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Lanciato quando*filePath* è nullo o vuoto. |
| ArgumentNullException | Lanciato quando*loadOptions* è zero. |
| ArgumentNullException | Lanciato quando*settings* è zero. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sui tipi di file supportati da GroupDocs.Viewer: [Formati di documenti supportati da GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Ulteriori informazioni su GroupDocs.Viewer per le funzionalità .NET: [Guida per sviluppatori](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Ulteriori informazioni sul caricamento di documenti crittografati e sulla visualizzazione di file da archivi di terze parti con GroupDocs.Viewer per .NET: [Come caricare e visualizzare il documento con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Guarda anche

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
