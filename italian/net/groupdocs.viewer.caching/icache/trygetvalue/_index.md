---
title: TryGetValue
second_title: Riferimento API GroupDocs.Viewer per .NET
description: Ottiene la voce associata a questa chiave se presente.
type: docs
weight: 30
url: /it/net/groupdocs.viewer.caching/icache/trygetvalue/
---
## ICache.TryGetValue&lt;TEntry&gt; method

Ottiene la voce associata a questa chiave se presente.

```csharp
public bool TryGetValue<TEntry>(string key, out TEntry value)
```

| Parametro | Descrizione |
| --- | --- |
| TEntry | Tipo di ingresso. |
| key | Una chiave che identifica la voce richiesta. |
| value | Il valore individuato o null. |

### Valore di ritorno

se la chiave è stata trovata.

```csharp
True
```

### Guarda anche

* interface [ICache](../../icache)
* spazio dei nomi [GroupDocs.Viewer.Caching](../../icache)
* assemblea [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
