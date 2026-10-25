---
title: "TryGetValue"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Liefert den mit diesem Schlüssel verknüpften Eintrag, falls vorhanden."
type: docs
weight: 30
url: /de/net/groupdocs.viewer.caching/icache/trygetvalue/
---

## ICache.TryGetValue&lt;TEntry&gt; method

Liefert den mit diesem Schlüssel verknüpften Eintrag, falls vorhanden.

```csharp
public bool TryGetValue<TEntry>(string key, out TEntry value)
```

| Parameter | Beschreibung |
| --- | --- |
| TEntry | Typ des Eintrags. |
| Schlüssel | Ein Schlüssel, der den angeforderten Eintrag identifiziert. |
| value | Der gefundene Wert oder null. |

### Rückgabewert

```csharp
True
```

wenn der Schlüssel gefunden wurde.

### Siehe auch

* interface [ICache](../../icache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
