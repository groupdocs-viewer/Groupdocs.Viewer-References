---
title: "PresentationFontInfo"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Incapsula i metadati e i dati binari di un carattere utilizzato in un documento Presentation caricato nell'istanza Viewer."
type: docs
weight: 15
url: /it/java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

Incapsula i metadati e i dati binari di un carattere utilizzato in un documento Presentation, caricato nell'istanza Viewer. Questo carattere è usato nel contenuto del documento e può essere incorporato nel documento stesso o installato nel sistema operativo in cui è in esecuzione GroupDocs.Viewer.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Ottiene il nome della famiglia del carattere (mai nullo o vuoto). |
|
|  | [getStyle()](#getStyle--) | Ottiene lo stile del carattere: Regular, Bold, Italic o BoldItalic. |
|
|  | [isEmbedded()](#isEmbedded--) | Indica se questo carattere è incorporato nel documento caricato nell'istanza Viewer. |
|
|  | [getFormat()](#getFormat--) | Ottiene il formato del carattere (TrueType, OpenType, ecc.). |
|
|  | [getContent()](#getContent--) | Ottiene il contenuto binario del carattere, o null se i dati del carattere non sono disponibili. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serializza le informazioni di questo carattere nella regola CSS @font-face usando lo scrittore specificato. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Ottiene il nome della famiglia del carattere (mai nullo o vuoto).


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Ottiene lo stile del carattere: Regular, Bold, Italic o BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Indica se questo carattere è incorporato nel documento caricato nell'istanza Viewer. Nota: i documenti Spreadsheet non possono contenere caratteri incorporati, quindi per loro restituisce sempre false.


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Ottiene il formato del carattere (TrueType, OpenType, ecc.). Se sono disponibili solo i metadati, restituisce FontFormat.Unknown.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Ottiene il contenuto binario del carattere, o null se i dati del carattere non sono disponibili.


**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serializza le informazioni di questo carattere nella regola CSS @font-face usando lo scrittore specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | output | java.io.Writer | scrittore per scrivere il CSS (non deve essere null) |
|

