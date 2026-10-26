---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Incapsula le metainformazioni e i dati binari di un font dal documento Spreadsheet caricato nell'istanza Viewer."
type: docs
weight: 16
url: /it/nodejs-java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Incapsula le metainformazioni e i dati binari di un font dal documento Spreadsheet, caricato nell'istanza Viewer. I documenti Spreadsheet non possono contenere font incorporati, quindi questo font particolare, se restituito dal metodo Viewer.getAllFonts(), è installato nel sistema operativo su cui è in esecuzione GroupDocs.Viewer.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Nome della famiglia del carattere, senza stile, mai nullo o vuoto. |
| [getStyle()](#getStyle--) | Stile di questo font — può essere Regular, Bold, Italic o BoldItalic. |
| [isStrikeout()](#isStrikeout--) | Indica se il font ha una singola barratura. |
| [isUnderline()](#isUnderline--) | Indica se il font è sottolineato. |
| [getColor()](#getColor--) | Colore di questo font. |
| [getCharset()](#getCharset--) | Set di caratteri di questo carattere. |
| [getContent()](#getContent--) | Contenuto di questo font come array di byte. |
| [getFormat()](#getFormat--) | Formato di questo carattere. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serializza le informazioni di questo font come una regola @font-face e le scrive nello writer specificato. |
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


Stile di questo font — può essere Regular, Bold, Italic o BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


Indica se il font ha una singola barratura.

**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Indica se il font è sottolineato.

**Returns:**
boolean
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


Colore di questo font.

**Returns:**
com.groupdocs.viewer.drawing.Argb32Color
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


Contenuto di questo font come array di byte. Può essere nullo se sono disponibili solo le metainformazioni.

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


Serializza le informazioni di questo font come una regola @font-face e le scrive nello writer specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| output | java.io.Writer | Dispositivo in cui scrivere i dati di testo serializzati. |

