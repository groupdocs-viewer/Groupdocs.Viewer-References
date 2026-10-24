---
title: "KnownColors"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: 
type: docs
weight: 10
url: /it/java/com.groupdocs.viewer.drawing.rgb24color/knowncolors/
---
**Inheritance:**
java.lang.Object
```
public class KnownColors
```
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [tryFindColor(String keyword, Rgb24Color[] output)](#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---) | Cerca di trovare un colore per il suo nome stringa. |
|
|  | [tryFindName(Rgb24Color color, String[] name)](#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---) | Cerca di trovare il nome di un colore per il suo valore RGB. |
|
### tryFindColor(String keyword, Rgb24Color[] output) {#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---}
```
public static boolean tryFindColor(String keyword, Rgb24Color[] output)
```


Cerca di trovare un colore per il suo nome stringa.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | parola chiave | java.lang.String | Un nome di colore. |
|
|  | output | [Rgb24Color\[\]](../../com.groupdocs.viewer.drawing/rgb24color) | Il contenitore del risultato per il colore trovato, o CssLevel1.Black in caso di errore. |
|

**Returns:**
boolean - True se il colore è stato trovato con successo per nome, false altrimenti.

### tryFindName(Rgb24Color color, String[] name) {#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---}
```
public static boolean tryFindName(Rgb24Color color, String[] name)
```


Cerca di trovare il nome di un colore per il suo valore RGB.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | color | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) | Un'istanza di colore. |
|
|  | nome | java.lang.String[] | Il contenitore del risultato per il nome del colore trovato, o null in caso di errore. |
|

**Returns:**
boolean - True se il nome è stato trovato con successo per il colore dato, false altrimenti.

