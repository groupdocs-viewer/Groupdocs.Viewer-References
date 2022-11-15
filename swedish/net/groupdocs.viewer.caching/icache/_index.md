---
title: ICache
second_title: GroupDocs.Viewer för .NET API-referens
description: Definierar metoder som krävs för att lagra renderade dokument och dokumentresurser сache.
type: docs
weight: 30
url: /sv/net/groupdocs.viewer.caching/icache/
---
## ICache interface

Definierar metoder som krävs för att lagra renderade dokument- och dokumentresurser сache.

```csharp
public interface ICache
```

## Metoder

| namn | Beskrivning |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/icache/getkeys)(string) | Returnerar alla nycklar som matchar filter. |
| [Set](../../groupdocs.viewer.caching/icache/set)(string, object) | Infogar en cache-post i cachen. |
| [TryGetValue&lt;TEntry&gt;](../../groupdocs.viewer.caching/icache/trygetvalue)(string, out TEntry) | Hämtar posten som är kopplad till denna nyckel om den finns. |

### Se även

* namnutrymme [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* hopsättning [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->