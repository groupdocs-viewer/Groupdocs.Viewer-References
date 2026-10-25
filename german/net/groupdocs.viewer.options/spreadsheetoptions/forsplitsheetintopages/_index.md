---
title: "ForSplitSheetIntoPages"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Initialisiert eine Instanz der SpreadsheetOptionsgroupdocs.viewer.options/spreadsheetoptions Klasse zum Rendern des Blatts in Seiten."
type: docs
weight: 50
url: /de/net/groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages/
---

## ForSplitSheetIntoPages(int) {#forsplitsheetintopages}

Initialisiert eine Instanz der [`SpreadsheetOptions`](../../spreadsheetoptions) Klasse zum Rendern des Blatts in Seiten.

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| countRowsPerPage | Int32 | Anzahl der Zeilen, die in jede Seite aufgenommen werden sollen. |

### Rückgabewert

Neue Instanz der [`SpreadsheetOptions`](../../spreadsheetoptions) Klasse zum Rendern des Blatts in Seiten.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *countRowsPerPage* gleich oder kleiner als Null ist. |

### Bemerkungen

Weitere Details finden Sie in der [Dokumentation](https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).

### Siehe auch

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForSplitSheetIntoPages(int, int) {#forsplitsheetintopages_1}

Initialisiert eine Instanz der [`SpreadsheetOptions`](../../spreadsheetoptions) Klasse zum Rendern des Blatts in Seiten.

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage, 
    int countColumnsPerPage)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| countRowsPerPage | Int32 | Anzahl der Zeilen, die in jede Seite aufgenommen werden sollen. |
| countColumnsPerPage | Int32 | Anzahl der Spalten, die in jede Seite aufgenommen werden sollen. |

### Rückgabewert

Neue Instanz der [`SpreadsheetOptions`](../../spreadsheetoptions) Klasse zum Rendern des Blatts in Seiten.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *countRowsPerPage* gleich oder kleiner als Null ist. |
| ArgumentException | Wird ausgelöst, wenn *countColumnsPerPage* gleich oder kleiner als Null ist. |

### Bemerkungen

Weitere Details finden Sie in der [Dokumentation](https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).

### Siehe auch

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
