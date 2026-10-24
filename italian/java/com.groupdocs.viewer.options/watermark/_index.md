---
title: "Watermark"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Rappresenta una filigrana di testo."
type: docs
weight: 37
url: /it/java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

Rappresenta una filigrana di testo. Per i dettagli, vedere la [documentazione](../https://docs.groupdocs.com/viewer/net/add-text-watermark/).


La classe Watermark rappresenta una filigrana di testo nel componente GroupDocs.Viewer.
Viene utilizzata per definire e applicare una filigrana all'output renderizzato dei documenti.


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
|  | [Watermark(String text)](#Watermark-java.lang.String-) | Inizializza una nuova istanza di |
Watermark
classe.
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getText()](#getText--) | Restituisce il testo della filigrana. |
|
|  | [getColor()](#getColor--) | Restituisce il colore della filigrana. |
|
|  | [getColorAsHex()](#getColorAsHex--) | Restituisce il colore della filigrana in formato esadecimale. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Imposta il colore della filigrana. |
|
|  | [setColor(String colorName)](#setColor-java.lang.String-) | Imposta il colore della filigrana. |
|
|  | [getPosition()](#getPosition--) | Restituisce la posizione della filigrana. |
|
|  | [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | Imposta la posizione della filigrana. |
|
|  | [getSize()](#getSize--) | Restituisce le dimensioni della filigrana. |
|
|  | [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | Imposta la dimensione della filigrana. |
|
|  | [getFontName()](#getFontName--) | Restituisce il nome del carattere usato per la filigrana. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | Imposta il nome del carattere usato per la filigrana. |
|
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


Inizializza una nuova istanza di
Watermark
classe.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | testo | java.lang.String | Il testo della filigrana. |
|

### getText() {#getText--}
```
public final String getText()
```


Restituisce il testo della filigrana.
Questo metodo recupera il testo della filigrana applicata al documento.


**Returns:**
java.lang.String - il testo della filigrana.

### getColor() {#getColor--}
```
public final Color getColor()
```


Restituisce il colore della filigrana.
Questo metodo recupera il colore della filigrana applicata al documento.


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.awt.Color - il colore della filigrana.

### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


Restituisce il colore della filigrana in formato esadecimale.
Questo metodo recupera il colore della filigrana applicata al documento.


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.lang.String - il colore della filigrana in formato esadecimale.

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Imposta il colore della filigrana.
Questo metodo imposta il colore della filigrana applicata al documento.


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.awt.Color | Il colore della filigrana da impostare. |
|

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


Imposta il colore della filigrana.
Questo metodo imposta il colore della filigrana applicata al documento.


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | colorName | java.lang.String | Il colore della filigrana da impostare. |
|

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


Restituisce la posizione della filigrana.
Questo metodo restituisce la posizione della filigrana applicata al documento.


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.

### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


Imposta la posizione della filigrana.
Questo metodo imposta la posizione della filigrana applicata al documento.


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [Position](../../com.groupdocs.viewer.options/position) | La posizione della filigrana. |
|

### getSize() {#getSize--}
```
public final Size getSize()
```


Restituisce le dimensioni della filigrana.
Questo metodo recupera la dimensione della filigrana applicata al documento.


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.

### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


Imposta la dimensione della filigrana.
Questo metodo imposta la dimensione della filigrana da applicare al documento.


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.viewer.options/size) | La dimensione della filigrana. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Restituisce il nome del carattere usato per la filigrana.


**Returns:**
java.lang.String - il nome del carattere usato per la filigrana.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Imposta il nome del carattere usato per la filigrana.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il nome del carattere usato per la filigrana. |
|

