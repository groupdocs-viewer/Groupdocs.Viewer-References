---
title: View
second_title: Riferimento API GroupDocs.Viewer per .NET
description: Crea la visualizzazione di tutte le pagine del documento.
type: docs
weight: 70
url: /it/net/groupdocs.viewer/viewer/view/
---
## View(ViewOptions) {#view}

Crea la visualizzazione di tutte le pagine del documento.

```csharp
public void View(ViewOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | ViewOptions | Le opzioni di visualizzazione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*options* è zero. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Generato quando è richiesta la password per aprire il documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Generato quando la password specificata non è corretta. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Generato quando non è stato possibile trovare l'allegato. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sulle diverse opzioni di visualizzazione seguendo questa guida: [Come personalizzare l'output di visualizzazione dei documenti utilizzando GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Guarda anche

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Crea la visualizzazione di tutte le pagine del documento.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | ViewOptions | Le opzioni di visualizzazione. |
| cancellationToken | CancellationToken | Token di annullamento per inviare una richiesta di annullamento del processo di visualizzazione corrente. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*options* è zero. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Generato quando è richiesta la password per aprire il documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Generato quando la password specificata non è corretta. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Generato quando non è stato possibile trovare l'allegato. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sulle diverse opzioni di visualizzazione seguendo questa guida: [Come personalizzare l'output di visualizzazione dei documenti utilizzando GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Guarda anche

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Crea la visualizzazione di pagine di documenti specifici.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | ViewOptions | Le opzioni di visualizzazione. |
| pageNumbers | Int32[] | I numeri di pagina da visualizzare. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*options* è zero. |
| ArgumentNullException | Lanciato quando*pageNumbers* è zero. |
| ArgumentException | Lanciato quando*pageNumbers* è vuoto. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Generato quando è richiesta la password per aprire il documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Generato quando la password specificata non è corretta. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Generato quando non è stato possibile trovare l'allegato. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sulle diverse opzioni di visualizzazione seguendo questa guida: [Come personalizzare l'output di visualizzazione dei documenti utilizzando GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Guarda anche

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Crea la visualizzazione di pagine di documenti specifici.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | ViewOptions | Le opzioni di visualizzazione. |
| pageNumbers | CancellationToken | I numeri di pagina da visualizzare. |
| cancellationToken | Int32[] | Token di annullamento per annullare l'elaborazione. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*options* è zero. |
| ArgumentNullException | Lanciato quando*pageNumbers* è zero. |
| ArgumentException | Lanciato quando*pageNumbers* è vuoto. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Generato quando è richiesta la password per aprire il documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Generato quando la password specificata non è corretta. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Generato quando non è stato possibile trovare l'allegato. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni sulle diverse opzioni di visualizzazione seguendo questa guida: [Come personalizzare l'output di visualizzazione dei documenti utilizzando GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Guarda anche

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* spazio dei nomi [GroupDocs.Viewer](../../viewer)
* assemblea [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
