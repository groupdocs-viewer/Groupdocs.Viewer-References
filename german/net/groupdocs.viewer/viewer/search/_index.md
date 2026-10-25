---
title: "Search"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Führt eine Textsuche durch und hebt das Ergebnis hervor, falls es im geladenen Dokument gemäß den geladenen Optionen gefunden wird."
type: docs
weight: 80
url: /de/net/groupdocs.viewer/viewer/search/
---

## Viewer.Search method

Führt eine Textsuche durch und hebt das Ergebnis (falls gefunden) im geladenen Dokument gemäß den geladenen Optionen hervor.

```csharp
public void Search(SearchHighlightOptions options)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| options | SearchHighlightOptions | Such‑ und Hervorhebungsoptionen, dies beinhaltet eine zu suchende Textphrase. Darf nicht `null` sein. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn das *options*-Argument `null` ist. |

### Siehe auch

* class [SearchHighlightOptions](../../../groupdocs.viewer.options/searchhighlightoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
