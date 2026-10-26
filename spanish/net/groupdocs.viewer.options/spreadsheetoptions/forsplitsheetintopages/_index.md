---
title: "ForSplitSheetIntoPages"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Inicializa una instancia de la clase SpreadsheetOptionsgroupdocs.viewer.options/spreadsheetoptions para renderizar la hoja en páginas."
type: docs
weight: 50
url: /es/net/groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages/
---

## ForSplitSheetIntoPages(int) {#forsplitsheetintopages}

Inicializa una instancia de la clase [`SpreadsheetOptions`](../../spreadsheetoptions) para renderizar la hoja en páginas.

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| countRowsPerPage | Int32 | Cantidad de filas a incluir en cada página. |

### Valor devuelto

Nueva instancia de la clase [`SpreadsheetOptions`](../../spreadsheetoptions) para renderizar la hoja en páginas.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando *countRowsPerPage* es igual o menor que cero. |

### Observaciones

Para más detalles, vea la [documentación](https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows).

### Ver también

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForSplitSheetIntoPages(int, int) {#forsplitsheetintopages_1}

Inicializa una instancia de la clase [`SpreadsheetOptions`](../../spreadsheetoptions) para renderizar la hoja en páginas.

```csharp
public static SpreadsheetOptions ForSplitSheetIntoPages(int countRowsPerPage, 
    int countColumnsPerPage)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| countRowsPerPage | Int32 | Cantidad de filas a incluir en cada página. |
| countColumnsPerPage | Int32 | Cantidad de columnas a incluir en cada página. |

### Valor devuelto

Nueva instancia de la clase [`SpreadsheetOptions`](../../spreadsheetoptions) para renderizar la hoja en páginas.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando *countRowsPerPage* es igual o menor que cero. |
| ArgumentException | Se lanza cuando *countColumnsPerPage* es igual o menor que cero. |

### Observaciones

Para más detalles, vea la [documentación](https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns).

### Ver también

* class [SpreadsheetOptions](../../spreadsheetoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
