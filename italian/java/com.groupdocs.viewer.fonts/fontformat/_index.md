---
title: "FontFormat"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Rappresenta tutti i formati di carattere che possono essere presenti nella classe UsedFontInfo."
type: docs
weight: 11
url: /it/java/com.groupdocs.viewer.fonts/fontformat/
---
**Inheritance:**
java.lang.Object
```
public final class FontFormat
```

Rappresenta tutti i formati di font, che possono essere presenti nella classe UsedFontInfo.

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Unknown](#Unknown) | Formato di carattere sconosciuto o non valido. |
|
|  | [TrueType](#TrueType) | Formato di carattere TrueType (TTF). |
|
|  | [OpenType](#OpenType) | Formato di carattere OpenType (OTF). |
|
|  | [TrueTypeCollection](#TrueTypeCollection) | Formato di carattere TrueType Collection (TTC). |
|
|  | [EmbeddedOpenType](#EmbeddedOpenType) | Formato di carattere Embedded OpenType (EOT). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [toString(int format)](#toString-int-) | Converte un valore di formato in una stringa leggibile dall'uomo. |
|
### Unknown {#Unknown}
```
public static final int Unknown
```


Formato di carattere sconosciuto o non valido.


### TrueType {#TrueType}
```
public static final int TrueType
```


Formato di carattere TrueType (TTF).


### OpenType {#OpenType}
```
public static final int OpenType
```


Formato di carattere OpenType (OTF).


### TrueTypeCollection {#TrueTypeCollection}
```
public static final int TrueTypeCollection
```


Formato di carattere TrueType Collection (TTC).


### EmbeddedOpenType {#EmbeddedOpenType}
```
public static final int EmbeddedOpenType
```


Formato di carattere Embedded OpenType (EOT).


### toString(int format) {#toString-int-}
```
public static String toString(int format)
```


Converte un valore di formato in una stringa leggibile dall'uomo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | formato | int | il valore del formato del carattere |
|

**Returns:**
java.lang.String - una rappresentazione stringa del formato del carattere

