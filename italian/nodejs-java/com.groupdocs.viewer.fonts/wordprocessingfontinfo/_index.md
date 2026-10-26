---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Incapsula metainformazioni e dati binari di un font dal documento WordProcessing caricato nell'istanza Viewer."
type: docs
weight: 17
url: /it/nodejs-java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Incapsula i metadati e i dati binari di un carattere dal documento WordProcessing, caricato nell'istanza Viewer. Questo carattere è utilizzato nel contenuto del documento ed è incorporato all'interno del documento stesso o è installato nel sistema operativo in cui è in esecuzione GroupDocs.Viewer.

Classe immutabile. Le sue istanze sono prodotte e restituite dall'API pubblica di GroupDocs.Viewer e normalmente non dovrebbero essere create dall'utente. Per ulteriori dettagli, consultare la documentazione: https://docs.groupdocs.com/viewer/net/getting-used-fonts/
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Nome della famiglia del carattere, senza stile, mai nullo o vuoto. |
| [getAltFamilyName()](#getAltFamilyName--) | Nome alternativo della famiglia del carattere. |
| [getStyle()](#getStyle--) | Stile del carattere \\u2014 può essere Regular, Bold, Italic o BoldItalic. |
| [isEmbedded()](#isEmbedded--) | Indica se questo carattere è incorporato nel documento (true) o è un carattere di sistema (false). |
| [getFormat()](#getFormat--) | Formato di questo carattere. |
| [getContent()](#getContent--) | Contenuto di questo carattere come array di byte, o null se non disponibile. |
| [getCharset()](#getCharset--) | Set di caratteri di questo carattere. |
| [toString()](#toString--) | Restituisce informazioni di debug su questo carattere nel seguente modello: "nome stile, incorporato/sistema, formato" |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serializza le informazioni di questo carattere come regola CSS @font-face e le scrive nello writer specificato. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Nome della famiglia del carattere, senza stile, mai nullo o vuoto.

**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


Nome alternativo della famiglia del carattere. Se mancante, restituisce una stringa vuota.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Stile del carattere \\u2014 può essere Regular, Bold, Italic o BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Indica se questo carattere è incorporato nel documento (true) o è un carattere di sistema (false).

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Formato di questo carattere. Se sono presenti solo i metadati e il contenuto binario è mancante, può restituire FontFormat.UNKNOWN.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Contenuto di questo carattere come array di byte, o null se non disponibile.

**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


Set di caratteri di questo carattere.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Restituisce informazioni di debug su questo carattere nel seguente modello: "nome stile, incorporato/sistema, formato"

**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serializza le informazioni di questo carattere come regola CSS @font-face e le scrive nello writer specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| output | java.io.Writer | Writer per ricevere il CSS serializzato. |

