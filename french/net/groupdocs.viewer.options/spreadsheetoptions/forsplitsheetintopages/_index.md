---
title: "ForSplitSheetIntoPages"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une instance de la classe SpreadsheetOptionsgroupdocs.viewer.options/spreadsheetoptions pour rendre la feuille en pages."
type: docs
weight: 50
url: /fr/net/groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages/
---

## ForSplitSheetIntoPages(int) {#forsplitsheetintopages}

Initialise une instance de la classe [`SpreadsheetOptions`](../../spreadsheetoptions) pour rendre la feuille en pages.

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| countRowsPerPage | Int32 | Nombre de lignes à inclure dans chaque page. |

### Valeur de retour

Nouvelle instance de la classe [`SpreadsheetOptions`](../../spreadsheetoptions) pour rendre la feuille en pages.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancé lorsque *countRowsPerPage* est égal ou inférieur à zéro. |

### Remarques

Pour plus de détails, voir la [documentation](https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).

### Voir aussi

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForSplitSheetIntoPages(int, int) {#forsplitsheetintopages_1}

Initialise une instance de la classe [`SpreadsheetOptions`](../../spreadsheetoptions) pour rendre la feuille en pages.

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage, 
    int countColumnsPerPage)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| countRowsPerPage | Int32 | Nombre de lignes à inclure dans chaque page. |
| countColumnsPerPage | Int32 | Nombre de colonnes à inclure dans chaque page. |

### Valeur de retour

Nouvelle instance de la classe [`SpreadsheetOptions`](../../spreadsheetoptions) pour rendre la feuille en pages.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancé lorsque *countRowsPerPage* est égal ou inférieur à zéro. |
| ArgumentException | Lancé lorsque *countColumnsPerPage* est égal ou inférieur à zéro. |

### Remarques

Pour plus de détails, voir la [documentation](https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).

### Voir aussi

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
