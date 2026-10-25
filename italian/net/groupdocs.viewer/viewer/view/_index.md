---
title: "View"
second_title: "GroupDocs.Viewer per .NET API Reference"
description: "Crea la visualizzazione di tutte le pagine del documento."
type: docs
weight: 90
url: /it/net/groupdocs.viewer/viewer/view/
---

## View(ViewOptions) {#view}

Crea la visualizzazione di tutte le pagine del documento.

```csharp
public void View(ViewOptions options)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| opzioni | ViewOptions | Le opzioni di visualizzazione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Sollevata quando *options* è nullo. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Generato quando è richiesta una password per aprire il documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Generato quando la password specificata è errata. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Sollevata quando non è stato possibile trovare l'allegato. |

### Osservazioni

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Vedi anche

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Crea la visualizzazione di tutte le pagine del documento.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| opzioni | ViewOptions | Le opzioni di visualizzazione. |
| cancellationToken | CancellationToken | Token di cancellazione per inviare una richiesta di annullamento del processo di visualizzazione corrente. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Sollevata quando *options* è nullo. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Generato quando è richiesta una password per aprire il documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Generato quando la password specificata è errata. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Sollevata quando non è stato possibile trovare l'allegato. |

### Osservazioni

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Vedi anche

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Crea la visualizzazione di pagine specifiche del documento.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| opzioni | ViewOptions | Le opzioni di visualizzazione. |
| pageNumbers | Int32[] | I numeri di pagina da visualizzare. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Sollevata quando *options* è nullo. |
| ArgumentNullException | Generato quando *pageNumbers* è nullo. |
| ArgumentException | Generato quando *pageNumbers* è vuoto. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Generato quando è richiesta una password per aprire il documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Generato quando la password specificata è errata. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Sollevata quando non è stato possibile trovare l'allegato. |

### Osservazioni

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Vedi anche

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Crea la visualizzazione di pagine specifiche del documento.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| opzioni | ViewOptions | Le opzioni di visualizzazione. |
| pageNumbers | CancellationToken | I numeri di pagina da visualizzare. |
| cancellationToken | Int32[] | Token di cancellazione per annullare l'elaborazione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Sollevata quando *options* è nullo. |
| ArgumentNullException | Generato quando *pageNumbers* è nullo. |
| ArgumentException | Generato quando *pageNumbers* è vuoto. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Generato quando è richiesta una password per aprire il documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Generato quando la password specificata è errata. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Sollevata quando non è stato possibile trovare l'allegato. |

### Osservazioni

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Vedi anche

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
