---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Incapsula meta-informazioni e dati binari di un carattere da un documento PDF caricato nell'istanza del Viewer."
type: docs
weight: 14
url: /it/nodejs-java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

Incapsula meta-informazioni e dati binari di un font da un documento PDF, caricato nell'istanza Viewer.

Questo carattere è usato nel contenuto del documento ed è uno dei seguenti:

 *  embedded inside the PDF document
 *  or installed in the operating system where GroupDocs.Viewer is running
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | Costruttore interno utilizzato dall'estrazione dei caratteri PDF. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Ottiene il nome della famiglia di caratteri. |
| [getStyle()](#getStyle--) | Ottiene lo stile di questo carattere. |
| [isEmbedded()](#isEmbedded--) | Restituisce se il carattere è incorporato nel documento PDF. |
| [isInstalled()](#isInstalled--) | Restituisce se il carattere è installato nel sistema operativo. |
| [getFormat()](#getFormat--) | Restituisce il formato del file del carattere. |
| [getContent()](#getContent--) | Restituisce il contenuto binario del carattere. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serializza questo carattere come una regola CSS @font-face. |
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


Costruttore interno utilizzato dall'estrazione dei caratteri PDF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| familyName | java.lang.String | nome della famiglia di caratteri |
| stile | com.groupdocs.viewer.fonts.FontStyles | stile (Regular, Bold, Italic, BoldItalic) |
| isEmbedded | boolean | true se il carattere è incorporato nel PDF |
| isInstalled | boolean | true se il carattere è installato nel sistema operativo |
| content | byte[] | dati binari del carattere (nullable) |
| format | int | formato del file del carattere |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Ottiene il nome della famiglia di caratteri.

**Returns:**
java.lang.String - stringa del nome della famiglia (mai null o vuota)
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Ottiene lo stile di questo carattere.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles - lo stile del carattere
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Restituisce se il carattere è incorporato nel documento PDF.

**Returns:**
boolean - true se incorporato
### isInstalled() {#isInstalled--}
```
public boolean isInstalled()
```


Restituisce se il carattere è installato nel sistema operativo.

**Returns:**
boolean - true se installato
### getFormat() {#getFormat--}
```
public int getFormat()
```


Restituisce il formato del file del carattere.

**Returns:**
int - l'enumerazione del formato del carattere
### getContent() {#getContent--}
```
public byte[] getContent()
```


Restituisce il contenuto binario del carattere.

**Returns:**
byte[] - array di byte o null se non disponibile
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serializza questo carattere come una regola CSS @font-face.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| output | java.io.Writer | writer su cui verrà scritto il CSS |

