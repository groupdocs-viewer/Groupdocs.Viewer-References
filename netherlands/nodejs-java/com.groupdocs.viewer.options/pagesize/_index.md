---
title: "PageSize"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "De grootte van de pagina."
type: docs
weight: 42
url: /nl/nodejs-java/com.groupdocs.viewer.options/pagesize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PageSize extends Enum<PageSize>
```

De grootte van de pagina.

De PageSize‑enum vertegenwoordigt verschillende paginagroottes in de GroupDocs.Viewer‑component. Het biedt een reeks vooraf gedefinieerde paginagroottes die kunnen worden gebruikt om de afmetingen van een pagina te specificeren in diverse scenario's voor documentweergave.

Voorbeeldgebruik:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = htmlViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Velden

| Veld | Beschrijving |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | De standaard, niet‑gespecificeerde paginagrootte. |
| [LETTER](#LETTER) | De afmeting van de Letter-pagina in punten is 792 x 612. |
| [LEDGER](#LEDGER) | De afmeting van de A0-pagina in punten is 3371 x 2384. |
| [A0](#A0) | De afmeting van de A1-pagina in punten is 2384 x 1685. |
| [A1](#A1) | De afmeting van de A2-pagina in punten is 1684 x 1190. |
| [A2](#A2) | De afmeting van de A3-pagina in punten is 1190 x 842. |
| [A3](#A3) | De afmeting van de A3-pagina in punten is 1190 x 842. |
| [A4](#A4) | De afmeting van de A4-pagina in punten is 842 x 595. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final PageSize UNSPECIFIED
```


De standaard, niet-gespecificeerde paginagrootte. Deze grootte wordt gebruikt wanneer geen specifieke paginagrootte is opgegeven.

### LETTER {#LETTER}
```
public static final PageSize LETTER
```


De afmeting van de Letter-pagina in punten is 792 x 612. Deze paginagrootte wordt vaak gebruikt voor brieven en documenten in Noord-Amerika.

### LEDGER {#LEDGER}
```
public static final PageSize LEDGER
```


De afmeting van de A0-pagina in punten is 3371 x 2384. Deze grote paginagrootte maakt deel uit van de internationale norm ISO 216.

### A0 {#A0}
```
public static final PageSize A0
```


De afmeting van de A1-pagina in punten is 2384 x 1685. Deze paginagrootte maakt deel uit van de internationale norm ISO 216.

### A1 {#A1}
```
public static final PageSize A1
```


De afmeting van de A2-pagina in punten is 1684 x 1190. Deze paginagrootte maakt deel uit van de internationale norm ISO 216.

### A2 {#A2}
```
public static final PageSize A2
```


De afmeting van de A3-pagina in punten is 1190 x 842. Deze paginagrootte maakt deel uit van de internationale norm ISO 216.

### A3 {#A3}
```
public static final PageSize A3
```


De afmeting van de A3-pagina in punten is 1190 x 842. Deze paginagrootte maakt deel uit van de internationale norm ISO 216.

### A4 {#A4}
```
public static final PageSize A4
```


De afmeting van de A4-pagina in punten is 842 x 595. Deze paginagrootte maakt deel uit van de internationale norm ISO 216.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize)
