---
title: "Size"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Contiene le dimensioni della filigrana."
type: docs
weight: 30
url: /it/java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Contiene le dimensioni della filigrana.


La classe Size rappresenta le dimensioni di una filigrana nel componente GroupDocs.Viewer.
Fornisce opzioni per specificare le dimensioni della filigrana, come larghezza e altezza.


Esempio di utilizzo:

````

 Watermark watermark = new Watermark("Watermark");
 watermark.setPosition(Position.DIAGONAL);
 watermark.setColor(java.awt.Color.GREEN);
 watermark.setSize(Size.HALF_SIZE);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setWatermark(watermark);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [Size(byte relativeSize)](#Size-byte-) | Inizializza una nuova istanza di |
Size
classe.
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [FULL_SIZE](#FULL-SIZE) | Rappresenta la dimensione massima del testo filigrana che si adatta alla pagina. |
|
|  | [HALF_SIZE](#HALF-SIZE) | Rappresenta la metà della dimensione massima del testo filigrana che si adatta alla pagina. |
|
|  | [ONE_THIRD](#ONE-THIRD) | Rappresenta un terzo della dimensione massima del testo filigrana che si adatta alla pagina. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getRelativeSize()](#getRelativeSize--) | Restituisce la dimensione del testo filigrana in percentuale rispetto alla larghezza della pagina. |
|
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


Inizializza una nuova istanza di
Size
classe.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | relativeSize | byte | La dimensione in percentuale rispetto alla dimensione della pagina. |
|

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


Rappresenta la dimensione massima del testo filigrana che si adatta alla pagina.


### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


Rappresenta la metà della dimensione massima del testo filigrana che si adatta alla pagina.


### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


Rappresenta un terzo della dimensione massima del testo filigrana che si adatta alla pagina.


### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


Restituisce la dimensione del testo filigrana in percentuale rispetto alla larghezza della pagina.


**Returns:**
byte - la dimensione del testo filigrana in percentuale.

