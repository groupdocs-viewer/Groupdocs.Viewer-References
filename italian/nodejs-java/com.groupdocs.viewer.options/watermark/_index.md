---
title: "Watermark"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Rappresenta una filigrana di testo."
type: docs
weight: 37
url: /it/nodejs-java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

Rappresenta una filigrana di testo. Per i dettagli, vedere la [documentazione][].

La classe Watermark rappresenta una filigrana di testo nel componente GroupDocs.Viewer. Viene utilizzata per definire e applicare una filigrana all'output renderizzato dei documenti.

Esempio di utilizzo:

```

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
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/add-text-watermark/
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Watermark(String text)](#Watermark-java.lang.String-) | Inizializza una nuova istanza della classe Watermark. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getText()](#getText--) | Restituisce il testo del watermark. |
| [getColor()](#getColor--) | Restituisce il colore del watermark. |
| [getColorAsHex()](#getColorAsHex--) | Restituisce il colore del watermark in formato esadecimale. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Imposta il colore del watermark. |
| [setColor(String colorName)](#setColor-java.lang.String-) | Imposta il colore del watermark. |
| [getPosition()](#getPosition--) | Restituisce la posizione del watermark. |
| [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | Imposta la posizione del watermark. |
| [getSize()](#getSize--) | Restituisce le dimensioni del watermark. |
| [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | Imposta le dimensioni del watermark. |
| [getFontName()](#getFontName--) | Restituisce il nome del font usato per il watermark. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Imposta il nome del font usato per il watermark. |
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


Inizializza una nuova istanza della classe Watermark.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Il testo del watermark. |

### getText() {#getText--}
```
public final String getText()
```


Restituisce il testo del watermark. Questo metodo recupera il testo del watermark applicato al documento.

**Returns:**
java.lang.String - il testo del watermark.
### getColor() {#getColor--}
```
public final Color getColor()
```


Restituisce il colore del watermark. Questo metodo recupera il colore del watermark applicato al documento.

***Note:** The default value is the red color obtained from Color\#getRed().getRed().*

**Returns:**
java.awt.Color - il colore del watermark.
### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


Restituisce il colore del watermark in formato esadecimale. Questo metodo recupera il colore del watermark applicato al documento.

***Note:** The default value is the red color obtained from Color\#getRed().getRed().*

**Returns:**
java.lang.String - il colore del watermark in formato esadecimale.
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Imposta il colore del watermark. Questo metodo imposta il colore del watermark applicato al documento.

***Note:** The default value is obtained from Color\#getRed().getRed().*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.awt.Color | Il colore del watermark da impostare. |

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


Imposta il colore del watermark. Questo metodo imposta il colore del watermark applicato al documento.

***Note:** The default value is obtained from Color\#getRed().getRed().*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorName | java.lang.String | Il colore del watermark da impostare. |

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


Restituisce la posizione del watermark. Questo metodo restituisce la posizione del watermark applicato al documento.

***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).*

**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.
### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


Imposta la posizione del watermark. Questo metodo imposta la posizione del watermark applicato al documento.

***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Position](../../com.groupdocs.viewer.options/position) | La posizione del watermark. |

### getSize() {#getSize--}
```
public final Size getSize()
```


Restituisce le dimensioni del watermark. Questo metodo recupera le dimensioni del watermark applicato al documento.

***Note:** The default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).*

**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.
### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


Imposta la dimensione della filigrana. Questo metodo imposta la dimensione della filigrana da applicare al documento.

***Note:** The default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Size](../../com.groupdocs.viewer.options/size) | La dimensione della filigrana. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Restituisce il nome del font usato per il watermark.

**Returns:**
java.lang.String - il nome del carattere usato per la filigrana.
### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Imposta il nome del font usato per il watermark.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String | Il nome del carattere usato per la filigrana. |

