---
title: "Rotazione"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Contiene la rotazione della pagina in gradi in senso orario."
type: docs
weight: 45
url: /it/java/com.groupdocs.viewer.options/rotation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Rotation extends Enum<Rotation>
```

Contiene la rotazione della pagina in gradi (orario).


L'enumerazione Rotazione rappresenta diversi angoli di rotazione per una pagina nel componente GroupDocs.Viewer.
Fornisce un insieme di opzioni di rotazione predefinite che possono essere utilizzate per specificare l'angolo di rotazione
per il rendering di una pagina in vari scenari di visualizzazione o conversione di documenti.


Esempio di utilizzo:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();

 pdfViewOptions.rotatePage(1, Rotation.ON_90_DEGREE);
 pdfViewOptions.rotatePage(2, Rotation.ON_180_DEGREE);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Campi

| Campo | Descrizione |
| --- | --- |
|  | [ON_90_DEGREE](#ON-90-DEGREE) | La rotazione della pagina di 90 gradi. |
|
|  | [ON_180_DEGREE](#ON-180-DEGREE) | La rotazione della pagina di 180 gradi. |
|
|  | [ON_270_DEGREE](#ON-270-DEGREE) | La rotazione della pagina di 270 gradi. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### ON_90_DEGREE {#ON-90-DEGREE}
```
public static final Rotation ON_90_DEGREE
```


La rotazione della pagina di 90 gradi.
Questa rotazione rappresenta una rotazione della pagina di 90 gradi in senso orario.


### ON_180_DEGREE {#ON-180-DEGREE}
```
public static final Rotation ON_180_DEGREE
```


La rotazione della pagina di 180 gradi.
Questa rotazione rappresenta una rotazione della pagina di 180 gradi in senso orario.


### ON_270_DEGREE {#ON-270-DEGREE}
```
public static final Rotation ON_270_DEGREE
```


La rotazione della pagina di 270 gradi.
Questa rotazione rappresenta una rotazione della pagina di 270 gradi in senso orario.


### values() {#values--}
```
public static Rotation[] values()
```




**Returns:**
com.groupdocs.viewer.options.Rotation[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Rotation valueOf(String name)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[Rotation](../../com.groupdocs.viewer.options/rotation)
