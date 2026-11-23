---
title: "SpreadsheetFontInfo"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Incapsula i metadati e i dati binari di un carattere dal documento Spreadsheet caricato nell'istanza Viewer."
type: docs
weight: 16
url: /it/java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Incapsula i metadati e i dati binari di un carattere dal documento Spreadsheet, caricato nell'istanza Viewer. I documenti Spreadsheet non possono contenere caratteri incorporati, quindi questo carattere particolare, se restituito dal metodo Viewer.getAllFonts(), è installato nel sistema operativo in cui è in esecuzione GroupDocs.Viewer.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Nome della famiglia del carattere, senza stile, mai nullo o vuoto. |
|
|  | [getStyle()](#getStyle--) | Stile di questo font \\u2014 può essere Regular, Bold, Italic o BoldItalic. |
|
|  | [isStrikeout()](#isStrikeout--) | Indica se il carattere è barrato singolarmente. |
|
|  | [isUnderline()](#isUnderline--) | Indica se il carattere è sottolineato. |
|
|  | [getColor()](#getColor--) | Colore di questo carattere. |
|
|  | [getCharset()](#getCharset--) | Set di caratteri di questo carattere. |
|
|  | [getContent()](#getContent--) | Contenuto di questo carattere come array di byte. |
|
|  | [getFormat()](#getFormat--) | Formato di questo carattere. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serializza le informazioni di questo carattere come una regola @font-face e le scrive nello scrittore specificato. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Nome della famiglia del carattere, senza stile, mai nullo o vuoto.


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Stile di questo font \\u2014 può essere Regular, Bold, Italic o BoldItalic.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


Indica se il carattere è barrato singolarmente.


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Indica se il carattere è sottolineato.


**Returns:**
boolean
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


Colore di questo carattere.


**Returns:**
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
### getCharset() {#getCharset--}
```
public int getCharset()
```


Set di caratteri di questo carattere.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Contenuto di questo carattere come array di byte. Può essere null se sono disponibili solo i metadati.


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Formato di questo carattere.


**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serializza le informazioni di questo carattere come una regola @font-face e le scrive nello scrittore specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | output | java.io.Writer | Dispositivo in cui scrivere i dati di testo serializzati. |
|

