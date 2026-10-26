---
title: "PageSize"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Le dimensioni della pagina."
type: docs
weight: 42
url: /it/nodejs-java/com.groupdocs.viewer.options/pagesize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PageSize extends Enum<PageSize>
```

Le dimensioni della pagina.

L'enumerazione PageSize rappresenta diverse dimensioni di pagina nel componente GroupDocs.Viewer. Fornisce un insieme di dimensioni di pagina predefinite che possono essere utilizzate per specificare le dimensioni di una pagina in vari scenari di rendering dei documenti.

Esempio di utilizzo:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = htmlViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Campi

| Campo | Descrizione |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | La dimensione di pagina predefinita, non specificata. |
| [LETTER](#LETTER) | La dimensione della pagina Letter in punti è 792 x 612. |
| [LEDGER](#LEDGER) | La dimensione della pagina A0 in punti è 3371 x 2384. |
| [A0](#A0) | La dimensione della pagina A1 in punti è 2384 x 1685. |
| [A1](#A1) | La dimensione della pagina A2 in punti è 1684 x 1190. |
| [A2](#A2) | La dimensione della pagina A3 in punti è 1190 x 842. |
| [A3](#A3) | La dimensione della pagina A3 in punti è 1190 x 842. |
| [A4](#A4) | La dimensione della pagina A4 in punti è 842 x 595. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final PageSize UNSPECIFIED
```


La dimensione predefinita, non specificata della pagina. Questa dimensione è usata quando non viene specificata una dimensione di pagina.

### LETTER {#LETTER}
```
public static final PageSize LETTER
```


La dimensione della pagina Letter in punti è 792 x 612. Questa dimensione di pagina è comunemente usata per lettere e documenti in Nord America.

### LEDGER {#LEDGER}
```
public static final PageSize LEDGER
```


La dimensione della pagina A0 in punti è 3371 x 2384. Questa grande dimensione di pagina fa parte dello standard internazionale ISO 216.

### A0 {#A0}
```
public static final PageSize A0
```


La dimensione della pagina A1 in punti è 2384 x 1685. Questa dimensione di pagina fa parte dello standard internazionale ISO 216.

### A1 {#A1}
```
public static final PageSize A1
```


La dimensione della pagina A2 in punti è 1684 x 1190. Questa dimensione di pagina fa parte dello standard internazionale ISO 216.

### A2 {#A2}
```
public static final PageSize A2
```


La dimensione della pagina A3 in punti è 1190 x 842. Questa dimensione di pagina fa parte dello standard internazionale ISO 216.

### A3 {#A3}
```
public static final PageSize A3
```


La dimensione della pagina A3 in punti è 1190 x 842. Questa dimensione di pagina fa parte dello standard internazionale ISO 216.

### A4 {#A4}
```
public static final PageSize A4
```


La dimensione della pagina A4 in punti è 842 x 595. Questa dimensione di pagina fa parte dello standard internazionale ISO 216.

### values() {#values--}
```
public static PageSize[] values()
```




**Returns:**
com.groupdocs.viewer.options.PageSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PageSize valueOf(String name)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize)
