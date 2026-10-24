---
title: "Position"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Definisce la posizione della filigrana."
type: docs
weight: 43
url: /it/java/com.groupdocs.viewer.options/position/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Position extends Enum<Position>
```

Definisce la posizione della filigrana.


L'enumerazione Position rappresenta diverse posizioni per un watermark nel componente GroupDocs.Viewer.
Fornisce un insieme di posizioni predefinite che possono essere utilizzate per specificare il posizionamento di un watermark
su un documento o immagine durante il processo di rendering.


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


## Campi

| Campo | Descrizione |
| --- | --- |
|  | [DIAGONAL](#DIAGONAL) | La posizione diagonale. |
|
|  | [TOP_LEFT](#TOP-LEFT) | La posizione in alto a sinistra. |
|
|  | [TOP_CENTER](#TOP-CENTER) | La posizione al centro superiore. |
|
|  | [TOP_RIGHT](#TOP-RIGHT) | La posizione in alto a destra. |
|
|  | [BOTTOM_LEFT](#BOTTOM-LEFT) | La posizione in basso a sinistra. |
|
|  | [BOTTOM_CENTER](#BOTTOM-CENTER) | La posizione al centro inferiore. |
|
|  | [BOTTOM_RIGHT](#BOTTOM-RIGHT) | La posizione in basso a destra. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### DIAGONAL {#DIAGONAL}
```
public static final Position DIAGONAL
```


La posizione diagonale.
Questa posizione rappresenta un allineamento o posizionamento diagonale.


### TOP_LEFT {#TOP-LEFT}
```
public static final Position TOP_LEFT
```


La posizione in alto a sinistra.
Questa posizione rappresenta un allineamento o posizionamento nell'angolo in alto a sinistra.


### TOP_CENTER {#TOP-CENTER}
```
public static final Position TOP_CENTER
```


La posizione al centro superiore.
Questa posizione rappresenta un allineamento o posizionamento al centro superiore.


### TOP_RIGHT {#TOP-RIGHT}
```
public static final Position TOP_RIGHT
```


La posizione in alto a destra.
Questa posizione rappresenta un allineamento o posizionamento nell'angolo in alto a destra.


### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final Position BOTTOM_LEFT
```


La posizione in basso a sinistra.
Questa posizione rappresenta un allineamento o posizionamento nell'angolo in basso a sinistra.


### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final Position BOTTOM_CENTER
```


La posizione al centro inferiore.
Questa posizione rappresenta un allineamento o posizionamento al centro inferiore.


### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final Position BOTTOM_RIGHT
```


La posizione in basso a destra.
Questa posizione rappresenta un allineamento o posizionamento nell'angolo in basso a destra.


### values() {#values--}
```
public static Position[] values()
```




**Returns:**
com.groupdocs.viewer.options.Position[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Position valueOf(String name)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.viewer.options/position)
