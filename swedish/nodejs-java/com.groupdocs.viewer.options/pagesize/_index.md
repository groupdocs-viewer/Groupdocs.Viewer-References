---
title: "PageSize"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Sidans storlek."
type: docs
weight: 42
url: /sv/nodejs-java/com.groupdocs.viewer.options/pagesize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PageSize extends Enum<PageSize>
```

Sidans storlek.

Enumen PageSize representerar olika sidstorlekar i GroupDocs.Viewer-komponenten. Den tillhandahåller en uppsättning fördefinierade sidstorlekar som kan användas för att specificera dimensionerna på en sida i olika dokumentrenderingsscenarier.

Exempel på användning:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = htmlViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Fält

| Fält | Beskrivning |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | Standard, ospecificerad sidstorlek. |
| [LETTER](#LETTER) | Storleken på Letter-sidan i punkter är 792 x 612. |
| [LEDGER](#LEDGER) | Storleken på A0-sidan i punkter är 3371 x 2384. |
| [A0](#A0) | Storleken på A1-sidan i punkter är 2384 x 1685. |
| [A1](#A1) | Storleken på A2-sidan i punkter är 1684 x 1190. |
| [A2](#A2) | Storleken på A3-sidan i punkter är 1190 x 842. |
| [A3](#A3) | Storleken på A3-sidan i punkter är 1190 x 842. |
| [A4](#A4) | Storleken på A4-sidan i punkter är 842 x 595. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final PageSize UNSPECIFIED
```


Standard, ospecificerad sidstorlek. Denna storlek används när ingen specifik sidstorlek anges.

### LETTER {#LETTER}
```
public static final PageSize LETTER
```


Storleken på Letter-sidan i punkter är 792 x 612. Denna sidstorlek används vanligtvis för brev och dokument i Nordamerika.

### LEDGER {#LEDGER}
```
public static final PageSize LEDGER
```


Storleken på A0-sidan i punkter är 3371 x 2384. Denna stora sidstorlek är en del av den internationella standarden ISO 216.

### A0 {#A0}
```
public static final PageSize A0
```


Storleken på A1-sidan i punkter är 2384 x 1685. Denna sidstorlek är en del av den internationella standarden ISO 216.

### A1 {#A1}
```
public static final PageSize A1
```


Storleken på A2-sidan i punkter är 1684 x 1190. Denna sidstorlek är en del av den internationella standarden ISO 216.

### A2 {#A2}
```
public static final PageSize A2
```


Storleken på A3-sidan i punkter är 1190 x 842. Denna sidstorlek är en del av den internationella standarden ISO 216.

### A3 {#A3}
```
public static final PageSize A3
```


Storleken på A3-sidan i punkter är 1190 x 842. Denna sidstorlek är en del av den internationella standarden ISO 216.

### A4 {#A4}
```
public static final PageSize A4
```


Storleken på A4-sidan i punkter är 842 x 595. Denna sidstorlek är en del av den internationella standarden ISO 216.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize)
